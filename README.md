# webpack-full-config
Full Webpack 5 config for quick development and project build
____
## Short description
This project is a complete Webpack 5 config for fast development with dev server and to quickly build a web project by minifying CSS, JS, correctly connecting fonts and other assets files.

**Important: This configuration does not contain the configuration of preprocessors and frameworks.**
____
## Project structure
![Project Tree](https://github.com/neveleneves/webpack-full-config/blob/master/src/assets/img/treeconfig.PNG)
* **Root files**
  * .babelrc *- local configuration (Babel)
  * package-lock.json *- dependency file
  * package.json *- main info file about project
  * postcss.config.js *- config file for PostCSS (used plugins and more)
* **Folders & other files**
  * **build** *- webpack configs file for dev, build mode
    * webpack.base.conf.js *- main webpack config file for all modes
    * webpack.build.conf.js *- config file for build mode
    * webpack.dev.conf.js *- config file for dev mode
  * **src** *- all source for build  
    * intex.html *- main html-page
    * intex.js *- main js-script for include styles, js-modules
    * **assets** *- folder for CSS, fonts, img and another assets files
       * **css** *- folder for css stylies 
          * fonts.css *- for include fonts 
          * reset.css *- for reset 
          * style.css *- for reset all original browser styles
       * **fonts** *- folder for fonts 
       * **img** *- folder for imges
    * **js** *- folder for js-modules includes to index.js
    * **static** *- folder for sitemap, favicon files 
