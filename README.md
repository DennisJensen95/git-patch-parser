# Patch

[![Checks](https://github.com/DennisJensen95/git-patch-parser/actions/workflows/ci.yml/badge.svg)](https://github.com/DennisJensen95/git-patch-parser/actions/workflows/ci.yml)
![Code coverage](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/DennisJensen95/2b7862c80c14d562c8659e1283543190/raw/git-patch-parser.json)


Rust crate for parsing and producing patch files in the [Unified Format].

The parser attempts to be forgiving enough to be compatible with diffs produced
by programs like git. It accomplishes this by ignoring the additional code
context and information provided in the diff by those programs.

See the **[Documentation]** for more information and for examples.

[Unified Format]: https://www.gnu.org/software/diffutils/manual/html_node/Unified-Format.html
[Documentation]: https://docs.rs/patch
