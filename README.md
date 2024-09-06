[![view on npm](https://badgen.net/npm/v/dmd-plugin-example)](https://www.npmjs.org/package/dmd-plugin-example)
[![npm module downloads](https://badgen.net/npm/dt/dmd-plugin-example)](https://www.npmjs.org/package/dmd-plugin-example)
[![Gihub repo dependents](https://badgen.net/github/dependents-repo/jsdoc2md/dmd-plugin-example)](https://github.com/jsdoc2md/dmd-plugin-example/network/dependents?dependent_type=REPOSITORY)
[![Gihub package dependents](https://badgen.net/github/dependents-pkg/jsdoc2md/dmd-plugin-example)](https://github.com/jsdoc2md/dmd-plugin-example/network/dependents?dependent_type=PACKAGE)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg)](https://github.com/feross/standard)

# dmd-plugin-example

This is a simple example demonstrating how to construct a dmd plugin. It adds a generated date to the bottom of your API docs.

To make your own plug-in, clone this project, edit and publish to npm. 

To use a plug-in in your project, first install it as a devDependency: 

```
$ npm install dmd-plugin-example --save-dev
```

Then pass the plug-in name to `jsdoc2md` or `dmd`:

```
$ jsdoc2md --plugin dmd-plugin-example lib/*.js 
```

