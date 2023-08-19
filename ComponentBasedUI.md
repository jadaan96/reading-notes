## Component Based UI

#### What are the building blocks of a React app?

Components 
* Functional Components 
*  Calss Components

#### What is the difference between an HTML element and a React component?

A React component is a function that utilizes JSX, a special JavaScript syntax. These functions return processed HTML elements for rendering, thanks to a transpiler like Babel that converts JSX into executable JavaScript. Consequently, the HTML elements in a React component aren't plain; they undergo processing.

#### What is JSX and why do we use it?


It's a JavaScript syntax extension enabling you to embed HTML-like code within your JavaScript.

#### Describe the process of embedding JavaScript expressions in JSX:

Incorporating JavaScript expressions within JSX permits dynamic content generation, value computation, and direct integration of logic into your UI components.

#### Does React or JSX have any special features for iteration or conditional logic?

React allows using conditionals and loops to control what gets displayed on the screen, a capability not present when you escape the JSX syntax. This enables iterating through arrays of elements for collective rendering or conditionally showing components based on values.

#### How does React know to respond to a user’s inputs? What word indicates that a React component manages data with a Hook?

Through Hooks, specifically useState, you can create variables akin to environmental variables that dynamically change with events or invoked functions. The inclusion of 'use' in its name signifies the initialization of a hook.

#### How can two react components share data?


Hooks like useState offer the capability to share information between components. Achieve this by placing your state at a higher level than the components you intend to share it between. Subsequently, pass the state as props to these child components.

#### Render and Commit

#### What are the three steps of refreshing a React UI?

Triggering,Rendering,Committing

#### How do you trigger updates to a component after the initial render?
by changing it’s state.

#### Does React recreate DOM nodes on every rerender?

Correct, the system operates by solely updating the specific portions of the DOM that experience changes. It achieves this by conducting meticulous assessments of component inputs and outputs. If a node's inputs remain unchanged, producing an anticipated output, the DOM remains unaffected and no updates are executed.

#### After React has updated the DOM, what still needs to happen before the user sees the change?

it has to be rendered on the browser again, or in react it’s called re-painting.

#### Note the naming conventions in the Airbnb React/JSX Style Guide. What pattern(s) do you see?

* Component names should adhere to PascalCase, whereas instances of these components should be in camelCase.

* File names must consistently match the component names.

* Avoid using props that share names with DOM reserved words.

* When importing files that serve as the root of a directory, employ only the directory name for the import




