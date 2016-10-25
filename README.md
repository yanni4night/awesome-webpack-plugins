# awesome-webpack-plugins

A list of awesome `Webpack` plugins/loaders.

## Plugins

1. [html-webpack-plugin](http://npmjs.org/html-webpack-plugin)
This plugin generates a solid base html page for your web application with all your webpack generated css and js files built in. Supports custom templates, favicon, html-minifications and more.

1. [webpack-shell-plugin](http://npmjs.org/webpack-shell-plugin)
This plugin allows you to run any shell commands before or after webpack builds. This will work for both webpack and webpack-dev-server.

1. [bell-on-bundler-error-plugin](http://npmjs.org/bell-on-bundler-error-plugin)
This plugin gets notification on bundler build errors. On that occasion, a bell character will be written to STDERR output.

1. [webpack-browser-plugin](http://npmjs.org/webpack-browser-plugin)
This plugin enables your webpack builds to automatically launch it's application on a browser.

1. [favicons-webpack-plugin](http://npmjs.org/favicons-webpack-plugin)
This plugin automatically generates over 30 favicons (configurable) for Android, iOS, and the different desktop browsers from one source png. Integrates well with the html-webpack-plugin.

1. [extract-text-webpack-plugin](http://npmjs.org/extract-text-webpack-plugin)
This plugin moves every require("style.css") in entry chunks into a separate css output file. So your styles are no longer inlined into the javascript, but separate in a css bundle file (styles.css). If your total stylesheet volume is big, it will be faster because the stylesheet bundle is loaded in parallel to the javascript bundle.

## Loaders

1. [json-loader](http://npmjs.org/json-loader)
Loads file as JSON

1. [raw-loader](http://npmjs.org/raw-loader)
Loads raw content of a file (as utf-8)

1. [xml-loader](http://npmjs.org/xml-loader)
Loads XML as JSON

1. [file-loader](http://npmjs.org/file-loader)
Emits the file into the output folder and returns the (relative) url.

1. [url-loader](http://npmjs.org/url-loader)
The url loader works like the file loader, but can return a Data Url if the file is smaller than a limit.

1. [image-loader](http://npmjs.org/image-loader)
Compresses your images. Ideal to use together with file or url.

1. [img-loader](http://npmjs.org/img-loader)
Load and compress images with imagemin.

1. [base64-image-loader](http://npmjs.org/base64-image-loader)
Load image as base64 string src

1. [vue-loader](http://npmjs.org/vue-loader)
Load single-file Vue.js components as modules, with loader-support for preprocessors.

1. [babel-loader](http://npmjs.org/babel-loader)
Turn ES6 code into vanilla ES5 using Babel.

1. [awesome-typescript-loader](http://npmjs.org/awesome-typescript-loader)
Loads TypeScript like JavaScript with watching support. 

1. [html-loader](http://npmjs.org/html-loader)
Exports HTML as string, require references to static resources.

1. [yaml-loader](http://npmjs.org/yaml-loader)
 Converts YAML to JSON

1. [yml-loader](http://npmjs.org/yml-loader)
 Converts YAML to JavaScript object, optionally omitting blacklisted keys

1. [ejs-loader](http://npmjs.org/ejs-loader)
Loads EJS (underscore( templating engine) template and returns a pre-compiled function

1. [mustache-loader](http://npmjs.org/mustache-loader)
Pre-compiles Mustache templates with Hogan.js and returns a function

1. [nunjucks-loader](http://npmjs.org/nunjucks-loader)
Precompiles nunjucks templates

1. [style-loader](http://npmjs.org/style-loader)
Add exports of a module as style to DOM

1. [css-loader](http://npmjs.org/css-loader)
Loads css file with resolved imports and returns css code

1. [less-loader](http://npmjs.org/less-loader)
Loads and compiles a less file

1. [sass-loader](http://npmjs.org/sass-loader)
Loads and compiles a scss file

1. [stylus-loader](http://npmjs.org/stylus-loader)
Loads and compiles a stylus file

1. [postcss-loader](http://npmjs.org/postcss-loader)
Post-process CSS with Autoprefixer and other PostCSS plugins

1. [autoprefixer-loader](http://npmjs.org/autoprefixer-loader)
Add vendor prefixes to CSS rules using values from Can I Use

1. [eslint-loader](http://npmjs.org/eslint-loader)
PreLoader for linting code using ESLint.

1. [image-size-loader](http://npmjs.org/image-size-loader)
Loads an image and returns its dimensions and type

1. [csslint-loader](http://npmjs.org/csslint-loader)
PreLoader for linting code using CSSLint
