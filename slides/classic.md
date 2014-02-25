##  Classic Streams

### Old interface from Node 0.4
<!-- .element: class="fragment" data-fragment-index="0" -->

#### Triggered whenever a stream has a `data` listener registered
<!-- .element: class="fragment" data-fragment-index="1" -->

```
process.stdin.on('data', function(buf) {
    console.log(buf);
});
```
<!-- .element: class="fragment javascript" data-fragment-index="1" -->
