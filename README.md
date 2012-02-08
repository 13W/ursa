rsab
====

This Node module provides wrappers for the RSA public/private key
crypto functionality of OpenSSL.

This module was inspired by
[node-rsa](https://github.com/chrisa/node-rsa) by Chris Andrews,
though I (danfuzz) don't think there's any code remaining from that
implementation other than a few lines in the `wscript` build file.

Installing
----------

```shell
npm install rsab
```

Or grab the source and

```shell
node-waf configure build
```

Testing
-------

```shell
node ./test/test.js
```

Usage
-----

See the doc comments and tests.

License
-------

Apache 2. See the top-leve file `LICENSE.txt`.