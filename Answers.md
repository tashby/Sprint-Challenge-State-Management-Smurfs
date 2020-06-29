1. What problem does the context API help solve?
Helps you pass info to components that need it while keeping your state un affected.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

Actions dispatch commands from components to a reducer. A reducer tells the component how to update state. The store contains the current updated state of the application. It is also keeps track of original state.

3. What is the difference between Application state and Component state? When would be a good time to use one over the other?

Application and component state differ in that application state is global; and allows components to access it. Component state is contained to the component; but can access application state.

4. Describe `redux-thunk`, what does it allow us to do? How does it change our `action-creators`?

Thunk is middleware. Middleware assists in running asynchronous operations. This allows action creators to flow info through the middleware; as opposed to directly to the reducer. This allows dynamic state as opposed to the same state everytime.

5. What is your favorite state management system you've learned and this sprint? Please explain why!

I like redux as it has a lot of documentation and resources.
