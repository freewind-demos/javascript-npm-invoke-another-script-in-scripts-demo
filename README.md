JavaScript Npm Invoke Another Script in "scripts" Demo
======================================================

```
npm install
npm run hello
```

You will see:

```
$ npm run hello

> @ hello /Users/freewind/workspace/javascript-npm-invoke-another-script-in-scripts-demo
> node hello.js

Hello, Javascript
```

You will see:

```
$ npm run demo

> @ demo /Users/freewind/workspace/javascript-npm-invoke-another-script-in-scripts-demo
> npm run hello && echo OK


> @ hello /Users/freewind/workspace/javascript-npm-invoke-another-script-in-scripts-demo
> node hello.js

Hello, Javascript
OK
```