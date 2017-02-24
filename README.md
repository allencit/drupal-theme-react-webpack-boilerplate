This repo is a boilerplate for drupal theme with react. You could use it as a base to build your own drupal theme.

## Features

- Load the javascritp file as needed
- Scss file build
- Css autoprefixer 
- Covert image to base64 if the image size < 50k

## How to use

First, you should clone the repo and install the dependencies.

```bash
$ cd <youProjectName>/site/default/theme
$ git clone git@github.com:allencit/drupal-theme-react-webpack-boilerplate.git <yourThemeName>
$ cd <yourThemeName>
$ npm install
```

Then, you need delete the old `.git` history.

```bash
rm -rf .git
```

You also need to update `package.json` and rename and update the theme info file.

From there, you can start to develop your own theme with `npm start` command.

## File info

### boilerplate.info

You need to rename this minimal file to `<yourThemeName>.info` and modify it as normal as you develop a drupal theme.

### webpack.config.entry.js

webpack entry file.

### webpack.config.js

webpack config file for develop.

### webpack.production.config.js

webpack config file for production.
