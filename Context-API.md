## Context-API
### Choosing the State Structure
#### Summarize the five principles for structuring state.

* **Group related state**. If you always update two or more state variables at the same time, consider merging them into a single state variable.
* **Avoid contradictions in state**. When the state is structured in a way that several pieces of state may contradict and “disagree” with each other, you leave room for mistakes. Try to avoid this.
 * **Avoid redundant state**. If you can calculate some information from the component’s props or its existing state variables during rendering, you should not put that information into that component’s state.

* **Avoid duplication in state**. When the same data is duplicated between multiple state variables, or within nested objects, it is difficult to keep them in sync. Reduce duplication when you can.
 
 * **Avoid deeply nested state**. Deeply hierarchical state is not very convenient to update. When possible, prefer to structure state in a flat way.


## Passing State Deeply with Context

**1- What problem do Contexts aim to solve?**
>  They provide a way to make certain information available to any component within a specific subtree, regardless of how deeply nested those components are.

**2-What is one technique to try before useContext?**
 passing props down the component tree. 
 
 **3-What hook complements useContext for complex applications**
  In more complex applications, you can complement useContext with the useReducer hook. useReducer helps manage complex state in React applications a