# fullstack-serverless-tutorial
Repo for Udemy course

## Requirements

1) [nodejs](https://nodejs.org/en/)
2) [typescript](https://www.typescriptlang.org/)
3) [firebase](https://github.com/firebase/firebase-tools)

## Install

1) Initialize the app with typescript compatibility
```
npx create-react-app my-app --template typescript
```

2) Install dependencies
```
npm install --save typescript @types/node @types/react @types/react-dom @types/jest
npm install firebase-tools
```

3) Init firebase
```
firebase login
firebase init
```

4) Install plugins
```
npm install redux react-redux redux-form react-router redux-thunk react-loadable
```

```
redux: manage states of app (api or firebase)
react-redux: connect state with components
redux-form: store form data in redux state
react-router: handle routes
redux-thunk: manage effects (connect firebase, execute server logic)
react-loadable: division of code
```