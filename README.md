# `@reason-react-native/slider`

[![Build Status](https://github.com/reason-react-native/slider/workflows/Build/badge.svg)](https://github.com/reason-react-native/slider/actions)
[![Version](https://img.shields.io/npm/v/@reason-react-native/slider.svg)](https://www.npmjs.com/@reason-react-native/slider)
[![Chat](https://img.shields.io/discord/235176658175262720.svg?logo=discord&colorb=blue)](https://reasonml-community.github.io/reason-react-native/discord/)

[ReasonML](https://reasonml.github.io) /
[BuckleScript](https://bucklescript.github.io) bindings for
[`@react-native-community/slider`](https://github.com/react-native-community/react-native-slider).

Exposed as `ReactNativeSomething` module.

`@reason-react-native/slider` X.y._ means it's compatible with
`@react-native-community/slider` X.y._

## Installation

When
[`@react-native-community/slider`](`https://github.com/react-native-community/react-native-slider`)
is properly installed & configured by following their installation instructions,
you can install the bindings:

```console
npm install @reason-react-native/slider
# or
yarn add @reason-react-native/slider
```

`@reason-react-native/slider` should be added to `bs-dependencies` in your
`bsconfig.json`. Something like

```diff
{
  //...
  "bs-dependencies": [
    "reason-react",
    "reason-react-native",
    // ...
+    "@reason-react-native/slider"
  ],
  //...
}
```

---

## Changelog

Check the [changelog](./CHANGELOG.md) for more informations about recent
releases.

---

## Contribute

Read the
[contribution guidelines](https://github.com/reason-react-native/.github/blob/master/CONTRIBUTING.md)
before contributing.

## Code of Conduct

We want this community to be friendly and respectful to each other. Please read
[our full code of conduct](https://github.com/reason-react-native/.github/blob/master/CODE_OF_CONDUCT.md)
so that you can understand what actions will and will not be tolerated.
