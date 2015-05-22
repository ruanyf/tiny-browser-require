# Tiny Browser Require

A tiny, simple CommonJS require() implemetation in browser-side, only 30+ lines.

## Usage

First put `require.js` on your page.

```html
<script src="require.js" />
```

Then use `require.register` to register your module.

```javascript
require.register("browser/debug.js", function(module, exports, require){
  // Module code goes here
});
```

Now you can use require function to load the module.

```javascript
var debug = require("browser/debug.js");
```

## License

MIT
