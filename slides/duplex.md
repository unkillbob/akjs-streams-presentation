##  Duplex Streams

### Bi-directional
<!-- .element: class="fragment" -->

```
var net = require('net');
var client = net.connect({ port: 8124 }, function() {
    // ...
});
```
<!-- .element: class="fragment" -->
