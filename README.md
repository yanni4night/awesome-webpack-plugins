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

1. [json](http://npmjs.org/json)
Loads file as JSON

1. [raw](http://npmjs.org/raw)
Loads raw content of a file (as utf-8)

1. [xml](http://npmjs.org/xml)
Loads XML as JSON

1. [file](http://npmjs.org/file)
Emits the file into the output folder and returns the (relative) url.

1. [url](http://npmjs.org/url)
The url loader works like the file loader, but can return a Data Url if the file is smaller than a limit.

1. [image](http://npmjs.org/image)
Compresses your images. Ideal to use together with file or url.

1. [img](http://npmjs.org/img)
Load and compress images with imagemin.

1. [base64-image](http://npmjs.org/base64-image)
Load image as base64 string src

1. [vue](http://npmjs.org/vue)
Load single-file Vue.js components as modules, with loader-support for preprocessors.

1. [babel](http://npmjs.org/babel)
Turn ES6 code into vanilla ES5 using Babel.

1. [awesome-typescript](http://npmjs.org/awesome-typescript)
Loads TypeScript like JavaScript with watching support. 

1. [html](http://npmjs.org/html)
Exports HTML as string, require references to static resources.

1. [yaml](http://npmjs.org/yaml)
 Converts YAML to JSON

1. [yml](http://npmjs.org/yml)
 Converts YAML to JavaScript object, optionally omitting blacklisted keys

1. [ejs](http://npmjs.org/ejs)
Loads EJS (underscore( templating engine) template and returns a pre-compiled function

1. [mustache](http://npmjs.org/mustache)
Pre-compiles Mustache templates with Hogan.js and returns a function

1. [nunjucks](http://npmjs.org/nunjucks)
Precompiles nunjucks templates

1. [style](http://npmjs.org/style)
Add exports of a module as style to DOM

1. [css](http://npmjs.org/css)
Loads css file with resolved imports and returns css code

1. [sass](http://npmjs.org/sass)
Loads and compiles a scss file

1. [stylus](http://npmjs.org/stylus)
Loads and compiles a stylus file

1. [postcss](http://npmjs.org/postcss)
Post-process CSS with Autoprefixer and other PostCSS plugins

1. [autoprefixer](http://npmjs.org/autoprefixer)
Add vendor prefixes to CSS rules using values from Can I Use

1. [eslint](http://npmjs.org/eslint)
PreLoader for linting code using ESLint.

1. [image-size](http://npmjs.org/image-size)
Loads an image and returns its dimensions and type

1. [csslint](http://npmjs.org/csslint)
PreLoader for linting code using CSSLint
