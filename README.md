# React SpinJS

[![npm](https://img.shields.io/badge/npm-v4.0.0-blue.svg)](https://www.npmjs.com/package/react-spinjs-new)

This is build on top of the fantastic spinner library, [spin.js](http://fgnass.github.io/spin.js/). This exposes spin.js as a component.

# Usage

```javascript
import ReactSpinner from 'react-spinjs';

// Put a default spinner
<ReactSpinner/>

// Pass in a config object
// See the documentation for spin.js
<ReactSpinner config={configObject}/>

// For convenience, pass in just a config
<ReactSpinner color="white"/>
```
