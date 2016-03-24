# Cartridge Images [![Build Status](https://travis-ci.org/cartridge/cartridge-images.svg?branch=master)](https://travis-ci.org/cartridge/cartridge-images)

> Image optimisation expansion pack for cartridge

To use this module, you will need [cartridge-cli](https://github.com/cartridge/cartridge-cli) installed.

You will need to make sure you have a cartridge project setup before you install any modules.

```shell
npm install cartridge-images --save-dev
```

This module add the following things to a project:

* Image Optimisation using [gulp-imagemin](https://github.com/sindresorhus/gulp-imagemin)
* SVG Optimisation using [gulp-svgmin](https://github.com/ben-eb/gulp-svgmin)
* Responsive Images using [gulp-responsive](https://github.com/mahnunchik/gulp-responsive)

##Config

Once installed, the config file `task.images.js` is stored in the `_config` directory in the root of your cartridge project.