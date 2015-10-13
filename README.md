# react-issue-viewer
A sample issue viewer built with React, along with ES6, webpack, live reload, less, mocha etc...


## Steps
```
# clone this repo
git clone https://github.com/vlt5/react-issue-tracker.git

# installation
npm install

# start the dev server
npm start  
(Then visit http://localhost:3000/)

# test cases
npm run test
(Then visit http://localhost:3001/webpack-dev-server/test)

```


## About
I've been hesitating whether shall I use [Flux](https://facebook.github.io/flux/) or shall I use those existing components out there.(like [React Router](https://github.com/rackt/react-router)).  
But finally I deceide to keep it simple, simply passing down callback instead of using flux and use light weight client-side routing libruary [page](https://visionmedia.github.io/page.js/) instead of react-router.

In addition, there're many boilerplates out there that has already integrated with React, ES6, live reload, gulp etc... But again, I kind of feel it's too much for this simple project, so I make my own boilerplate. Whenever I need something, I just `npm install --save` it. And it's much more fun!
