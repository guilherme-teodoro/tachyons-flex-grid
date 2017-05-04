# tachyons-flex-grid 1.1.0

A 12 column flexbox grid for Tachyons

#### Stats

616 | 53 | 227
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev tachyons-flex-grid
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/guilherme-teodoro/tachyons-flex-grid
```

ssh:
```
git clone git@github.com:guilherme-teodoro/tachyons-flex-grid.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "tachyons-flex-grid";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/tachyons-flex-grid@1.1.0/css/tachyons-flex-grid.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/tachyons-flex-grid">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/* Variables */
/* Media Queries */
/*

   GRID

*/
.row { display: -webkit-box; display: -ms-flexbox; display: flex; -ms-flex-wrap: wrap; flex-wrap: wrap; margin-left: -.5rem; margin-right: -.5rem; }
.col { max-width: 100%; -ms-flex-preferred-size: 0; flex-basis: 0; -webkit-box-flex: 1; -ms-flex-positive: 1; flex-grow: 1; padding: 0 .5rem; }
.col1 { max-width: calc( 100% / 12 ); -ms-flex-preferred-size: calc( 100% / 12 ); flex-basis: calc( 100% / 12 ); padding: 0 .5rem; }
.col2 { max-width: calc( ( 100% / 12 ) * 2 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 2 ); flex-basis: calc( ( 100% / 12 ) * 2 ); padding: 0 .5rem; }
.col3 { max-width: calc( ( 100% / 12 ) * 3 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 3 ); flex-basis: calc( ( 100% / 12 ) * 3 ); padding: 0 .5rem; }
.col4 { max-width: calc( ( 100% / 12 ) * 4 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 4 ); flex-basis: calc( ( 100% / 12 ) * 4 ); padding: 0 .5rem; }
.col5 { max-width: calc( ( 100% / 12 ) * 5 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 5 ); flex-basis: calc( ( 100% / 12 ) * 5 ); padding: 0 .5rem; }
.col6 { max-width: 50%; -ms-flex-preferred-size: 50%; flex-basis: 50%; padding: 0 .5rem; }
.col7 { max-width: calc( ( 100% / 12 ) * 7 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 7 ); flex-basis: calc( ( 100% / 12 ) * 7 ); padding: 0 .5rem; }
.col8 { max-width: calc( ( 100% / 12 ) * 8 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 8 ); flex-basis: calc( ( 100% / 12 ) * 8 ); padding: 0 .5rem; }
.col9 { max-width: calc( ( 100% / 12 ) * 9 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 9 ); flex-basis: calc( ( 100% / 12 ) * 9 ); padding: 0 .5rem; }
.col10 { max-width: calc( ( 100% / 12 ) * 10 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 10 ); flex-basis: calc( ( 100% / 12 ) * 10 ); padding: 0 .5rem; }
.col11 { max-width: calc( ( 100% / 12 ) * 11 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 11 ); flex-basis: calc( ( 100% / 12 ) * 11 ); padding: 0 .5rem; }
.col12 { max-width: 100%; -ms-flex-preferred-size: 100%; flex-basis: 100%; padding: 0 .5rem; }
@media screen and (min-width: 30em) {
 .col-ns { max-width: 100%; -ms-flex-preferred-size: 0; flex-basis: 0; -webkit-box-flex: 1; -ms-flex-positive: 1; flex-grow: 1; padding: 0 .5rem; }
 .col1-ns { max-width: calc( 100% / 12 ); -ms-flex-preferred-size: calc( 100% / 12 ); flex-basis: calc( 100% / 12 ); padding: 0 .5rem; }
 .col2-ns { max-width: calc( ( 100% / 12 ) * 2 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 2 ); flex-basis: calc( ( 100% / 12 ) * 2 ); padding: 0 .5rem; }
 .col3-ns { max-width: calc( ( 100% / 12 ) * 3 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 3 ); flex-basis: calc( ( 100% / 12 ) * 3 ); padding: 0 .5rem; }
 .col4-ns { max-width: calc( ( 100% / 12 ) * 4 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 4 ); flex-basis: calc( ( 100% / 12 ) * 4 ); padding: 0 .5rem; }
 .col5-ns { max-width: calc( ( 100% / 12 ) * 5 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 5 ); flex-basis: calc( ( 100% / 12 ) * 5 ); padding: 0 .5rem; }
 .col6-ns { max-width: 50%; -ms-flex-preferred-size: 50%; flex-basis: 50%; padding: 0 .5rem; }
 .col7-ns { max-width: calc( ( 100% / 12 ) * 7 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 7 ); flex-basis: calc( ( 100% / 12 ) * 7 ); padding: 0 .5rem; }
 .col8-ns { max-width: calc( ( 100% / 12 ) * 8 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 8 ); flex-basis: calc( ( 100% / 12 ) * 8 ); padding: 0 .5rem; }
 .col9-ns { max-width: calc( ( 100% / 12 ) * 9 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 9 ); flex-basis: calc( ( 100% / 12 ) * 9 ); padding: 0 .5rem; }
 .col10-ns { max-width: calc( ( 100% / 12 ) * 10 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 10 ); flex-basis: calc( ( 100% / 12 ) * 10 ); padding: 0 .5rem; }
 .col11-ns { max-width: calc( ( 100% / 12 ) * 11 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 11 ); flex-basis: calc( ( 100% / 12 ) * 11 ); padding: 0 .5rem; }
 .col12-ns { max-width: 100%; -ms-flex-preferred-size: 100%; flex-basis: 100%; padding: 0 .5rem; }
}
@media screen and (min-width: 30em) and (max-width: 60em) {
 .col-m { max-width: 100%; -ms-flex-preferred-size: 0; flex-basis: 0; -webkit-box-flex: 1; -ms-flex-positive: 1; flex-grow: 1; padding: 0 .5rem; }
 .col1-m { max-width: calc( 100% / 12 ); -ms-flex-preferred-size: calc( 100% / 12 ); flex-basis: calc( 100% / 12 ); padding: 0 .5rem; }
 .col2-m { max-width: calc( ( 100% / 12 ) * 2 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 2 ); flex-basis: calc( ( 100% / 12 ) * 2 ); padding: 0 .5rem; }
 .col3-m { max-width: calc( ( 100% / 12 ) * 3 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 3 ); flex-basis: calc( ( 100% / 12 ) * 3 ); padding: 0 .5rem; }
 .col4-m { max-width: calc( ( 100% / 12 ) * 4 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 4 ); flex-basis: calc( ( 100% / 12 ) * 4 ); padding: 0 .5rem; }
 .col5-m { max-width: calc( ( 100% / 12 ) * 5 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 5 ); flex-basis: calc( ( 100% / 12 ) * 5 ); padding: 0 .5rem; }
 .col6-m { max-width: 50%; -ms-flex-preferred-size: 50%; flex-basis: 50%; padding: 0 .5rem; }
 .col7-m { max-width: calc( ( 100% / 12 ) * 7 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 7 ); flex-basis: calc( ( 100% / 12 ) * 7 ); padding: 0 .5rem; }
 .col8-m { max-width: calc( ( 100% / 12 ) * 8 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 8 ); flex-basis: calc( ( 100% / 12 ) * 8 ); padding: 0 .5rem; }
 .col9-m { max-width: calc( ( 100% / 12 ) * 9 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 9 ); flex-basis: calc( ( 100% / 12 ) * 9 ); padding: 0 .5rem; }
 .col10-m { max-width: calc( ( 100% / 12 ) * 10 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 10 ); flex-basis: calc( ( 100% / 12 ) * 10 ); padding: 0 .5rem; }
 .col11-m { max-width: calc( ( 100% / 12 ) * 11 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 11 ); flex-basis: calc( ( 100% / 12 ) * 11 ); padding: 0 .5rem; }
 .col12-m { max-width: 100%; -ms-flex-preferred-size: 100%; flex-basis: 100%; padding: 0 .5rem; }
}
@media screen and (min-width: 60em) {
 .col-l { max-width: 100%; -ms-flex-preferred-size: 0; flex-basis: 0; -webkit-box-flex: 1; -ms-flex-positive: 1; flex-grow: 1; padding: 0 .5rem; }
 .col1-l { max-width: calc( 100% / 12 ); -ms-flex-preferred-size: calc( 100% / 12 ); flex-basis: calc( 100% / 12 ); padding: 0 .5rem; }
 .col2-l { max-width: calc( ( 100% / 12 ) * 2 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 2 ); flex-basis: calc( ( 100% / 12 ) * 2 ); padding: 0 .5rem; }
 .col3-l { max-width: calc( ( 100% / 12 ) * 3 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 3 ); flex-basis: calc( ( 100% / 12 ) * 3 ); padding: 0 .5rem; }
 .col4-l { max-width: calc( ( 100% / 12 ) * 4 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 4 ); flex-basis: calc( ( 100% / 12 ) * 4 ); padding: 0 .5rem; }
 .col5-l { max-width: calc( ( 100% / 12 ) * 5 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 5 ); flex-basis: calc( ( 100% / 12 ) * 5 ); padding: 0 .5rem; }
 .col6-l { max-width: 50%; -ms-flex-preferred-size: 50%; flex-basis: 50%; padding: 0 .5rem; }
 .col7-l { max-width: calc( ( 100% / 12 ) * 7 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 7 ); flex-basis: calc( ( 100% / 12 ) * 7 ); padding: 0 .5rem; }
 .col8-l { max-width: calc( ( 100% / 12 ) * 8 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 8 ); flex-basis: calc( ( 100% / 12 ) * 8 ); padding: 0 .5rem; }
 .col9-l { max-width: calc( ( 100% / 12 ) * 9 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 9 ); flex-basis: calc( ( 100% / 12 ) * 9 ); padding: 0 .5rem; }
 .col10-l { max-width: calc( ( 100% / 12 ) * 10 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 10 ); flex-basis: calc( ( 100% / 12 ) * 10 ); padding: 0 .5rem; }
 .col11-l { max-width: calc( ( 100% / 12 ) * 11 ); -ms-flex-preferred-size: calc( ( 100% / 12 ) * 11 ); flex-basis: calc( ( 100% / 12 ) * 11 ); padding: 0 .5rem; }
 .col12-l { max-width: 100%; -ms-flex-preferred-size: 100%; flex-basis: 100%; padding: 0 .5rem; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

- [Guilherme Teodoro](http://guilhermeteodoro.com)
- [Marcelo Nomoto](https://github.com/mynomoto)

## License

ISC

