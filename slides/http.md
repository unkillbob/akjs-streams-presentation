# web

<br/>

```
var http = require('http');

http.createServer(function(req, res) {
    // req: Readable stream
    // res: Writable stream
});
```
<!--.element: class="fragment javascript"-->

<br/>

```
var net = require('net');
var client = net.connect({ port: 8124 }, function() {
    // ...
});
```
<!--.element: class="fragment javascript"-->
