# PlusUltra Exchange Plugins

This library exports a collection of exchange-rate plugins for use with [`plusultra-core-js`](https://github.com/PlusUltraAPT/plusultra-core-js).

Use it like this:

```js
import { makeContext } from 'plusultra-core-js'
import { coinbasePlugin, shapeshiftPlugin } from 'plusultra-exchange-plugins'

makeContext({
  plugins: [coinbasePlugin, shapeshiftPlugin]
})
```

The supported plugins are:

* `coinbasePlugin` - Converts from BTC to most fiat currencies.
* `shapeshiftPlugin` - Converts from BTC to most common altcoins.
