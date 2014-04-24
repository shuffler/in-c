# Brunch on a diet

A [Brunch](http://brunch.io) skeleton for quickly getting started with your project.

It provides as plugins [Coffeescript](http://bower.io), [Stylus](http://bower.io) and [Eco](http://bower.io).

Beside that, the output js will come out wrapped as it would if compiled by the coffeescript compiler and all [Eco](http://bower.io) templates will live on a global JST variable like some are used to.



## Getting started
* Install (if you don't have them):
    * [Node.js](http://nodejs.org): `brew install node` on OS X
    * [Brunch](http://brunch.io): `npm install -g brunch`
    * [Bower](http://bower.io): `npm install -g bower`
    * Brunch plugins and Bower dependencies: `npm install & bower install`.
* Run:
    * `brunch watch --server` — watches the project with continuous rebuild. This will also launch HTTP server with [pushState](https://developer.mozilla.org/en-US/docs/Web/Guide/API/DOM/Manipulating_the_browser_history).
    * `brunch build --production` — builds minified project for production
* Learn:
    * `public/` dir is fully auto-generated and served by HTTP server.  Write your code in `app/` dir.
    * Place static files you want to be copied from `app/assets/` to `public/`.
    
