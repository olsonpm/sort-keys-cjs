## What is this

A simple cjs wrapper to the [sort-keys](https://github.com/sindresorhus/sort-keys) module

## Why make a wrapper ?

Since version 5 of sort-keys, the module [only supports esm import](https://github.com/sindresorhus/sort-keys/commit/c265d92177cad270e92f0911dc9df13a2a2c0cff).
In order to continue using this module conveniently I decided to wrap it in [fix-esm](https://www.npmjs.com/package/fix-esm).

## Why declare sort-keys as a peer dependency ?

Doing this allows you to decide the version of sort-keys in your project.
