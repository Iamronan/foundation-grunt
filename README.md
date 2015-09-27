# Foundation 5.5 Static #



A basic setup for projects based on the Foundation 5 framework

Features:

* Latest Foundation 5 Framework (version 5.5)
* Custom gruntfile.js to handle theme development and cross browser/device testing


This project uses acustomised version of zf-5 yeoman generator

https://www.npmjs.com/package/generator-zf5

Festures include

* Sass compiling
* Publishing to dist directory
* Server with LiveReload (127.0.0.1:9000)
* Bower install
* JSHint
* Font Awesome (option)


Installation

* Clone/Fork into your /localhost folder 
* Open your terminal at the path to your project folder
* MAKE SURE YOU INSTALL NODE AND GRUNT GLOBALLY

If you have not used these before have a read at his tutorial.


* Access the root folder via temrinal and run the command **npm install && bower install --save**


Grunt tasks:

run project (compile Jade, compile Sass, bower install, livereload (server on 127.0.0.1:9000), watch)

$ grunt
publishing project (into dist directory) (compile Jade, compile Sass, validate-js, copy, concatenation, minifications)

$ grunt publish
dist directory preview (server on 127.0.0.1:9001)

$ grunt server-dist
Other Grunt tasks (if you want to use it)

..for validating javascript

$ grunt validate-js
..for injecting bower libraries (also in default grunt task)

$ grunt bower-install
..for compiling Sass files

$ grunt compile-sass
..for compiling Jade files



