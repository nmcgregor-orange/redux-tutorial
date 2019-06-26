clone it->

then install:
```
npm install
```
then run:
```
npm start
```

great tutorial: https://www.valentinog.com/blog/redux/

## 3 useful redux methods:

### __getState()__ - accesses the current state of the application

### __dispatch()__ - dispatches an action

### __subscribe()__ - listening on state changes

## Connecting Redux to React:

### use library called __react-redux__

### main method to use is __connect__ which connects a React component with the Redux store

### fundamental arguments to use are:

### • __mapStateToProps__ - makes the props available to a React component

### • __mapDispatchToProps__ - makes actions available to a React component so you are able to dispatch actions from the React component 

### Use a __provider__ to wrap your React application to make it aware of Redux's entire store

• make a habit of validation props with PropType (or use Typescript)