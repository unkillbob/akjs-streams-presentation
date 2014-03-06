```
var http = require('http'),
    fs = require('fs');

var pirateBay = http.createServer(function(req, res) {
    fs.readFile('photoshop.dmg', function(err, data) {
        res.end(data);
    });
});

pirateBay.listen(8080);
```
<!-- .element: class="javascript" -->
