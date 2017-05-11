Apache OpenWhisk Web action redirecting request to Express applications

How to use
==========

The basic usage is:

```
const app = require('./server');
const forward = require('openwhisk-expressjs')(app);

function main(args) {
  return forward(args);
}

exports.main = main;
```
