##  Transform Streams

### Transform input and produce output
<!-- .element: class="fragment" -->

```
var zlib = require('zlib');
var gzip = zlib.createGzip(); // Readable/Writable transform stream
```
<!-- .element: class="fragment" -->
