# Gofork

## Presentation

Gofork is a CLI tool to find forks that are ahead of a github repository.

## Usage

```
$ gofork --help
usage: gofork [-h|--help] [-r|--repo "<value>"] [-b|--branch "<value>"]
              [-v|--verbose] [-p|--page <integer>]

              CLI tool to find active forks

Arguments:

  -h  --help     Print help information
  -r  --repo     Repository to check
  -b  --branch   Branch to check. Default: repo default branch
  -v  --verbose  Show private and up to date repositories
  -p  --page     Page to check (use -1 for all). Default: 1
```

## Roadmap

* [x] Print the results in table
* [x] Add support for branches (with the default being the repo default branch)
* [x] Use terminal colors
* [x] Verbose flag for private/even forks
* [x] Loading bar
* [X] Sort output

## Built with

Built with love using [Golang](https://golang.org), [Github API](https://developer.github.com/v3/) and [akamensky's argparse](https://github.com/akamensky/argparse), [gookit's color](https://github.com/gookit/color), [olekukonko's tablewriter](https://github.com/olekukonko/tablewriter), [schollz's progressbar](https://github.com/schollz/progressbar) libraries.

## License

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
