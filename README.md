# atom-gulp-snippets [![Build Status](https://secure.travis-ci.org/manolenso/atom-gulp-snippets.png?branch=master)](http://travis-ci.org/manolenso/atom-gulp-snippets)

Coffeescript & Javascript Gulp snippets
inspired by  [Gulp-cheatsheet](https://github.com/osscafe/gulp-cheatsheet)
## Development
```sh
$ cd ~/.atom/packages
$ git clone https://github.com/manolenso/atom-gulp-snippets
$ cd atom-gulp-snippets
$ apm install
$ apm link
```
----
## Javascript: _gulp-javascript.cson_
---

#### [guv] Gulp plugin require

```javascript
var ${1:plugin-variable} = require('gulp-${2:plugin-name}');$3
```

#### [gut] Gulp task Array

```javascript
gulp.task('${1:my_task}', ['$2'], function() {
    ${3://Do stuff}
});$4
```

#### [guo] Gulp Pipe Option

```javascript
.pipe($1({$2:'$3'}))$4
```
#### [guw] Gulp Task Watch

```javascript
gulp.watch('$1', ['$2']);$3
```

#### [gup] Gulp Pipe

```javascript
.pipe(${1:name}('${2:file}'))$3
```

#### [guw] Gulp Task Watch

```javascript
gulp.task('watch', function () {
  gulp.watch('$1', ['$2'])$3
});$4
```
----
## Gulp Coffeescript: _gulp-coffee.cson_
----



## License
Copyright (c) 2014 . Licensed under the MIT license.
