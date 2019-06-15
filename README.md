[![Build Status](https://drone-github.parasynthetic.dev/api/badges/karlredman/node-timetrap_wraplib/status.svg)](https://drone-github.parasynthetic.dev/karlredman/node-timetrap_wraplib)
[![npm version](https://img.shields.io/npm/v/node-timetrap_wraplib.svg)](https://www.npmjs.com/package/node-timetrap_wraplib)
[![issues](https://img.shields.io/github/issues/karlredman/node-timetrap_wraplib.svg)](https://github.com/karlredman/node-timetrap_wraplib/issues)
[![license](https://img.shields.io/github/license/karlredman/node-timetrap_wraplib.svg)](https://github.com/karlredman/node-timetrap_wraplib/blob/master/LICENSE)

# Project: Timetrap wrapper lib for node.js

Author: [Karl N. Redman](https://karlredman.github.io/)

This is a wrapper library for the [Timetrap](https://github.com/samg/timetrap) command line ruby application. The library offers an api for synchronous and asynchronous timetrap system calls.

* See the project [pindex.md](https://github.com/karlredman/node-timetrap_wraplib/blob/master/pindex.md) file for directory layout.
* See the project [Timetrap.example.js](https://github.com/karlredman/node-timetrap_wraplib/blob/master/examples/Timetrap.example.js) file for directory layout.

## Note:

This library is a work in progress. More info soon.

## Requirements:
* Linux (currently)
* Node.js v8.4+
* a running [Timetrap](https://github.com/samg/timetrap) installation with some data

## Features

## Upcoming Features:
* better documentation
* commands:
	* kill
	* move
	* archive

## Installation:

## Example Configuration / Usage:
### Configuration:
* `examples/Timetrap.example.js`
	1. in `function main` specify the database file to watch
		* ...if you want to run the database file monitoring functionality
	2. uncomment the code you want to run
	3. run the example
	```
	node ./Timetrap.example.js
	```

## API Documentation:

## F.A.Q:

## Thank You and Credit To:
* The author and contributors of the [Timetrap](https://github.com/samg/timetrap) project for an elegant and useful time keeping solution.
* The community at [StackOverFlow](https://stackoverflow.com).
* Node.js contributors.
* jest contributors.
