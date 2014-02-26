# map-stream

<br/>

```
var map = require('map-stream');

var transform = map(function(data, callback) {
    // transform
    callback(null, newData);
    // emit 'error' event
    callback(err);
    // drop data (filter)
    callback();
});

readable.pipe(transform).pipe(writable);
```
<!-- .element: class="javascript" -->
