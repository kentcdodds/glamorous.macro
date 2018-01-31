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

You basically can replace all usage of the default export of glamorous with `glamorous.macro`. However, `glamorous.macro` does _not_ support named exports
for built-in components.

[npm]: https://www.npmjs.com/
[node]: https://nodejs.org
[babel-plugin-macros]: https://github.com/kentcdodds/babel-plugin-macros
[babel-plugin-glamorous-displayname]: https://github.com/bernard-lin/babel-plugin-glamorous-displayname
[macros-badge]: https://img.shields.io/badge/babel--macro-%F0%9F%8E%A3-f5da55.svg?style=flat-square
[babel-plugin-macros]: https://github.com/kentcdodds/babel-plugin-macros
