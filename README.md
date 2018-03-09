# fast-af

Curated collection of fastest JavaScript algorithms.

- [`extend()`](#extend)
- [`shallowEqual()`](#shallowequal)
- [`deepEqual()`](#deepequal)
- [`stableStringify()`](#stablestringify)


## `extend()`

Extends arbitrary number object (similar how `Object.assign()` works).

```js
const {extend} = require('fast-af/extend');

extend(a, b, {foo: 'bar'});
```


## `shallowEqual()`

Shallow compares two objects for equality.

```js
const {shallowEqual} = require('fast-af/shallowEqual');

const isEqual = shallowEqual({foo: 'bar'}, {foo: 'bar'});
```


## `deepEqual()`

Compares recursively JavaScript objects for equality.

```js
const {deepEqual} = require('fast-af/deepEqual');

const isEqual = deepEqual({foo: 'bar'}, {foo: 'bar'});
```


## `stableStringify()`

Predictably stringifies plain JavaScript objects.

```js
const {stableStringify} = require('fast-af/stableStringify');

const str = stableStringify({foo: 'bar'});
```
