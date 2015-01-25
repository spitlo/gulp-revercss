# gulp-revercss
Gulp wrapper for revercss

##Example use:
``` JavaScript
gulp.task( 'revercss', function() {
  gulp.src('src/revcss/**/*.revcss')
    .pipe(revercss({
      minified: true
    }))
    .pipe(concat('main.css'))
    .pipe(gulp.dest('./build/css'));
})
```
##Options
Same as [revercss](https://github.com/spitlo/revercss/)
