
# grammarjs-operator

![experimental](http://img.shields.io/badge/status-experimental-orange.svg?style=flat)

Operator plugin.

## Example

```js
var Grammar = require('grammarjs-grammar');
var operator = require('grammarjs-operator');
var grammar = new Grammar('my-grammar');
grammar.use(operator());
```