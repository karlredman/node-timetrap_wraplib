# Project: Timetrap wrapper lib for node.js

Author: [Karl N. Redman](https://karlredman.github.io/)

## Note:

This library is a work in progress. More info soon.

## Description:

This is a wrapper library for the [Timetrap](https://github.com/samg/timetrap) command line ruby application. The library offers and api for synchronous and asynchronous timetrap system calls.

* See the project [pindex.md](https://github.com/karlredman/node-timetrap_wraplib/blob/master/pindex.md) file for directory layout.
* See the project [Timetrap.example.js](https://github.com/karlredman/node-timetrap_wraplib/blob/master/examples/Timetrap.example.js) file for directory layout.

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
