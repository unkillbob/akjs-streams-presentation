```
var http = require('http'),
    fs = require('fs'),
    path = require('path');

http.createServer(function(req, res) {
    fs.createReadStream('photoshop.dmg').pipe(res);
});

server.listen(8080);
```
<!-- .element: class="javascript" -->
