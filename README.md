# gh submodule-update

A [gh](https://github.com/cli/cli) extension to fetch & pull your git submodule to latest, and then run `git submodule update` on your current directory.

I made this before I learned about `git config --global submodule.recurse true`


## Usage

```sh
gh submodule-update --path  ~/Documents/peloton/music-common-data
```

## Installation

```sh
gh extension install nicholasoxford/gh-submodule-update

```


## License

MIT

## Author

Nicholas Oxford (a.k.a. nicholasoxford)
