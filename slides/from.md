# from

### Easily create readable streams

<br/>

```
var from = require('from');

var readData = from(function getChunk(count, next) {
    this.emit('data', someData);

    if (finished) { this.emit('end'); }

    next(); // or just `return true;` if sync
});

readData.pipe(writable);
```
<!-- .element: class="fragment javascript" -->
