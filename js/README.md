# Cucumber.js

Cucumber brought (natively) to your JavaScript stack.

It can run basic fatures inside both Node.js and web browsers.

It still needs a lot of work. Only a few feature elements are supported at the moment.

## Prerequesites

* Node.js 0.4.8 (tested on 0.4.7 too)
* npm 1.0.6

### Works on

* Node.js 0.4.7, 0.4.8, 0.5.0-pre
* Google Chrome 13.0.772.0 (dev)
* Firefox 4.0.1
* Safari 5.0.5

And probably lots of other browsers.

## Play with it!

    $ open js/example/index.html

## Setup for using in Node.js and running tests

The only dependency of cucumber.js is Gherkin:

    $ npm link
    
## Run tests

Specs:

    $ cd js/spec
    $ ../../node_modules/.bin/jasmine-node .
    
Features (yes, cucumber.js is eating itself):

    $ cd js
    $ node cucumber.js features/basic.feature
