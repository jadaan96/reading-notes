## Summary of Thinking in React

**Step 1: Break Down the UI into a Component Hierarchy**



**Step 2: Create a Static React Version**

**Step 3: Determine the Minimal Complete UI State**



**Step 4: Identify the State's Location**



**Step 5: Implement Inverse Data Flow**


##  Component’s Memory

**Why Local Variables Might Not Suffice for React Components**

Local variables are not persistent across renders, meaning their values are not retained between different render cycles.

**Argument and Return of the useState Hook**

The argument provided to the `useState` hook is the initial value for a state variable. It returns an array containing the state variable itself and a function used to update the state.

**Accessing State Across Components**

Components in React have isolated states. To enable state sharing between components, it's necessary to move the shared state to a common parent component and pass it down as props to child components.

