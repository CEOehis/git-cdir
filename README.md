# git-cdir

Use `git-cdir` to clone a repository and change directory in one fell swoop!

## Usage

```sh
git-cdir <repo-url> [<dir>]
```

## Examples

```sh
$ git-cdir https://github.com/CEOehis/git-cdir
# clones https://github.com/CEOehis/git-cdir into a directory named `git-cdir`
# and changes the working directory to `git-cdir`

$ git-cdir https://github.com/CEOehis/git-cdir local-dir
# clones https://github.com/CEOehis/git-cdir into a directory named `local-dir`
# and changes the working directory to `local-dir`
```

## Installation

### NPM

```sh
npm install --global git-cdir
```

## License

This project is [MIT LICENSED](/LICENSE)
