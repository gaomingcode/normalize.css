# @csstools/normalize.css

[![GitHub Version](https://img.shields.io/github/release/gaomingcode/normalize.css.svg)](https://github.com/gaomingcode/normalize.css)
[![Packagist Downloads](https://img.shields.io/packagist/dm/gaomingcode/normalize.css)](https://github.com/gaomingcode/normalize.css)
[![Github License](https://img.shields.io/github/license/gaomingcode/normalize.css)](https://github.com/gaomingcode/normalize.css)

## Installation

### Composer

```
composer require gaomingcode/normalize.css
```

## ReadMe from Origin

# @csstools/normalize.css [<img src="https://csstools.github.io/normalize.css/logo.svg" alt="normalize" width="90" height="90" align="right">][@csstools/normalize.css]

[@csstools/normalize.css] is a CSS library that provides consistent,
cross-browser default styling of HTML elements.

## Usage

```html
<link href="https://unpkg.com/@csstools/normalize.css" rel="stylesheet" />
```

Or to exclusively support evergreen browsers.

```html
<link href="https://unpkg.com/@csstools/normalize.css/evergreen.css" rel="stylesheet" />
```

## Install

```sh
npm install @csstools/normalize.css --save
```

#### Webpack Usage

Import [@csstools/normalize.css] in CSS:

```css
@import '~@csstools/normalize.css';
```

Alternatively, import [@csstools/normalize.css] in JS:

```js
import '@csstools/normalize.css';
```

In `webpack.config.js`, use the appropriate loaders:

```js
module.exports = {
  module: {
    rules: [
      {
        test: /\.css$/,
        use: [ 'style-loader', 'css-loader' ]
      }
    ]
  }
}
```

**Download**

See https://csstools.github.io/normalize.css/latest/normalize.css

## What does it do?

* Normalizes styles for a wide range of elements.
* Corrects bugs and common browser inconsistencies.
* Explains what code does using detailed comments.

## Browser support

* Chrome (last 3)
* Edge (last 3)
* Firefox (last 3)
* Firefox ESR
* Opera (last 3)
* Safari (last 3)
* iOS Safari (last 2)
* Internet Explorer 9+

## Contributing

Please read the [contribution guidelines](CONTRIBUTING.md) in order to make the
contribution process easy and effective for everyone involved.

## Similar Projects

- [modern-normalize.css](https://github.com/sindresorhus/modern-normalize) - An
alternative to normalize.css, adhering to a minimal set of normalizations and
common developer expectations and preferences.
- [opinionate.css](https://github.com/adamgruber/opinionate.css) - A supplement
to normalize.css with opinionated rules.
- [remedy.css](https://github.com/mozdevs/cssremedy) - An alternative to
normalize.css, adhering to different common developer expectations and
preferences.
- [sanitize.css](https://github.com/csstools/sanitize.css) - An alternative to
normalize.css, adhering to common developer expectations and preferences.

## Differences from `necolas/normalize.css`

Nicolas Gallagher and I started writing normalize.css together. I named and
created the normalize.css repository with the help of Paul Irish and Ben Alman.
I transferred the repository to Necolas, who turned it into a “household” CSS
library.

Later, I resumed authorship of normalize.css with Luciano Battagliero. Together,
we tagged, deprecated, and removed “opinionated” styles — styles developers
often prefer but which do not fix bugs or “normalize” browser differences.

Later, Necolas resumed authorship and the issue of whether to include or omit
the opinionated styles forced us to split.

I continue working on the normalize.css project, currently under the “csstools”
tag. I hope one day our differences are resolved and the projects are one again.

## Acknowledgements

normalize.css is a project by [Jonathan Neal](https://github.com/jonathantneal),
co-created with [Nicolas Gallagher](https://github.com/necolas).

[@csstools/normalize.css]: https://github.com/csstools/normalize.css
