# concat-stream

### Concatenate stream data

<br/>

```
var concat = require('concat-stream');

var gatherData = concat(function(allTheDatas) {
    // concatenated Buffer/String or an array
});

readable.pipe(gatherData);
```
<!-- .element: class="fragment javascript" -->
