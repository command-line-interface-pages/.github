# About

Want something more thatn TlDr? Tired of non-standardized [TlDr](https://github.com/tldr-pages/tldr) pages and lack of page parsability?
Want be able to explore file system hierichy explanations? Then this project is for you!
Write pages in Markdown-like language, or YAML or even TOML and use one unified syntax for them.

## More information

:heavy_check_mark: Get more details:

![image](https://user-images.githubusercontent.com/42812113/219330370-4ac69b1e-b5bd-46c1-8b40-bc4e6e3c17dc.png)

then [TlDr](https://github.com/tldr-pages/tldr) can provide:

![image](https://user-images.githubusercontent.com/42812113/219330632-fa110dbf-91c8-41fd-84cc-8338b74f94c8.png)

See not just a concrete example, but also what kind of arguments and how many of them are expected. :smile_cat:

## Directory explanations

:heavy_check_mark: Read about directories and files in them:

![image](https://user-images.githubusercontent.com/42812113/219865611-ae3e4b1b-10f2-4532-bf8e-b6b1d0db7733.png)

while it's impossible with [TlDr](https://github.com/tldr-pages/tldr).

# Differences from TlDr

- All rules are required, no exceptions are done, everything is formalized and
  clear. Instead of using primitive placeholder syntax we prefer feature rich one with
  a customizable rendering. We don't like do things manually and write more then we need.
- Intead of relying on numerous clients we develop and use only one official
  client. It doesn't mean that third-party clients can't be created. But such
  clients are not supported officially and we don't depend on third-party client
  issues. What it means for outside developers is that their clients can be broken
  but only if they ignored some announcment about breaking changes.

# Expectations from the end user

We assume that the end user is already familiar with some programming stuff. To
be more precise we expect all page syntax to be understandable by default no
matter it what. When we encounter some repetetive problem we standardize a way
to solve it. We don't handle each page specificly. It means that all page are
written in the same way and syntax may be slithtly harder to read than in TlDr.
If you are not that kind of user who prefers standardization over readability
(even the last one is kept okay) [TlDr](https://github.com/tldr-pages) project
may be a better choise.

# Contributions

## How to contribute?

There is no much freedom in allowed languages to simplify tooling support.
Just the following languages to use are permitted to be used in this organization:

- [Bash](https://en.wikipedia.org/wiki/Bash_\(Unix_shell\)) with [sed](https://en.wikipedia.org/wiki/Sed), [yq](https://mikefarah.gitbook.io/yq/): GitHub Actions
- [Go](https://en.wikipedia.org/wiki/Go_\(programming_language): client and
  automation tools
- [TypeScript](https://en.wikipedia.org/wiki/TypeScript): Visual Studio Code
  extensions
- [Lua](https://en.wikipedia.org/wiki/Lua_\(programming_language\)): Micro extensions
- [Emacs Lisp](https://en.wikipedia.org/wiki/Emacs_Lisp): Emacs extensions

, but if you wanna write a tool prototype then any language can be used and such thing should be put in [this](https://github.com/command-line-interface-pages/prototypes) repository.

## What if I wanna more rights?

Then contribute regularly to this orgranization. It doesn't matter what repository you contribute to,
just the fact that you invest your time for it is considered and proposed changes quality by all means. :smile:
