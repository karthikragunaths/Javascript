Redux itself can be used by itslef.

react-redux - binds react with redux

redux-thunk is a middleware for redux which allows us to access the 
dispatch method so that we can make asyn actions

Providers - from react-redux
    it is a react component - it is the glue between react and redux
    wrap everything inside provider component inside return

    Provider has state - store

store
    holds the whole state tree of your application
    only way to change the state inside the store is to dispatch an action on it

    createstore (reducer, [preloadedState], [enhancer])