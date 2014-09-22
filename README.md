# CSS TRANSITION PROPERTIES

  Mobile-first classes for css-transition-properties.
  Set the desired css-transition-properties on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-transition-properties
```
View on [npm](https://www.npmjs.org/package/css-transition-properties)


## File Size

2.2K transition-properties.css
1.8K transition-properties.min.css 
318B minified and gzipped

## The Code
```
.tp-n   { transition-property: none; }
.tp-all { transition-property: all; }
.tp-i   { transition-property: inherit; }
.tp-c   { transition-property: color; }
.tp-bc  { transition-property: background-color; }
.tp-w   { transition-property: width; }
.tp-h   { transition-property: height; }
.tp-l   { transition-property: left; }
.tp-r   { transition-property: right; }
.tp-t   { transition-property: top; }
.tp-b   { transition-property: bottom; }
.tp-o   { transition-property: opacity; }

@media screen and (min-width: 48em) {
  .tp-n-ns   { transition-property: none; }
  .tp-all-ns { transition-property: all; }
  .tp-i-ns   { transition-property: inherit; }
  .tp-c-ns   { transition-property: color; }
  .tp-bc-ns  { transition-property: background-color; }
  .tp-w-ns   { transition-property: width; }
  .tp-h-ns   { transition-property: height; }
  .tp-l-ns   { transition-property: left; }
  .tp-r-ns   { transition-property: right; }
  .tp-t-ns   { transition-property: top; }
  .tp-b-ns   { transition-property: bottom; }
  .tp-o-ns   { transition-property: opacity; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .tp-n-m   { transition-property: none; }
  .tp-all-m { transition-property: all; }
  .tp-i-m   { transition-property: inherit; }
  .tp-c-m   { transition-property: color; }
  .tp-bc-m  { transition-property: background-color; }
  .tp-w-m   { transition-property: width; }
  .tp-h-m   { transition-property: height; }
  .tp-l-m   { transition-property: left; }
  .tp-r-m   { transition-property: right; }
  .tp-t-m   { transition-property: top; }
  .tp-b-m   { transition-property: bottom; }
  .tp-o-m   { transition-property: opacity; }
}

@media screen and (min-width: 64em)  {
  .tp-n-l   { transition-property: none; }
  .tp-all-l { transition-property: all; }
  .tp-i-l   { transition-property: inherit; }
  .tp-c-l   { transition-property: color; }
  .tp-bc-l  { transition-property: background-color; }
  .tp-w-l   { transition-property: width; }
  .tp-h-l   { transition-property: height; }
  .tp-l-l   { transition-property: left; }
  .tp-r-l   { transition-property: right; }
  .tp-t-l   { transition-property: top; }
  .tp-b-l   { transition-property: bottom; }
  .tp-o-l   { transition-property: opacity; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

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

