# HTML Boilerplate
HTML Boilerplate is a simple, professional template for building HTML sites.  No frameworks, no libraries, and no extra bloat.

**Note: This boilerplate is not intended for sites which need to support Internet Explorer.**

## Quick Start
1. Clone the repo and navigate to that directory

  ```bash
    git clone https://github.com/aleksnyder/html-boilerplate.git new-site
    cd new-site
  ```
2. Install dependencies with your favorite package manager [npm](https://www.npmjs.com/): `npm install`
  or [yarn](https://yarnpkg.com/): `yarn`.
3. Compile the site assets using `npm run build` or `yarn build` depending on your preferred package manager.
4. Open `index.html` and start coding!

## Features
* A lightweight, finely-tuned starter template.
* Includes:
  * Customized reset based on [A Modern CSS Reset](https://hankchizljaw.com/wrote/a-modern-css-reset/)
  * Babel to transpile newer JavaScript features for browser which do not support
    those features
* Placeholder Open Graph elements and attributes.
* An example package.json file with NPM scripts built in to jumpstart application
  development
* SASS mixins for media queries, responsive ratio, responsive fonts, and more.
* Useful CSS helper classes.
* Defaut print styles

## Available commands
HTML Boilerplate includes several useful npm scripts in the `package.json` file.  Each npm script is preceded by `npm run` or `yarn`.

| Name           | Script details                                                                  |
| :-------------- | :----------------------------------------------------------------------------- |
| build:css      | Compiles SCSS stylesheets and minify the compiled CSS file                      |
| uglify         | Uglifies and minifies the JavaScript files                                      |
| webp           | Transforms jpg, png images in `src/img` to webp format                          |
| imagemin       | Optimize images in the `src/img` directory and outputs those images `build/img` |

## License

The code is available under the [MIT license](LICENSE).
