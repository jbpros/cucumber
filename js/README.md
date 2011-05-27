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

    $ open <cuke_root>/js/example/index.html

## Setup for using in Node.js and running tests

The only dependency of cucumber.js is Gherkin:

    $ cd <cuke_root>
    $ npm install gherkin
    
If you want to run the specs:

    $ cd <cuke_root> 
    $ npm install -g jasmine-node # a command-line tool needs the "global" flag
    
## Run tests

Specs:

    $ cd <cuke_root>/js/spec
    $ jasmine-node .
    
Features (yes, cucumber.js is eating itself):

    $ cd <cuke_root>/js
    $ node cucumber.js features/basic.feature
