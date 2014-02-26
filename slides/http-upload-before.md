```
var http = require('http'),
    fs = require('fs');

http.createServer(function(req, res) {
    fs.readFile('photoshop.dmg', function(err, data) {
        res.end(data);
    });
});

server.listen(8080);
```
<!-- .element: class="javascript" -->
