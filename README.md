## Redux Essentials Example - Counter App

## Overview 
In [Part 1: Redux Overview and Concepts](https://redux.js.org/tutorials/essentials/part-1-overview-concepts), we looked at how Redux can help us build maintainable apps by giving us a single central place to put global app state. We also talked about core Redux concepts like dispatching action objects, using reducer functions that return new state values, and writing async logic using thunks. 

In [Part 2: Redux App Structure](https://redux.js.org/tutorials/essentials/part-2-app-structure), we saw how APIs like `configureStore` and `createSlice` from Redux Toolkit and `Provider` and `useSelector` from React-Redux work together to let us write Redux logic and interact with that logic from our React components.

## Setup
If you'd like to try create this project on your own computer, you can start a new Create-React-App project using the Redux template:

npx create-react-app redux-essentials-example --template redux

Or you can clone this project
```shell
git clone https://github.com/ismaeldevmw/redux-essentials-example-counter-app.git
cd redux-essentials-example-counter-app
npm install
npm run dev
```