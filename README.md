# g(it) s(tash) ex(plorer)

> Interactive `git stash` explorer using [`fzf`](https://github.com/junegunn/fzf)

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

- **up/down**: navigate (click line also works)
- **ctrl-b**: create a branch from selected stash
- **del**: drop selected stash
- **enter**: view full diff (less)
- **esc**: exit gsex

## Related tools

[gdex](https://github.com/therealklanni/gdex) - g(it) d(iff) ex(plorer)

## License

MIT © Kevin Lanni

Modified from original work by [bturrubiates](https://github.com/bturrubiates/fzf-scripts).
