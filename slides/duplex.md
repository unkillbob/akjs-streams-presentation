##  Duplex Streams

### Bi-directional
<!-- .element: class="fragment" -->

<br/>

```
var net = require('net');
var client = net.connect({ port: 8124 }, function() {
    // ...
});
```
<!-- .element: class="fragment javascript" -->
