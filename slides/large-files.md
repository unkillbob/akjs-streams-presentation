# Large Files

<br/>

```
fs.createReadStream('log.txt')
    .pipe(split())
    .pipe(processEachLineOfLog());
```
<!--.element: class="fragment javascript"-->
