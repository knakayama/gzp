gzp
===

**Github** **Zsh** **Peco**

# Description

**Note:** This code is heavily inspired by [anyframe](https://github.com/mollifier/anyframe).

List your repositories and browse it with [peco style](https://github.com/peco/peco).

# Requirements

* [peco](https://github.com/peco/peco)
* [jq](https://github.com/stedolan/jq)

# Install

## antigen

```zsh
antigen bundle knakayama/gzp
```

# Usage

First, execute `gzp-action-setup` to get GitHub Access Token like the following:

```bash
$ gzp-action-setup
```

Next, edit your `~/.zshrc` like the following:

```zsh
bindkey '^x^g' gzp-widget-open-gh-repo
```

Finally, hit `^x^g` in your terminal.

# License

[MIT](https://github.com/knakayama/gzp/blob/master/LICENSE)

# Author

[knakayama](https://github.com/knakayama)