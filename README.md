# Labels [![Build Status](https://travis-ci.org/cferdinandi/labels.svg)](https://travis-ci.org/cferdinandi/labels)
Lightweight CSS labels.

[Download Labels](https://github.com/cferdinandi/labels/archive/master.zip) / [View the demo](http://cferdinandi.github.io/labels/).

**In This Documentation**

1. [Getting Started](#getting-started)
2. [Browser Compatibility](#browser-compatibility)
3. [How to Contribute](#how-to-contribute)
4. [License](#license)
5. [Changelog](#changelog)



## Getting Started

Compiled and production-ready code can be found in the `dist` directory. The `src` directory contains development code.

### 1. Include Labels on your site.

```html
<link rel="stylesheet" href="dist/css/labels.css">
```

Labels is [built with Sass](http://sass-lang.com/) for easy customization. If you don't use Sass, that's ok. The `css` folder contains compiled vanilla CSS.

The `_config.scss` and `_mixins.scss` files are the same ones used in [Kraken](http://cferdinandi.github.io/kraken/), so you can drop the `_labels.css` file right into Kraken without making any updates. Or, adjust the variables to suit your own project.

### 2. Add the markup to your HTML.

```html
<span class="label">Default Label</span>
<span class="label label-success">Success Label</span>
<span class="label label-danger">Danger Label</span>
<span class="label label-warning">Warning Label</span>
```

And that's it, you're done. Nice work!



## Browser Compatibility

Labels works in all modern browsers, and IE 6 and above.



## How to Contribute

In lieu of a formal style guide, take care to maintain the existing coding style. Don't forget to update the version number, the changelog (in the `readme.md` file), and when applicable, the documentation.



## License

Labels is licensed under the [MIT License](http://gomakethings.com/mit/).



## Changelog

Labels uses [semantic versioning](http://semver.org/).

* v1.2.0 - August 25, 2014
	* Switched from Sass Lib to Ruby Sass.
* v1.1.0 - June 23, 2014
	* Converted to gulp.js workflow.
	* Updated naming conventions.
	* Added minified versions of files.
	* Updated to three number versioning system.
* v1.0 - December 2, 2013
	* Initial release.