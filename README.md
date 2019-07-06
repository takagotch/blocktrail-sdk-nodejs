### blocktrail-sdk-nodejs
---
https://github.com/blocktrail/blocktrail-sdk-nodejs

```js
var blocktrail = require('blocktrail-sdk');
console.log("1234456789 Satoshi to BTC: ", blocktrail.toBTC(123456789));
console.log("1.23456789 BTC Satoshi: ", blocktrail.toSatoshi(1.23456789));


function onLoadWorkerLoadAsmCrypto(worker) {
  worker.postMessage({
    method: 'importScripts',
    script: document.location.protocol + '//' + document.location.host + '/build/asmcrypto.min.js'
  });
}
```

```sh
npm install blocktrail-sdk
jshint main.js lib/ test/
jscs main.js lib/ test/
```

```
```


