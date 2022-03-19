# gode.qwkm(message)

Convert between [Dvorak](https://en.wikipedia.org/wiki/Dvorak_keyboard_layout) and [Kedmanee](https://en.wikipedia.org/wiki/Thai_Kedmanee_keyboard_layout) layout in both ways. Takes 1 argument and return converted string.

* `message` *string* User's message.

### CommonJS

```js
const gode = require('gode.js')

let message = '8cf/pgh'
gode.dvkm(message)
//returns ครับพี่
```

### ES6 *(in this case, typescript)*

```js
import gode from 'gode.js'

let message: string = '8cf/pgh'
gode.dvkm(message)
//returns สครับพี่
```