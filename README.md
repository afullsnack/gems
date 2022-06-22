# Gems
A list of various resources discovered on the internet for use in my various projects

Table-of-content
- [Frontend react](#react-frontend)
- [Backend nodejs](#nodejs-backend)
- [Products software](#products-software)
- [Developer tools](#dev-tools)

## Frontend (React) <a name="react-frontend" />

### Filepond (file uploading package for nodejs)
[Filepond](https://www.npmjs.com/package/filepond)<br/>
A JavaScript library that can upload anything you throw at it, optimizes images for faster uploads, and offers a great, accessible, silky smooth user experience.

```:installation
npm install filepond --save
```



### Apex Charts (A simple and viualy stunning charting library)
[Apexcharts](https://www.npmjs.com/package/apexcharts)<br/>
A modern JavaScript charting library that allows you to build interactive data visualizations with simple API and 100+ ready-to-use samples. Packed with the features that you expect, ApexCharts includes over a dozen chart types that deliver beautiful, responsive visualizations in your apps and dashboards. ApexCharts is an MIT licensed open-source project that can be used in commercial and non-commercial projects.

```:installation
npm install apexcharts --save
```



### Progressbar (A progressbar indicator with usefull tools)
[Progressbar](https://www.npmjs.com/package/progressbar)<br/>
A nice wrapper around TJ Holowaychuck's node-progress with chaining, domains, and steps

```:installation
npm install --save progressbar
```


### Draggable (A fully featured drag and drop library)
[Draggable](https://www.npmjs.com/package/draggable)<br/>
High performance, fully cross browser, full featured drag and drop in a tiny (2k gzipped), dependency-free package.

```:installation
npm install draggable --save
```


### Check password strength (Check the strength of a password with pre-saved RegEx)
[Check password strength](https://www.npmjs.com/package/check-password-strength)<br/>
A simple way to check that password strength of a certain passphrase. A password strength checker based from Javascript RegEx.

```:installation
npm i check-password-strength --save
```


### UseAnimation (A collection of animations)
[react-useanimations](https://github.com/useAnimations/react-useanimations)<br/>
React-useanimations is a collection of free animated open source icons for React.js.

```:installation
npm install -S react-useanimations
````

#### Usage
```js
import React from 'react';
import UseAnimations from 'react-useanimations';
// EVERY ANIMATION NEEDS TO BE IMPORTED FIRST -> YOUR BUNDLE WILL INCLUDE ONLY WHAT IT NEEDS
import github from 'react-useanimations/lib/github'

const App = () => <UseAnimations animation={github} />;

export default App;
```


## Backend nodejs <a name="nodejs-backend" />

### NanoId (Generate string ID for js)
[NanoId](https://www.npmjs.com/package/nanoid)<br/>
A tiny, secure, URL-friendly, unique string ID generator for JavaScript.

```:installation
npm install nanoid --save
```



### Lowdb (A lightweight local DB)
[Lowdb](https://www.npmjs.com/package/lowdb)<br/>
Tiny local JSON database for small projects 🦉

```:installation
npm install lowdb --save
```


### tRPC (A lightweight typesafe way to consume API endpoints)
[tRPC](https://trpc.io)
tRPC allows you to easily build & consume fully typesafe APIs, without schemas or code generation.

⚠️ Requirements: tRPC requires TypeScript > 4.1 as it relies on Template Literal Types.

Server installation: For implementing tRPC endpoints and routers. Install in your server codebase.
```:installation
npm install @trpc/server
```
Client installation: For making typesafe API calls from your client. Install in your client codebase.
```:installation
npm install @trpc/client
```

React app library: For generating a powerful set of React hooks for querying your tRPC API. Powered by react-query.
```:installation
npm install @trpc/react react-query
```

Next.js utitlity library: A set of utilies for integrating tRPC with Next.js.
```:installation
npm install @trpc/next
```



## Products (Software and Cloud) <a name="products-software" />



## Dev tools (Developer tools) <a name="dev-tools" />

### Warp terminal (A blazingly fast terminal)
[Warp.dev](https://www.warp.dev/)<br/>
The terminal for the 21st century
WARP IS A BLAZINGLY FAST, RUST-BASED TERMINAL REIMAGINED FROM THE GROUND UP TO WORK LIKE A MODERN APP.



### Commander.js (A CLI creation tool)
[Commander.js](https://github.com/tj/commander.js)<br/>
The complete solution for node.js command-line interfaces.

```:installation
npm install commander
```

Example<br/>
```js
const { program } = require('commander');

program
  .option('--first')
  .option('-s, --separator <char>');

program.parse();

const options = program.opts();
const limit = options.first ? 1 : undefined;
console.log(program.args[0].split(options.separator, limit));
```
