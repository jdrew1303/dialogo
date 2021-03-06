Dialogo
=========

> ([Diálogo](http://es.wikipedia.org/wiki/Di%C3%A1logo), spanish for dialogue) "to discuss areas of disagreement frankly in order to resolve them." -- [Dictionary.com](http://dictionary.reference.com/browse/dialogue)

Dialogo supports realtime collaboration apps. It's a Javascript implementation of [Differential Synchronization](https://neil.fraser.name/writing/sync/) that works on browsers and node.js.

Installation
------------

``` sh
npm install dialogo
```

Specs
-------

Specs (built using mocha.js) run on travis-ci: [![Build Status](https://travis-ci.org/benjamine/dialogo.png?branch=master)](https://travis-ci.org/benjamine/dialogo)

you can test them using ```npm test```, or on browsers opening [Test page](http://benjamine.github.io/dialogo/test/test.html)

Working Demo
--------------------

- run ```npm start```
- open http://localhost:6147 in 2 (or more!) browser windows
- edit and see changes sync in realtime

Note: the editor will detect if the content is JSON, or just text and use the best strategy.
Look the browser console for details.

Warning
----------

At this point this is just an experiment (very incomplete and buggy), use at your own risk.

License
--------

The MIT License (MIT)

Copyright (c) 2014 Benjamin Eidelman (@beneidel)

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
