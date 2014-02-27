# `pipe()`

### Readable ==> Writable
<!-- .element: class="fragment" -->

### Manages back-pressure for you
<!-- .element: class="fragment" -->

<br/>

```
readable.pipe(writable) // returns writable
```
<!-- .element: class="fragment javascript" -->

```
readable.pipe(transform1)
    .pipe(transform2)
    // ...
    .pipe(writable);
```
<!-- .element: class="fragment javascript" -->
