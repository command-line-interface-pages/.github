# Used languages

Just the following languages to use are allowed to be used in this organization:

- [Bash](https://en.wikipedia.org/wiki/Bash_\(Unix_shell\)) with [sed](https://en.wikipedia.org/wiki/Sed) and [jq](https://en.wikipedia.org/wiki/Jq_\(programming_language\)): GitHub Actions  
  Note that we have client written in Bash, which will be rewritten in Go to conform our policy.
- [Go](https://en.wikipedia.org/wiki/Go_\(programming_language): client and
  automation tools
- [TypeScript](https://en.wikipedia.org/wiki/TypeScript): Visual Studio Code
  extensions
- [Lua](https://en.wikipedia.org/wiki/Lua_\(programming_language\)): Micro extensions
- [Emacs Lisp](https://en.wikipedia.org/wiki/Emacs_Lisp): Emacs extensions

# Differences from TlDr

- All rules are required, no exceptions are done, everything is formalized and
  clear.
- Instead of using primitive placeholder syntax we prefer feature rich one with
  a customizable rendering.
- Intead of trying to rely on numerous clients we develop and use only one
  client. It doesn't mean that third-party clients can't be created. But such
  clients are not supported officially and we don't depend on third-party client
  issues.

# Expectations from the end user

We assume that the end user is already familiar with some programming stuff. To
be more precise we expect all page syntax to be understandable by default no
matter it what. When we encounter some repetetive problem we standardize a way
to solve it. We don't handle each page specificly. It means that all page are
written in the same way and syntax may be slithtly harder to read than in TlDr.
If you are not that kind of user who prefers standardization over readability
(even the last one is kept okay) [TlDr](https://github.com/tldr-pages) project
may be a better choise.
