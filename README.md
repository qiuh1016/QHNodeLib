# QHNodeLib


Install
------------
npm install qhnodelib

Usage
------------
const Logger = require('qhnodelib').Logger;
global.Log = Logger({echo: 'info', errorLevel: 'debug', filename: __dirname + '/logs.log'});
