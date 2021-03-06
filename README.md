[![Build Status](https://img.shields.io/travis/mohebifar/lebab.svg?style=flat-square)](http://travis-ci.org/mohebifar/lebab) [![License](http://img.shields.io/:license-mit-brightgreen.svg?style=flat-square)](http://mohebifar.mit-license.org) [![JS.ORG](https://img.shields.io/badge/js.org-xto6-ffb400.svg?style=flat-square)](http://js.org)

# Lebab
![Lebab](https://raw.githubusercontent.com/mohebifar/lebab-logo/master/logo.png)

**lebab** transpiles your ES5 code to ES2015. It does exactly the opposite of what babel does. If you want to understand what lebab exactly does, [try the live demo](http://lebab.io/try-it).


## Usage
Install it using npm :

```bash
$ npm install -g lebab
```

Transpile your old-fashioned code using the `lebab` cli tool.
```bash
lebab es5.js -o es6.js
```

## Supported Features

* Function/Prototypes to Classes
* Callback to Arrow functions
* String concatenation to Template Strings
* Using `let` and `const` instead of `var`
* Default arguments instead of `a = a || 2`
* Function properties in objects to Object methods
