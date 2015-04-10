#How to: gulp with less [Gulp - The streaming build system]

###1. Open Terminal
Check if npm is installed: 
```sh
$ npm -v 
```
if not: 
```sh
$ npm install osx
```

###2. Install gulp globally: 
```sh
$ npm install -g gulp
```
###3. Change directory to your progect folder:
```sh 
$ cd /Applications/MAMP/htdocs/project
``` 
and: 
```sh
$ npm init
```


###4. It will ask you to create new package.json, just follow the guidlines

###5. Install all the dependencies
```sh
$ npm install gulp-less gulp-autoprefixer gulp-minify-css gulp-jshint gulp-concat gulp-uglify gulp-imagemin gulp-notify gulp-rename gulp-livereload gulp-cache gulp-plumber gulp-sourcemaps gulp-minify-html del --save-dev
```

###6. Create and configure your gulpfile.js

###7. Do 
```sh
$ gulp watch 
```
and enjoy!

NOTE: if you already have gulpfile.js and package.json = you only have to do first two steps
