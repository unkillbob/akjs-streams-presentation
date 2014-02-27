# Reading

<br/>

```
readableStream.on('readable', function() {
    var data = readable.read();
    // .read() returns null if the stream is finished.
});
```
<!-- .element: class="javascript" -->

```
// Reading a "Classic" stream
classic.on('data', function(data) {
    console.log(data);
});
classic.on('end', function() {
    console.log('The End.');
});
```
<!-- .element: class="fragment javascript" -->

