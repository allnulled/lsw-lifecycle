# lsw-lifecycle

Lifecycle tool for LSW.

This package depends by default on:

 - [`@allnulled/lsw-cycler`](https://github.com/allnulled/lsw-cycler).
 - [`@allnulled/lsw-trigger`](https://github.com/allnulled/lsw-trigger).
 - [`@allnulled/lsw-database`](https://github.com/allnulled/lsw-database).
 - [`@allnulled/lsw-schema`](https://github.com/allnulled/lsw-schema).
 - [`@allnulled/lsw`](https://github.com/allnulled/lsw).

## Installation

```sh
npm i -s @allnulled/lsw-lifecycle
```

## Importation

From node.js you have to:

```sh
require("node_modules/@allnulled/lsw-lifecycle/lsw-lifecycle.js");
```

From html you have to:

```html
<script src="node_modules/@allnulled/lsw-lifecycle/lsw-lifecycle.js"></script>
```

## API

The global variable is found at `window.LswLifecycle`.

It is an instance of `LswCycler` with a predefined set of methods, defined on its `LswLifecycle.steps` property.

## Conclusion

This package is an internal dependency of `lsw` set of dependencies. You can take it as reference, and overwrite its defaults to fit your needs, or get inspiration on how to use `lsw-cycler`, which is the prototypal root of this artifact.