## Setting it all up

<br/>

```
$ npm install -g gulp
```
<!-- .element: class="fragment bash" -->

```
$ npm install --save-dev gulp gulp-util
```
<!-- .element: class="fragment bash" -->

<br/>

```
$ atom gulpfile.js
```
<!-- .element: class="fragment bash" -->

```
var gulp = require('gulp');
gulp.task('default', function() {
    // build all the things
});
```
<!-- .element: class="fragment javascript" -->

<br/>

```
$ gulp
```
<!-- .element: class="fragment bash" -->
