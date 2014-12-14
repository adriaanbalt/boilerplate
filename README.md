
# Boilerplate website

####Introduction

#### Features

* [JS Uglify](https://github.com/gruntjs/grunt-contrib-uglify)
* [Watch / Live reload](https://github.com/gruntjs/grunt-contrib-watch)
* [Compass](http://compass-style.org/)

#### Libraries

* [Normalize](http://necolas.github.io/normalize.css/)
* [Modernizr](http://modernizr.com/)
* [Angular](https://angularjs.org/)
* [Compass](http://compass-style.org/)

#### Requirements
Make sure your have the following installed with these versions or greater when running the bootstrap

* ```Node v0.10.26```
* ```Sass v3.3.9```
* ```Compass >1.0.0.alpha.20```

#### Installation

There are several hoops you may have to jump through to get all dependencies installed, but hopefully alot of this stuff will be on your machine anyway.

#### Installing Tooling dependencies (Grunt tasks, Bower)

```
npm install
```

### Grunt Tasks:

#### Dev
The dev command will launch an http server as well as build all html/css/js for the app and the styleguide. Files will also be 'watched' for changes and rebuilt if necessary. Code will be checked for errors and any unit tests will be run.

```
grunt dev
```
