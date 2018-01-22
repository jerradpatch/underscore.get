#Underscore.get


## Usage

### For Node.js, Browserify and Webpack

Install from npm

    npm install underscore.get

Require individual functions

```javascript
const {get} = require("underscore.get");

get(obj, 'a[0].b', defaultValue);
```

Or use Mixin

```javascript
const getMixin = require("underscore.get");
_.mixin(getMixin);
_.get(obj, 'a[0].b', defaultValue);
```
