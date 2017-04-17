# object.entries-ponyfill

> [`Object.entries()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/entries) [ponyfill](https://ponyfill.com)

## built-in

You should polyfill your targeted browser environments automatically with [polyfill.io](https://polyfill.io), rather than using non-tailored approach like this ponyfill. Node =< 7 has `Object.entries` natively. Therefore, you probably only need this ponyfill for Node < 7.

## install

```sh
$ npm install object.entries-ponyfill
```

## example

```js
const entries = require('object.entries-ponyfill')

entries({ foo: 123, bar: 456 })
// => [ [ 'foo', 123 ], [ 'bar', 456 ] ]
```
