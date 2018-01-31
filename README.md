# glamorous.macro

[![Babel Macro][macros-badge]][babel-plugin-macros]

This is a [`babel-plugin-macros`][babel-plugin-macros] macro for
[`babel-plugin-glamorous-displayname`][babel-plugin-glamorous-displayname].

Please see those projects for more information.

## Installation

This module is distributed via [npm][npm] which is bundled with [node][node] and
should be installed as one of your project's `devDependencies`:

```
npm install --save-dev glamorous.macro
```

You'll also need to install and configure [`babel-plugin-macros`][babel-plugin-macros] if you
haven't already.

## Usage

Once you've [configured `babel-plugin-macros`](https://github.com/kentcdodds/babel-plugin-macros/blob/master/other/docs/user.md)
you can import/require `glamorous.macro`. For example:

```js
import glamorous from 'glamorous.macro'

const MyStyledInput = glamorous.input({
  /* your styles */
})
```

**Note**:

[`babel-plugin-glamorous-displayname`][babel-plugin-glamorous-displayname] allows you to have a few more APIs
than you have with this macro, but this macro comes with all the benefits of using
[`babel-plugin-macros`][babel-plugin-macros] (which you can read about in the `babel-plugin-macros` docs).

[npm]: https://www.npmjs.com/
[node]: https://nodejs.org
[babel-plugin-macros]: https://github.com/kentcdodds/babel-plugin-macros
[babel-plugin-glamorous-displayname]: https://github.com/bernard-lin/babel-plugin-glamorous-displayname
[macros-badge]: https://img.shields.io/badge/babel--macro-%F0%9F%8E%A3-f5da55.svg?style=flat-square
[babel-plugin-macros]: https://github.com/kentcdodds/babel-plugin-macros
