# **g**(it) **s**(tash) **ex**(plorer)

> Interactive `git stash` explorer using [`fzf`](https://github.com/junegunn/fzf))

![demo](demo.gif)

## Installation

CURL:

```sh
curl -o /usr/local/bin/gsex https://git.io/gsex && chmod 755 /usr/local/bin/gsex
```

npm:

```sh
npm install -g gsex
```

## Usage

```sh
$ gsex [<options>]
```

Type to fuzzy-search stashes.

Keys:

- **up/down**: navigate stashes
- **ctrl-b**: create a branch from selected stash
- **del**: drop selected stash
- **enter**: view full diff (less)
- **esc**: exit gsex

## License

MIT © Kevin Lanni

Modified from original work by [bturrubiates](https://github.com/bturrubiates/fzf-scripts).
