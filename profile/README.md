# About :information_source:

[![chat](https://img.shields.io/badge/chat-a32236?labelColor=ed425c&style=flat-square)](https://matrix.to/#/#clip-project:matrix.org)

Want to learn [command syntax](https://github.com/command-line-interface-pages/cli-pages), [hierarchy structure](https://github.com/command-line-interface-pages/directory-pages) and command configs? Then this
project is for you! Don't just copy-paste things, learn them. :smile:

> :bell: Note for programmers: all pages are written in a [parsable way](https://github.com/command-line-interface-pages/syntax/blob/main/base.md) so
> it's possible to automatically extract some data from them to handle it.

## Installation :smile:

Via the following command you can install our page [render](https://github.com/command-line-interface-pages/v2-tooling/tree/main/clip-view):

```sh
temp="$(mktemp)"
wget -O "$temp" https://raw.githubusercontent.com/command-line-interface-pages/v2-tooling/main/clip-view/makefile
make -f "$temp" remote-install
```

To verify whether if successfully installed type `clip-view --version`.

## Uninstallation :disappointed:

All tools are being installed in the `/home/$USER/.local/bin` directory. So to remove
them just run the `rm` command like `rm /home/$USER/.local/bin/clip-view`.

## Expectations from the end user :books:

We assume that the end user is already familiar with some programming stuff. To
be more precise we expect all page syntax to be understandable by default no
matter what. When we encounter some repetitive problem we standardize a way
to solve it. We don't handle each page specifically.

## Contributions :hammer_and_wrench:

Each repository contains a link to its contributing guide (named CONTRIBUTING.md)
where you can learn how to get started with writing your own pages, [themes](https://github.com/command-line-interface-pages/themes)
or [tools](https://github.com/command-line-interface-pages/v2-tooling).

## Current goals :checkered_flag:

Current goals are listed in each repo separately like [here](https://github.com/command-line-interface-pages/cli-pages#current-goals-checkered_flag).

## Supported by :heart_eyes:

[![tldr](https://img.shields.io/badge/TlDr-a32236?labelColor=ed425c&style=flat-square)](https://github.com/tldr-pages/tldr/pull/9845)
[![cheat](https://img.shields.io/badge/Cheat-a32236?labelColor=ed425c&style=flat-square)](https://github.com/cheat/cheatsheets/pull/226)
[![cheatsheets](https://img.shields.io/badge/Cheatsheets-a32236?labelColor=ed425c&style=flat-square)](https://github.com/rstacruz/cheatsheets/pull/1953)
[![eg](https://img.shields.io/badge/Eg-a32236?labelColor=ed425c&style=flat-square)](https://github.com/srsudar/eg/pull/97)
