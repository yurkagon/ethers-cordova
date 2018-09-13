ethers-cordova
=========

Complete Ethereum wallet implementation and utilities in JavaScript, clonned from [ethers.js](https://github.com/ethers-io/ethers.js/) and modifed for getting better perfomance on mobile apps that use [Cordova](https://cordova.apache.org/)

Installing
----------

NPM

```
npm i ethers-cordova
```
That package uses `scrypt` plugins. If you run the app on Android and IOS, will be used cordova plugin [cordova-plugin-scrypt](https://github.com/Crypho/cordova-plugin-scrypt) that is much faster on mobile devices. Add it to your project:
```
cordova plugin add cordova-plugin-scrypt
```
In other platforms such as browser (or you didnt install `cordova-plugin-scrypt`) will be used [scrypt-js](https://github.com/ricmoo/scrypt-js)

Documentation
-------------
For more information check the [original repository](https://github.com/ethers-io/ethers.js/)

Browse the [API Documentation](https://docs.ethers.io/ethers.js/html/) online.

Donations
---------

If you want to buy some coffee for the original author, he won't say no **:o)**

Ethereum: `0xEA517D5a070e6705Cc5467858681Ed953d285Eb9`


License
-------

Completely MIT Licensed. Including ALL dependencies.
