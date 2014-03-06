##  Writable Streams

### Can be piped to but not from
<!-- .element: class="fragment" -->

<br/>

```
process.stdout
```
<!-- .element: class="fragment javascript" -->

```
fs.createWriteStream('/path/to/file.txt', {
    encoding: 'utf8'
})
```
<!-- .element: class="fragment javascript" -->
