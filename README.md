# token.js

Simple utility to generate a random token including the ability to define the length.

```
var token = require('token.js');
console.log("Generate a 6 character token:", token());
console.log("Generate a 32 character token:", token(32));
```