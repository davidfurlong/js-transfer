# js-transfer

JSON2 with support for undefined, NaN, Infinity, -Infinity

# Usage

```js

import transfer from 'js-transfer';

transfer.parse(transfer.stringify([undefined, 1, undefined, NaN, Infinity, -Infinity]));

```
