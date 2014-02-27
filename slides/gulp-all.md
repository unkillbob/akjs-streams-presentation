## Putting it all together...

<br/>

```
gulp.task('scripts', function() {
    return gulp.src('./scripts/**/*.js')
        .pipe(uglify())
        .pipe(concat('all.js'))
        .pipe(gulp.dest('./dist'));
});

gulp.task('default', ['scripts'], function() {
    gulp.watch('./scripts/**/*.js', ['scripts']);
});
```
<!-- .element: class="javascript" -->
