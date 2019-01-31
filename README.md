# bs-moment

[![Build Status](https://travis-ci.org/reasonml-community/bs-moment.svg?branch=master)](https://travis-ci.org/reasonml-community/bs-moment)
[![npm](https://img.shields.io/npm/v/bs-moment.svg)](https://www.npmjs.com/package/bs-moment)

[BuckleScript](https://github.com/bloomberg/bucklescript) bindings for [Moment Timezone](https://momentjs.com/timezone/).

## Status

This package is still 🚧 WIP 🚧, but new bindings are added *as needed* instead of actively. Feel free to create an issue or PR if you find anything missing.

## Mutations

This binding takes an opinionated approach to mutations, e.g. `moment().add`, `moment().startOf`, and bind them with names like `mutableAdd` and `mutableStartOf`. To compensate that, there's an immutable version named `add` and `startOf` which takes a `moment().clone` first before applying the mutations.

## Deprecations

Deprecated methods (e.g. `moment().days` in favor of `moment().day`) are not included in this binding.
