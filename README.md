# Static Site

A simple environment for building static HTML/CSS/JS projects, based on the [Guard](https://github.com/guard/guard) gem.

_Static Site_ includes the [Sass (SCSS)](http://sass-lang.com) CSS preprocessor, [Coffee Script](http://coffeescript.org) for nicer JavaScript, and [Live Reload](https://github.com/guard/guard-livereload). Pages are run through [Jekyll](https://github.com/mojombo/jekyll), and [Guard](https://github.com/guard/guard) watches the project files to make sure files are concatenated/compiled/refreshed automatically.

[Normalize.css](https://github.com/necolas/normalize.css) is included to ensure a nice level playing field for styling. A development build of [Modernizr](http://modernizr.com) is also included - be sure to swap this out for a custom, minified version suitable for your project.

The project structure is set up to serve files from the `/public` directory, for compatibility with the [Pow](http://pow.cx) development web server.


## Compatibility

Normalize.css and the included CSS modules use features supported in the major modern browsers, and IE 8. Support for IE 7 and below is not intended.


## Usage

1. Clone the repo.
2. Run `guard`.
3. Profit.
