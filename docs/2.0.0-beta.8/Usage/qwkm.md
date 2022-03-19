# gode.qwkm(message)

Convert between [QWERTY](https://en.wikipedia.org/wiki/QWERTY) and [Kedmanee](https://en.wikipedia.org/wiki/Thai_Kedmanee_keyboard_layout) layout in both ways. Takes 1 argument and return converted string.

* `message` *string* User's message.

### CommonJS

```js
const gode = require('gode.js')

let message = 'l;ylfu'
gode.qwkm(message)
//returns สวัสดี
```

### ES6 *(in this case, typescript)*

```js
import gode from 'gode.js'

let message: string = 'l;ylfu'
gode.qwkm(message)
//returns สวัสดี
```