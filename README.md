Webpack 4 Boilerplate With Sass, lodash, Bootstrap v4, jQuery, Popper.js on board!
===========

> Plain webpack 4 boilerplate with Babel, SASS, lodash, Bootstrap v4, jQuery, Popper.js on board!

## Requirements
You only need <b>node.js</b> pre-installed and you’re good to go. 

If you don’t want to work with lodash, just remove it from the node packages and the webpack config.

## Ready to go with 4 easy steps!

## Step 01: Download
Clone into current directory
```sh
git clone https://github.com/adamklepacz/webpack_bolierplate_ak92.git
```

## Step 02: Setup
Install all dependencies
```sh
$ npm install
```

## Step 03: Development
Run the local webpack-dev-server with livereload and autocompile on [http://localhost:8080/](http://localhost:8080/)
```sh
$ npm run dev
```
## Step 04: Build
Build the current application
```sh
$ npm run build
```


## Project structure
# Javascript files
app<br>
  |---index.js<br>
  |---/components<br>

**Index.js** is Your entry point javascript file when You can import all your components from the component folder.
**A component** folder is a place where You should storage modules responsible for the logic of a specific component in your project like ex. form, preloader, navbar etc.

# Styles folder
styles<br>
  |---/components<br>
  |---/modules<br>
  |---/globals<br>
  |---/templates<br>
  |---/variables<br>
  |---index.scss<br>

**Components folder** is a place for generic, reusable, small components like buttons. <br>
**Modules folder** is a place for sections of a website which use components.<br>
**Globals folder** is a place where You should style your global elements like forms, typography, accessibility etc.<br>
**Templates folder** is a place where You should mostly define a spacing between components and modules, depends on where they appear on your project. Files examples which will be here in the folder: _homepage.scss, _contact-page.scss.<br>
**Variables folder** is a place where You should overwrite bootstrap variables and define Your own variables like _colors.scss, _spacing.scss etc.<br>
**Index.scss** is your application entry point, here You include all your files from other folders.<br>

## [webpack](https://webpack.js.org/)
If you're not familiar with webpack, the [webpack-dev-server](https://webpack.js.org/configuration/dev-server/) will serve the static files in your build folder and watch your source files for changes.
When changes are made the bundle will be recompiled. This modified bundle is served from memory at the relative path specified in publicPath.
