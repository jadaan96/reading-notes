# First Principle of Redux
The first principle of Redux is often referred to as "Single Source of Truth." It means that all the data needed to render your application's user interface is stored in a single JavaScript object called the "store."

## Store
In Redux, a "store" is a central repository holding your application's entire state. It serves as the one place where all your application's data is stored, acting as the single source of truth.

### getState()
Use the `getState()` method to retrieve the current state of the Redux store. It returns the current state object, representing the entire state tree of your application.

### dispatch(action)
The `dispatch(action)` method is used to send actions to the Redux store, triggering state updates through reducers. You dispatch actions whenever you want to change the state in your Redux store.

### subscribe(listener)
Use `subscribe(listener)` to add a listener function that gets called whenever the state in the Redux store changes. It's like setting up a notification system for state changes.

### combineReducers()
`combineReducers()` is a Redux function that helps organize and manage different parts of your application's state. It's like organizing puzzle pieces into categories or slices, making it easier to work with and understand. It's especially useful when you have multiple reducers handling different parts of your application's state, and you want to combine them into a single state tree.
