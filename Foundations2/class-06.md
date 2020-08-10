## NODE.JS
# An Introduction to Node.js 

https://www.sitepoint.com/an-introduction-to-node-js/

<ul>
<li>Event-based, non-blocking, asynchronous I/O runtime that uses Google's V8 JavaScript engine and libuv library. (lolllll what)
<li>Chrome's V8 JavaScript Engine: an open-source JS engine that runs in Chrome and others (Brava, Opera, Vivaldi). Compiles JS directly to native machine code that computers can execute.
<li>Node isn't executed in the browser, it's the V8 engine PLUS other features, like a file system API, HTTP library and a variety of OS-related util methods. 
<li> Essentially, it's a program that we can use to execute JS on our computers.
<li>npm: a package manager that comes with Node.
</ul>

# Node binaries vs Version manager
<ul>
<li>Use a version manager rather than downloading official Node?
<li>Allows you to install multiple versions and switch between them at-will
<li> https://www.sitepoint.com/quick-tip-multiple-versions-node-nvm/
</ul>

# Console
<ul>
<li> Console info: https://nodejs.org/api/console.html#console_console
<li> "Hello, World!" >>> node hello.js
</ul>

## Compatability

<ul>
<li> Node has excellent support for modern JavaScript (generally won't have to worry about compatability issues)
</ul>

# npm

<ul>
<li> npm -v: 6.14.5
<li>THE package manager for JavaScript (ooh lala) and also the world's largest software registry
<li>There are over 1,000,000 packages of JS code available to download with billions of downloads per week!!!!! 
</ul>

## Installing a Package Globally
<ul>
<li> npm install -g jshint
<li> will install jshint (static code analysis tool) https://www.npmjs.com/package/jshint
<li> can be used to lint and fix errors (eg ESb-related errors: add /* jshint esversion: 6 */)
</ul>

## Installing a package locally
<ul>
<li>npm init -y will create and auto-populate a package.json file, THEN >> npm install lodash --save (which is a util library) will create a test.s file and add:
</ul>

    const _ = require('lodash');

    const arr = [0, 1, false, 2, '', 3];
    console.log(_.compact(arr));

<ul>
<li>THEN use `node test.js` and you should see [1, 2, 3 ] output to the terminal!!!!! okay but why does this help
<li> https://www.npmjs.com/package/lodash
</ul>

## Working with the package.json file
<ul>
<li>node_modules: where npm has saved lodash and any libraries that lodash depends on. can be created at any time by running npm install.
<li>https://www.sitepoint.com/beginners-guide-node-package-manager/
</ul>

## What is Node.js used for?
<ul>
<li>installing (npm) and running (Node) various build tools (Webpack, ESLint, Gulp.js, Mocha, Chai, etc)
<li> Yarn vs npm: https://www.sitepoint.com/yarn-vs-npm/
<li> LETS US RUN JAVASCRIPT ON THE SERVER
    <ul>
    <li> Node is single-threaded and EVENT-DRIVEN which means everything happens in reaction to one event
    <li>implements asynchronous (non-blocking) behavior
<li>can be used as a scripting language to automate repetitive or error-prone tasks
