# vim-closer

Closes brackets. Perfect companion to [vim-endwise].

Basically a more conservative version of [auto-pairs] that only works when you press enter.

[![Status](http://img.shields.io/travis/rstacruz/vim-closer/master.svg)](https://travis-ci.org/rstacruz/vim-closer/ "See test builds")

[auto-pairs]: https://github.com/jiangmiao/auto-pairs
[vim-endwise]: https://github.com/tpope/vim-endwise

<br>

## What

Closing are automatically inserted after pressing <kbd>Enter ⏎</kbd>. It supports languages that have `(`, `[`, and `{` brackets.

```css
.section {
```

```css
.section {
  |
}
```

It tries to automatically figure out whatever braces were opened in the line. This is useful for, say, JavaScript where `});` is commonly seen.

```js
describe(function () {
```

```js
describe(function () {
  |
});
```

<br>

## Install

```vim
Plug 'rstacruz/vim-closer'
```

<br>

## Thanks

**vim-closer** © 2015+, Rico Sta. Cruz. Released under the [MIT] License.<br>
Authored and maintained by Rico Sta. Cruz with help from contributors ([list][contributors]).

> [ricostacruz.com](http://ricostacruz.com) &nbsp;&middot;&nbsp;
> GitHub [@rstacruz](https://github.com/rstacruz) &nbsp;&middot;&nbsp;
> Twitter [@rstacruz](https://twitter.com/rstacruz)

[MIT]: http://mit-license.org/
[contributors]: http://github.com/rstacruz/vim-closer/contributors
