# gode.convert(EngLayout, ThaLayout, message)

Universal convert method. Takes 3 arguments and return converted string.

* `EngLayout` *string: 'QWERTY' | 'Dvorak'* User's English keyboard layout.
* `ThaLayout` *string: 'Kedmanee' | 'Manoonchai'* User's Thai keyboard layout.
* `message` *string* User's message.

### CommonJS

```js
const gode = require('gode.js')

let message = 'l;ylfu'
gode.convert('QWERTY', 'Kedmanee', message)
//returns สวัสดี
```

### ES6 *(in this case, typescript)*

```js
import gode, {EngLayout, ThaLayout} from 'gode.js'

let message: string = 'l;ylfu'
gode.convert('QWERTY' as EngLayout, 'Kedmanee' as ThaLayout, message)
//returns สวัสดี
```