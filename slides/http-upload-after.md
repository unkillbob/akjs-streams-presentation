```
var http = require('http'),
    fs = require('fs');

var pirateBay = http.createServer(function(req, res) {
    fs.createReadStream('photoshop.dmg').pipe(res);
});

pirateBay.listen(8080);
```
<!-- .element: class="javascript" -->
