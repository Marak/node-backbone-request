# backbone-request

A sync engine for **server-side** [backbone.js](http://backbonejs.org) built on the well-established [request](http://github.com/mikeal/request) library.


# Installation

     npm install backbone-request

# Usage

    var Backbone = require('backbone');
    var request = require('backbone-request');
    Backbone.sync = request.sync;

It doesn't really get any easier than that. Now server-side Backbone can sync with any HTTP endpoint using [request](http://github.com/mikeal/request) 