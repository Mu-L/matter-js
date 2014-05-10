### Building and Contributing

To build you must first install [node.js](http://nodejs.org/) and [grunt](http://gruntjs.com/), then run

	npm install

This will install the required build dependencies, then run

	grunt dev

which is a task that builds the `matter-dev.js` file, spawns a `connect` and `watch` server, then opens `demo/dev.html` in your browser. Any changes you make to the source will automatically rebuild `matter-dev.js` and reload your browser for quick and easy testing.

Contributions are welcome, please ensure they follow the same style and architecture as the rest of the code. You should run `grunt test` to ensure `jshint` gives no errors. Please do not include any changes to the files in the `build` directory. 