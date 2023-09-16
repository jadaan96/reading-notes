### Why Create Multiple Reducers?
Multiple reducers are created to manage different parts of the application state separately. In a complex Redux application, it is often necessary to break down the state management into smaller, more manageable pieces. Each reducer is responsible for handling a specific part of the application's state, making the codebase more modular and maintainable.

### How to Combine Multiple Reducers
You can combine multiple reducers using the `combineReducers` utility provided by Redux. This function takes an object where each key represents a slice of the state, and each value is a reducer function responsible for managing that specific slice. It returns a single reducer that can be used to create the application's state tree.

### Managing State as an Immutable Object
Redux encourages managing state as an immutable object to ensure predictability and ease of debugging. When state is immutable, it becomes easier to track changes, as you can be sure that any modifications to the state result in a new state object, rather than modifying the existing one. This immutability helps with debugging, time-travel debugging, and avoiding unintended side effects.

### How `combineReducers` Assembles the New State Tree
`combineReducers` assembles the new state tree by taking an object where each key represents a slice of the state, and each value is a reducer function responsible for managing that slice. When an action is dispatched, `combineReducers` calls each individual reducer with the corresponding slice of the state, and then it combines the results into a single state tree.

### Defining Initial State in an App Using `combineReducers`
You can define the initial state for an app using `combineReducers` by providing an initial state object as the second argument to `combineReducers`. This initial state object should have the same structure as the state slices managed by the individual reducers.

### Splitting Reducing Functions for Complex Apps
You will want to split your reducing functions as your app becomes more complex to maintain a clear and organized code structure. Splitting reducers allows you to focus on specific parts of the state and their corresponding logic, making it easier to debug, test, and scale your application.

### Naming Convention for Reducers
A popular convention when naming reducers is to use descriptive names that indicate the slice of state they manage. For example, if you have a reducer responsible for managing the state of user data, you might name it `userReducer`. This naming convention helps developers quickly understand the purpose of each reducer in a large application.
    