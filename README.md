# css-transition-properties 0.0.6

Css module of single purpose classes for transition properties

#### Stats

379 | 48 | 48
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-transition-properties
```

#### With Git

```
git clone https://github.com/tachyons-css/css-transition-properties
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-transition-properties";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-transition-properties">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   TRANSITION PROPERTIES
*/
.tp-n { transition-property: none; }
.tp-all { transition-property: all; }
.tp-i { transition-property: inherit; }
.tp-c { transition-property: color; }
.tp-bc { transition-property: background-color; }
.tp-w { transition-property: width; }
.tp-h { transition-property: height; }
.tp-l { transition-property: left; }
.tp-r { transition-property: right; }
.tp-t { transition-property: top; }
.tp-b { transition-property: bottom; }
.tp-o { transition-property: opacity; }
@media screen and (min-width: 48em) {
 .tp-n-ns { transition-property: none; }
 .tp-all-ns { transition-property: all; }
 .tp-i-ns { transition-property: inherit; }
 .tp-c-ns { transition-property: color; }
 .tp-bc-ns { transition-property: background-color; }
 .tp-w-ns { transition-property: width; }
 .tp-h-ns { transition-property: height; }
 .tp-l-ns { transition-property: left; }
 .tp-r-ns { transition-property: right; }
 .tp-t-ns { transition-property: top; }
 .tp-b-ns { transition-property: bottom; }
 .tp-o-ns { transition-property: opacity; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .tp-n-m { transition-property: none; }
 .tp-all-m { transition-property: all; }
 .tp-i-m { transition-property: inherit; }
 .tp-c-m { transition-property: color; }
 .tp-bc-m { transition-property: background-color; }
 .tp-w-m { transition-property: width; }
 .tp-h-m { transition-property: height; }
 .tp-l-m { transition-property: left; }
 .tp-r-m { transition-property: right; }
 .tp-t-m { transition-property: top; }
 .tp-b-m { transition-property: bottom; }
 .tp-o-m { transition-property: opacity; }
}
@media screen and (min-width: 64em) {
 .tp-n-l { transition-property: none; }
 .tp-all-l { transition-property: all; }
 .tp-i-l { transition-property: inherit; }
 .tp-c-l { transition-property: color; }
 .tp-bc-l { transition-property: background-color; }
 .tp-w-l { transition-property: width; }
 .tp-h-l { transition-property: height; }
 .tp-l-l { transition-property: left; }
 .tp-r-l { transition-property: right; }
 .tp-t-l { transition-property: top; }
 .tp-b-l { transition-property: bottom; }
 .tp-o-l { transition-property: opacity; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC
