
# node-canvas

 Node canvas is a [Cairo](http://cairographics.org/) backed Canvas implementation for [NodeJS](http://nodejs.org).

## Authors

  - TJ Holowaychuk ([visionmedia](http://github.com/visionmedia))

## TODO

     [x] drawing shapes
     [x] line styles
     [x] list of valid css colors
     [x] match canvas defaults (mostly, test suite from webkit would be nice)
     [x] transformations
     [x] gradients
     [x] make sure constructor names match
     [x] compositing
     [ ] Image
     [ ] patterns
     [ ] text
     [ ] PixelArray
     [ ] data urls

## Testing

Visual tests utilize md5 checksums in order to assert integrity.

Build:

    $ node-waf configure build

Test:

    $ make test

## License 

(The MIT License)

Copyright (c) 2009-2010 TJ Holowaychuk &lt;tj@vision-media.ca&gt;

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.