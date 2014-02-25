##  Readable Streams

### Can be piped from but not to
<!-- .element: class="fragment" -->

```
process.stdin
```
<!-- .element: class="fragment javascript" -->

```
fs.createReadStream('/path/to/file.txt', {
    encoding: 'utf8'
})
```
<!-- .element: class="fragment javascript" -->
