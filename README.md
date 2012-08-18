# Static Site

A simple environment for building static HTML/CSS/JS projects, based on
the [Guard](https://github.com/guard/guard) gem.

_Static Site_ includes the [Sass (SCSS)](http://sass-lang.com) CSS preprocessor, [Coffee
Script](http://coffeescript.org) for nicer JavaScript, and [Live
Reload](https://github.com/guard/guard-livereload). [Guard](https://github.com/guard/guard) watches the project files and makes sure files are concatinated/compiled/refreashed automatically.

[Normalize.css](https://github.com/necolas/normalize.css) is included to ensure a nice level playing field for styling. A development build of [Modernizr](http://modernizr.com) is also included - be sure to swap this out for a custom, minified version suitable for your project.

The project structure is setup to serve files from the `/public` directory, for compatibility with the [Pow](http://pow.cx) development web server.


## Usage

1. Clone the repo.
2. Run `guard`.
3. Profit.

