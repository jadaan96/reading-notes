### Reducers
1- What is the motivation for adding a reducer?
> To reduce this complexity and keep all your logic in one easy-to-access place

2-What are actions in the context of a reducer? How are they different than setting state directly?
> Instead of telling React “what to do” by setting state, you specify “what the user just did” by dispatching “actions” from your event handlers. 

3-What common list operation is useReduce named for, and why?
>Although reducers can “reduce” the amount of code inside your component, they are actually named after the reduce() operation that you can perform on arrays.
The reduce() operation lets you take an array and “accumulate” a single value out of many

4-When should you switch from useState to useReducer?
> if  state management requirements become more complex, involve shared logic, or require better predictability, switching to useReducer 