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
  * .babelrc
  * package-lock.json
  * package.json
  * postcss.config.js
* **Folders & other files**
  * **build**
    * webpack.base.conf.js
    * webpack.build.conf.js
    * webpack.dev.conf.js
  * **src**
    * intex.html
    * intex.js
    * **assets**
       * **css**
          * fonts.css
          * reset.css
          * style.css
       * **fonts**
       * **img**
    * **js**
    * **static**
