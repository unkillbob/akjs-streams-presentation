##  Writable Streams

### Can be piped to but not from
<!-- .element: class="fragment" -->

```
process.stdout
```
<!-- .element: class="fragment" -->

```
fs.createWriteStream('/path/to/file.txt', { encoding: 'utf8' })
```
<!-- .element: class="fragment" -->
