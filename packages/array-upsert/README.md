<!-- DO NOT EDIT THIS FILE! THIS FILE WAS AUTOGENERATED BY TEMPLATE-MATE -->
<!-- SEE https://github.com/angus-c/just/blob/master/CONTRIBUTING.md#readme-template -->

## just-upsert

Part of a [library](https://anguscroll.com/just) of zero-dependency npm modules that do just do one thing.
Guilt-free utilities for every occasion.

[`🍦 Try it`](https://anguscroll.com/just/just-upsert)

```shell
npm install just-upsert
```
```shell
yarn add just-upsert
```

Upsert (update or insert) a value into an array at a target index

```js
import upsert from 'just-upsert';

upsert([1,2,3,4],-1,2) // [1,2,-1,4]
upsert(['a','b','c'],'d',6) // ['a','b','c','d']
```