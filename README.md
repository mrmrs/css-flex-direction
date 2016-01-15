# css-flex-direction 0.0.7

Css module of single purpose classes for flex direction

#### Stats

235 | 20 | 20
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-flex-direction
```

#### With Git

```
git clone https://github.com/tachyons-css/css-flex-direction
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-flex-direction";
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
<link rel="stylesheet" href="path/to/module/css/css-flex-direction">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   FLEX DIRECTION
*/
.fd-row { flex-direction: row; }
.fd-rev { flex-direction: row-reverse; }
.fd-col { flex-direction: column; }
.fd-colrev { flex-direction: column-reverse; }
.fd-i { flex-direction: inherit; }
@media screen and (min-width: 48em) {
 .fd-row-ns { flex-direction: row; }
 .fd-rev-ns { flex-direction: row-reverse; }
 .fd-col-ns { flex-direction: column; }
 .fd-colrev-ns { flex-direction: column-reverse; }
 .fd-i-ns { flex-direction: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .fd-row-m { flex-direction: row; }
 .fd-rev-m { flex-direction: row-reverse; }
 .fd-col-m { flex-direction: column; }
 .fd-colrev-m { flex-direction: column-reverse; }
 .fd-i-m { flex-direction: inherit; }
}
@media screen and (min-width: 64em) {
 .fd-row-l { flex-direction: row; }
 .fd-rev-l { flex-direction: row-reverse; }
 .fd-col-l { flex-direction: column; }
 .fd-colrev-l { flex-direction: column-reverse; }
 .fd-i-l { flex-direction: inherit; }
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

MIT

