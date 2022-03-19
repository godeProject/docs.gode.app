# gode.qwkm(message)

Convert between [Dvorak](https://en.wikipedia.org/wiki/Dvorak_keyboard_layout) and [Manoonchai](https://manoonchai.com/) layout in both ways. Takes 1 argument and return converted string.

* `message` *string* User's message.

### CommonJS

```js
const gode = require('gode.js')

let message = 'ocoe'
gode.dvmn(message)
//returns เกเร
```

### ES6 *(in this case, typescript)*

```js
import gode from 'gode.js'

let message: string = 'ocoe'
gode.dvmn(message)
//returns เกเร
```