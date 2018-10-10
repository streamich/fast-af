# fast-af

Curated collection of fastest JavaScript algorithms.

- [`extend()`](#extend)
- [`shallowEqual()`](#shallowequal)
- [`deepEqual()`](#deepequal)
- [`stableStringify()`](#stablestringify)


## `extend()`

Extends arbitrary number object (similar how `Object.assign()` works).

```js
import {extend} from 'fast-af/extend';

extend(a, b, {foo: 'bar'});
```


## `shallowEqual()`

Shallow compares two objects for equality.

```js
import {shallowEqual} from 'fast-af/shallowEqual';

const isEqual = shallowEqual({foo: 'bar'}, {foo: 'bar'});
```


## `deepEqual()`

Compares recursively JavaScript objects for equality.

```js
import {deepEqual} from 'fast-af/deepEqual';

const isEqual = deepEqual({foo: 'bar'}, {foo: 'bar'});
```


## `stableStringify()`

Predictably stringifies plain JavaScript objects.

```js
import {stableStringify} from 'fast-af/stableStringify';

const str = stableStringify({foo: 'bar'});
```
