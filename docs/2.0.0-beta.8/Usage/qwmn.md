# gode.qwkm(message)

Convert between [QWERTY](https://en.wikipedia.org/wiki/QWERTY) and [Manoonchai](https://manoonchai.com/) layout in both ways. Takes 1 argument and return converted string.

* `message` *string* User's message.

### CommonJS

```js
const gode = require('gode.js')

let message = 'sisd'
gode.qwmn(message)
//returns เกเร
```

### ES6 *(in this case, typescript)*

```js
import gode from 'gode.js'

let message: string = 'sisd'
gode.qwmn(message)
//returns เกเร
```