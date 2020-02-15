## Generators

### Usage

install: `npm install --save chemisax/generators`

```
// Generate some dummy things

const {generators} = require('generators')

let dummyData = new generators.DummyGenerator({ params })
```

TODO: It would be nice to update to use ES6 and import/export because it's cleaner, also object destructuring is useful, but we need to use a transpiler like babel. Maybe in the future?

IDEAL:
```
// Generate some dummy things

import {DummyGenerator} from 'generators'

let dummyData = new DummyGenerator({ params })
```
