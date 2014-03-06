## gulpfile.js cont'd

<br/>

```
gulp.task('scripts', ['lint'], function(done) {
    // return a stream, promise or call done
```
<!-- .element: class="fragment javascript" -->

```
    return gulp.src('./scripts/**/*.js') // readable
```
<!-- .element: class="fragment javascript" -->

```
        .pipe(uglify())
        .pipe(concat('all.js'))
```
<!-- .element: class="fragment javascript" -->

```
        .pipe(gulp.dest('./dist')); // through stream
});
```
<!-- .element: class="fragment javascript" -->

<br/>

```
gulp.task('default', ['lint', 'test'], function() {
    gulp.watch('{scripts,tests}/**', ['lint', 'test']);
});
```
<!-- .element: class="fragment javascript" -->
