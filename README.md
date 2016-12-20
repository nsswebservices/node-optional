#OPTIONAL

Node-optional allows you to optionally 'require' modules without surrounding everything with 'try/catch'.  Usage and installation is easy and this module itself is very easy and straightforward to use.

##Install

```
  npm install optional
```

##Usage

```javascript
var optional = require("./optional");

var express = optional("express");
var fs = optional("fs");

console.log("express: " + express);
console.log("fs: " + fs);
```

Output:
```
express: null
fs: [object Object]
```

##Changelog

###v0.1.4

 * Forked repository from https://github.com/tony-o/node-optional to https://github.com/nsswebservices/node-optional
 * Updated package.json version number to follow semver convension by removing 'v' prefix.
 
###v0.1.0-2

 * Corrected bug when trying to optionally include relative paths
 
 
