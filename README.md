# CSS in JS
React: [CSS in JS](https://speakerdeck.com/vjeux/react-css-in-js) techniques comparison.

## Usage
Inside each package folder, run:

```bash
npm i
npm run build && open index.html
```

## Features

**How to read the table**

More crosses doesn't mean "better", it depends on your needs.
For example, if a package supports the css file extraction you can run the autoprefixing at build time.

| Package | Version | Automatic Vendor Prefixing | Pseudo Classes | Media Queries | Styles As Object Literals | Extract CSS File | Stars |
|---------|:-------:|:--------------------------:|:--------------:|:-------------:|:-------------------------:|:----------------:|:-----:|
| [aphrodite](https://github.com/Khan/aphrodite) | 0.1.2 | x | x | x | x | x | ![GitHub stars](https://img.shields.io/github/stars/Khan/aphrodite.svg?style=social&label=Star) |
| [babel-plugin-css-in-js](https://github.com/martinandert/babel-plugin-css-in-js) | 1.2.2 | x | x | x | x | x | ![GitHub stars](https://img.shields.io/github/stars/martinandert/babel-plugin-css-in-js.svg?style=social&label=Star) |
| [bloody-react-styled](https://github.com/bloodyowl/react-styled) | 3.0.0 | | x | x | | | ![GitHub stars](https://img.shields.io/github/stars/bloodyowl/react-styled.svg?style=social&label=Star) |
| [cess-loader](https://github.com/irom-io/cess-loader) | 0.1.5 | | x | x | | x | ![GitHub stars](https://img.shields.io/github/stars/irom-io/cess-loader.svg?style=social&label=Star) |
| [classy](https://github.com/inturn/classy) | 0.3.0 | | x | x | x | | ![GitHub stars](https://img.shields.io/github/stars/inturn/classy.svg?style=social&label=Star) |
| [csjs](https://github.com/rtsao/csjs) | 1.0.0 | | x | x | | | ![GitHub stars](https://img.shields.io/github/stars/rtsao/csjs.svg?style=social&label=Star) |
| [css-loader](https://github.com/webpack/css-loader) | 0.15.6 | | x | x | | x | ![GitHub stars](https://img.shields.io/github/stars/webpack/css-loader.svg?style=social&label=Star) |
| [css-ns](https://github.com/jareware/css-ns) | 1.0.0 | | x | x | | x | ![GitHub stars](https://img.shields.io/github/stars/jareware/css-ns.svg?style=social&label=Star) |
| [cssobj](https://github.com/cssobj/cssobj) | 0.2.21 | x | x | x | x | | ![GitHub stars](https://img.shields.io/github/stars/cssobj/cssobj.svg?style=social&label=Star) |
| [cssx-loader](https://github.com/krasimir/cssx) | 3.8.0 | x | x | x | | x | ![GitHub stars](https://img.shields.io/github/stars/krasimir/cssx.svg?style=social&label=Star) |
| [es-css-modules](https://github.com/jacobp100/es-css-modules) | 1.2.3 | | x | x | | x | ![GitHub stars](https://img.shields.io/github/stars/jacobp100/es-css-modules.svg?style=social&label=Star) |
| [glamor](https://github.com/threepointone/glamor) | 2.1.0 | x | x | x | x | x | ![GitHub stars](https://img.shields.io/github/stars/threepointone/glamor.svg?style=social&label=Star) |
| [hyperstyles](https://github.com/colingourlay/hyperstyles) | 3.3.0 | | x | x | | x | ![GitHub stars](https://img.shields.io/github/stars/colingourlay/hyperstyles.svg?style=social&label=Star) |
| [j2c](https://github.com/j2css/j2c) | 0.10.0 | | x | x | x | x | ![GitHub stars](https://img.shields.io/github/stars/j2css/j2c.svg?style=social&label=Star) |
| [jsxstyle](https://github.com/petehunt/jsxstyle) | 0.0.14 | x | | | x | | ![GitHub stars](https://img.shields.io/github/stars/petehunt/jsxstyle.svg?style=social&label=Star) |
| [radium](https://github.com/FormidableLabs/radium) | 0.13.5 | x | x | x | x | | ![GitHub stars](https://img.shields.io/github/stars/FormidableLabs/radium.svg?style=social&label=Star) |
| [react-css-builder](https://github.com/jhudson8/react-css-builder) | 0.2.0 | | | | x | | ![GitHub stars](https://img.shields.io/github/stars/jhudson8/react-css-builder.svg?style=social&label=Star) |
| [react-css-components](https://github.com/andreypopp/react-css-components) | 0.6.9 | | x | x | | x | ![GitHub stars](https://img.shields.io/github/stars/andreypopp/react-css-components.svg?style=social&label=Star) |
| [react-css-modules](https://github.com/gajus/react-css-modules) | 3.0.2 | | x | x | | x | ![GitHub stars](https://img.shields.io/github/stars/gajus/react-css-modules.svg?style=social&label=Star) |
| [react-cxs](https://github.com/jxnblk/react-cxs) | 1.0.0-beta.4 | | x | x | x | x | ![GitHub stars](https://img.shields.io/github/stars/jxnblk/react-cxs.svg?style=social&label=Star) |
| [react-fela](https://github.com/rofrischmann/react-fela) | 2.1.0 | x | x | x | x | x | ![GitHub stars](https://img.shields.io/github/stars/rofrischmann/react-fela.svg?style=social&label=Star) |
| [react-free-style](https://github.com/blakeembrey/react-free-style) | 0.6.0 | | x | x | x | x | ![GitHub stars](https://img.shields.io/github/stars/blakeembrey/react-free-style.svg?style=social&label=Star) |
| [react-inline-css](https://github.com/RickWong/react-inline-css) | 1.2.0 | | x | x | | | ![GitHub stars](https://img.shields.io/github/stars/RickWong/react-inline-css.svg?style=social&label=Star) |
| [react-inline-style](https://github.com/dowjones/react-inline-style) | 0.1.0 | x | x | x | x | | ![GitHub stars](https://img.shields.io/github/stars/dowjones/react-inline-style.svg?style=social&label=Star) |
| [react-inline](https://github.com/martinandert/react-inline) | 0.6.3 | x | x | x | x | x | ![GitHub stars](https://img.shields.io/github/stars/martinandert/react-inline.svg?style=social&label=Star) |
| [react-jss](https://github.com/jsstyles/react-jss) | 2.0.5 | x | x | x | x | x | ![GitHub stars](https://img.shields.io/github/stars/jsstyles/react-jss.svg?style=social&label=Star) |
| [react-look](https://github.com/rofrischmann/react-look) | 0.6.1 | x | x | x | x | | ![GitHub stars](https://img.shields.io/github/stars/rofrischmann/react-look.svg?style=social&label=Star) |
| [react-native-web](https://github.com/necolas/react-native-web) | 0.0.11 | x | | | x | x | ![GitHub stars](https://img.shields.io/github/stars/necolas/react-native-web.svg?style=social&label=Star) |
| [react-statics-styles](https://github.com/elierotenberg/react-statics-styles) | 3.0.2 | | x | | x | x | ![GitHub stars](https://img.shields.io/github/stars/elierotenberg/react-statics-styles.svg?style=social&label=Star) |
| [react-styl](https://github.com/nick/react-styl) | 0.0.1 | | x | x | | | ![GitHub stars](https://img.shields.io/github/stars/nick/react-styl.svg?style=social&label=Star) |
| [react-style](https://github.com/js-next/react-style) | 0.5.5 | | | x | x | x | ![GitHub stars](https://img.shields.io/github/stars/js-next/react-style.svg?style=social&label=Star) |
| [react-styleable](https://github.com/pluralsight/react-styleable) | 1.4.0 | | x | x | | x | ![GitHub stars](https://img.shields.io/github/stars/pluralsight/react-styleable.svg?style=social&label=Star) |
| [react-stylematic](https://github.com/rtsao/react-stylematic) | 1.0.1 | x | x | x | x | x | ![GitHub stars](https://img.shields.io/github/stars/rtsao/react-stylematic.svg?style=social&label=Star) |
| [react-theme](https://github.com/azazdeaz/react-theme) | 0.1.4 | | | | x | | ![GitHub stars](https://img.shields.io/github/stars/azazdeaz/react-theme.svg?style=social&label=Star) |
| [react-vstyle](https://github.com/fdecampredon/react-vstyle) | 0.1.0 | x | x | x | x | x | ![GitHub stars](https://img.shields.io/github/stars/fdecampredon/react-vstyle.svg?style=social&label=Star) |
| [reactcss](https://github.com/casesandberg/reactcss) | 0.3.2 | x | | | x | | ![GitHub stars](https://img.shields.io/github/stars/casesandberg/reactcss.svg?style=social&label=Star) |
| [scope-styles](https://github.com/rtsao/scope-styles) | 0.6.0 |  | x | x | x | x | ![GitHub stars](https://img.shields.io/github/stars/rtsao/scope-styles.svg?style=social&label=Star) |
| [smart-css](https://github.com/hackhat/smart-css) | 1.1.1 | | x | x | x | | ![GitHub stars](https://img.shields.io/github/stars/hackhat/smart-css.svg?style=social&label=Star) |
| [stile](https://github.com/bloodyowl/stile) + [react-media-queries](https://github.com/bloodyowl/react-media-queries) | 2.0.0 | x | | x | x | | ![GitHub stars](https://img.shields.io/github/stars/bloodyowl/stile.svg?style=social&label=Star) |
| [stilr](https://github.com/kodyl/stilr) | 1.1.0 | | x | x | x | x | ![GitHub stars](https://img.shields.io/github/stars/kodyl/stilr.svg?style=social&label=Star) |
| [style-it](https://github.com/buildbreakdo/style-it) | 1.2.9 | | x | x | | | ![GitHub stars](https://img.shields.io/github/stars/buildbreakdo/style-it.svg?style=social&label=Star) |
| [styled-components](https://github.com/styled-components/styled-components) | 1.0.3 | x | x | x | | | ![GitHub stars](https://img.shields.io/github/stars/styled-components/styled-components.svg?style=social&label=Star) |
| [styling](https://github.com/andreypopp/styling) | 0.2.0 | | x | | x | x | ![GitHub stars](https://img.shields.io/github/stars/andreypopp/styling.svg?style=social&label=Star) |

## Testimonials

> ["Wow, this totally makes my week!"](https://twitter.com/dan_abramov/status/604260877622202368) - Dan Abramov

> ["nice compilation of css-in-js techniques"](https://twitter.com/tjholowaychuk/status/739812614239195136) - TJ Holowaychuk

[SurviveJS / Styling React](http://survivejs.com/webpack_react/styling_react/) by Juho Vepsäläinen

[The Case for CSS Modules](http://markdalgleish.github.io/presentation-the-case-for-css-modules) by Mark Dalgleish

[First Class Styles](https://markdalgleish.github.io/presentation-first-class-styles) by Mark Dalgleish

## Contributing

If your package is not listed here, feel free to add it.
