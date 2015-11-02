# jekyll-bootstrap-starter
A minimal, clean starting point using Jeykll and Bootstrap

## Local development
* Install:
  * [Jekyll](http://jekyllrb.com/docs/installation/)
  * [Bundler](http://bundler.io/#getting-started)
  * [SCSS-Lint](https://github.com/brigade/scss-lint#installation)
  * [node](https://nodejs.org/download/)
  * [gulp](https://github.com/gulpjs/gulp/blob/master/docs/getting-started.md)
  * Consider using [Homebrew](http://brew.sh/) to install some of the tools.
* Run:
  * `npm install`
  * `gulp`
  * `bundle install`
  * `jekyll serve --baseurl ''`
  * Running `gulp watch` comes in handy while developing.

## Highlights

### HTML
* Run `gulp html` to copy the generated `index.html` file from Jekyll.

### Scripts
* The script can be built and linted using `gulp scripts` and `gulp jshint`.
* The `gulpfile.js` represents a minimal build for this design.

### Styles
* Run `gulp styles` to build and `gulp scsslint` to lint.
* The styles are built using `gulp-autoprefixer` to keep the definitions clean of vendor prefix maintenance.
