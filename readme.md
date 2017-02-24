# SRDA

> SRDA 資料串連平台

## How to install

Prerequisites:

* [Node.js](http://nodejs.org/) >=4.0.0  

Installation process:
1. Clone this repository
2. Run ```npm install``` to install dependencies

## Usage

For project development with livereload run:
```
gulp serve
```

To build project run: (Result will be in ```dist/``` folder.)
```
gulp build [--force]
```

To serve built project run:
```
gulp serve:dist
```

Gulp help:
```
gulp help
```


## Built-in features

* Webserver with liverelaod
* Pug compilation
* Sass compilation
* ES2016 transpiling with Babel.js
* ES2015 modules bundling with Rollup.js
* JS linting with ESLint
* CSS autoprefixing
* CSS minification
* Image optimaliztion
* Lean Modernizr builds
* Improved file caching
* Deploying via rsync/sftp


---

