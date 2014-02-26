# through

<br/>

```
var through = require('through');

var transform = through(function write(data) {
    this.queue(data);
}, function end() {
    this.queue(null);
});

readable.pipe(transform).pipe(writable);
```
<!-- .element: class="javascript" -->
