# webpack-full-config
____
## Short description
This project is a complete Webpack 5 config for fast development with dev server and to quickly build a web project by minifying CSS, JS, correctly connecting fonts and other assets files.

**Important: This configuration does not contain the configuration of preprocessors and frameworks.**
____
## Project structure
![Project Tree](https://github.com/neveleneves/webpack-full-config/blob/master/src/assets/img/treeconfig.PNG)
* **Root files**
  * **.babelrc** - local configuration (Babel)
  * **package-lock.json** - dependency file
  * **package.json** - main info file about project
  * **postcss.config.js** - config file for PostCSS (used plugins and more)
* **Folders & other files**
  * **build** -webpack configs file for dev, build mode
    * **webpack.base.conf.js** - main webpack config file for all modes
    * **webpack.build.conf.js** - config file for build mode
    * **webpack.dev.conf.js** - config file for dev mode
  * **src** - all source for build 
    * **intex.html** - main html-page
    * **intex.js** - main js-script for include styles, js-modules
    * **assets** - folder for CSS, fonts, img and another assets files
       * **css** - folder for css stylies
          * **fonts.css** - for include fonts 
          * **reset.css** - css file for reset the original browser styles
          * **style.css** - main css file with styles
       * **fonts** - folder for fonts
       * **img** - folder for imges
    * **js** - folder for js-modules includes to index.js
    * **static** - folder for sitemap, favicon files 
____
## Packages & Plugins
* **Packages**
  * **Webpack** - Project build system.
  * **Babel** - JS-transcompiler.
  * **PostCSS** - Converts the original CSS to modified CSS using plugins.
  * **webpack-merge** - Groups multiple config files into one.
  * **css-loader**, **file-loader** - Loaders for different project files. 
  * **webpack-dev-server** - Dev server for auto updates assets files.
  
* **Plugins**
  * **autoprefixer** - plugin for PostCSS, auto prefixes in CSS styles.
  * **css-mqpacker** - plugin for PostCSS, optimization of media queries.
  * **cssnano** - plugin for PostCSS, modular minimizer for optimization CSS.
  * **copy-webpack-plugin** - plugin for Webpack, copy files from src to build.
  * **html-webpack-plugin** - plugin for Webpack, build html-pages. 
  * **mini-css-extract-plugin** - plugin for Webpack, extracting CSS into separate files.
