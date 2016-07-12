[![Stories in Ready](https://badge.waffle.io/DamianMcNulty/web-starter-kit.png?label=ready&title=Ready)](https://waffle.io/DamianMcNulty/web-starter-kit)
[![Build Status](https://travis-ci.org/DamianMcNulty/web-starter-kit.svg?branch=master)](https://travis-ci.org/DamianMcNulty/web-starter-kit)


## Overview

[Web Starter Kit](https://developers.google.com/web/tools/starter-kit/) 
Following best practices outlined in Google's [Web Fundamentals](https://developers.google.com/web/fundamentals/).

### Features

| Feature                                | Summary                                                                                                                                                                                                                                                     |
|----------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Responsive boilerplate | A responsive boilerplate optimized for the multi-screen web. Powered by [Material Design Lite](http://getmdl.io).  You're free to use either this or a completely clean-slate  via [basic.html](https://github.com/google/web-starter-kit/blob/master/app/basic.html).                          |
| Sass support                           | Compile [Sass](http://sass-lang.com/) into CSS with ease, bringing support for variables, mixins and more. (Run `gulp serve` or `gulp` for production)                                                                                                      |
| Performance optimization               | Minify and concatenate JavaScript, CSS, HTML and images to help keep your pages lean. (Run `gulp` to create an optimised version of your project to `/dist`)                                                                                                |
| Code Linting               | JavaScript code linting is done using [ESLint](http://eslint.org) - a pluggable linter tool for identifying and reporting on patterns in JavaScript. Web Starter Kit uses ESLint with [eslint-config-google](https://github.com/google/eslint-config-google), which tries to follow the Google JavaScript style guide.                                                                                                |
| ES2015 via Babel 6.0                   | Optional ES2015 support using [Babel](https://babeljs.io/). To enable ES2015 support remove the line `"only": "gulpfile.babel.js",` in the [.babelrc](.babelrc) file. ES2015 source code will be automatically transpiled to ES5 for wide browser support.  |
| Built-in HTTP Server                   | A built-in server for previewing your site locally while you develop and iterate                                                                                                                                                                            |
| Live Browser Reloading                 | Reload the browser in real-time anytime an edit is made without the need for an extension. (Run `gulp serve` and edit your files)                                                                                                                           |
| Cross-device Synchronization           | Synchronize clicks, scrolls, forms and live-reload across multiple devices as you edit your project. Powered by [BrowserSync](http://browsersync.io). (Run `gulp serve` and open up the IP provided on other devices on your network)                       |
| Offline support                     | Thanks to our baked in [Service Worker](http://www.html5rocks.com/en/tutorials/service-worker/introduction/) [pre-caching](https://github.com/google/web-starter-kit/blob/master/gulpfile.babel.js#L226), sites deploying `dist` to a HTTPS domain will enjoy offline support. This is made possible by [sw-precache](https://github.com/GoogleChrome/sw-precache/).                                                                                                                                              |
| PageSpeed Insights                     | Web performance metrics showing how well your site performs on mobile and desktop (Run `gulp pagespeed`)                                                                                                                                                    |

## Web Performance

Web Starter Kit strives to give you a high performance starting point out of the box. Our median Web Page Test [scores](http://www.webpagetest.org/result/160709_BV_85G/) for the default template have a [Speed Index](https://sites.google.com/a/webpagetest.org/docs/using-webpagetest/metrics/speed-index) of ~1400	 (1000 is ideal) and a repeat-visit Speed Index of ~520 thanks to Service Worker precaching. 

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

* Chrome
* Edge
* Firefox
* Safari
* Opera
* Internet Explorer 9+

## License

Apache 2.0  
Copyright 2015 Google Inc

Copyright 2016 Damian McNulty
