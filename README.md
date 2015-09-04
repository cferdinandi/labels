# Labels [![Build Status](https://travis-ci.org/cferdinandi/labels.svg)](https://travis-ci.org/cferdinandi/labels)
Lightweight CSS labels.

[Download Labels](https://github.com/cferdinandi/labels/archive/master.zip) / [View the demo](http://cferdinandi.github.io/labels/)



## Getting Started

Compiled and production-ready code can be found in the `dist` directory. The `src` directory contains development code.

### 1. Include Labels on your site.

```html
<link rel="stylesheet" href="dist/css/labels.css">
```

### 2. Add the markup to your HTML.

```html
<span class="label">Default Label</span>
<span class="label label-success">Success Label</span>
<span class="label label-danger">Danger Label</span>
<span class="label label-warning">Warning Label</span>
```

And that's it, you're done. Nice work!



## Installing with Package Managers

You can install Labels with your favorite package manager.

* **NPM:** `npm install cferdinandi/labels`
* **Bower:** `bower install https://github.com/cferdinandi/labels.git`
* **Component:** `component install cferdinandi/labels`



## Working with the Source Files

If you would prefer, you can work with the development code in the `src` directory using the included [Gulp build system](http://gulpjs.com/). This compiles, lints, and minifies code, and runs unit tests. It's the same build system that's used by [Kraken](http://cferdinandi.github.io/kraken/), so it includes some unnecessary tasks and Sass variables but can be dropped right in to the boilerplate without any configuration.

### Dependencies
Make sure these are installed first.

* [Node.js](http://nodejs.org)
* [Gulp](http://gulpjs.com) `sudo npm install -g gulp`

### Quick Start

1. In bash/terminal/command line, `cd` into your project directory.
2. Run `npm install` to install required files.
3. When it's done installing, run one of the task runners to get going:
	* `gulp` manually compiles files.
	* `gulp watch` automatically compiles files when changes are made and applies changes using [LiveReload](http://livereload.com/).



## Browser Compatibility

Labels works in all modern browsers, and IE 6 and above.



## How to Contribute

In lieu of a formal style guide, take care to maintain the existing coding style. Please apply fixes to both the development and production code. Don't forget to update the version number, and when applicable, the documentation.



## License

The code is available under the [MIT License](LICENSE.md).