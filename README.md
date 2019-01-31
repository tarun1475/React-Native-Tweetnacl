# react-native-tweetnacl

Port of [TweetNaCl](http://tweetnacl.cr.yp.to) / [NaCl](http://nacl.cr.yp.to/)
to JavaScript for modern browsers and Node.js. Public domain.

[![Build Status](https://travis-ci.org/dchest/tweetnacl-js.svg?branch=master)
](https://travis-ci.org/dchest/tweetnacl-js)

### ReactNative Example Project Code

Check : https://github.com/tarun1475/React-native-tweetnacl-demo/blob/master/App.js/

### How do I get set up?

1. Install

```sh
npm i --save react-native-tweetnacl
react-native link react-native-randombytes
# install latest rn-nodeify
npm i --save-dev mvayngrib/rn-nodeify
# install node core shims and recursively hack package.json files
# in ./node_modules to add/update the "browser"/"react-native" field with relevant mappings
./node_modules/.bin/rn-nodeify --hack --install
```

2. `rn-nodeify` will create a `shim.js` in the project root directory

```js
// index.ios.js or index.android.js or index.js
// make sure you use `import` and not require!
import "./shim.js";
// ...the rest of your code
```

### TweetNaCl docs

Checkout : https://github.com/dchest/tweetnacl-js/
