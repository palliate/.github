---
layout: default
title: Linting
parent: Development
nav_order: 22
has_children: false
permalink: /development/linting
---

# Linting

To simplify [linting](https://en.wikipedia.org/wiki/Lint_(software)) palliate and its subprojects use [Trunk](https://trunk.io/).

Since all projects are git based and use a fair amount of TOML configuration files the following linters  and tools are always active:
* git-diff-check
* [gitleaks](https://gitleaks.io/)
* [actionlint](https://github.com/rhysd/actionlint) for GitHub Actions
* [markdownlint](https://github.com/DavidAnson/markdownlint) for Markdown
* [taplo](https://taplo.tamasfe.dev/) for TOML


For the Python subprojects the following linters and tools are active:
* [flake8](https://flake8.pycqa.org/en/latest/) all code formatting features are disabled
* [autopep8](https://github.com/hhatto/autopep8)
* [isort](https://pycqa.github.io/isort/)
* [pylint](https://pylint.pycqa.org/en/latest/)

For the C++ subprojects the following linters and tools are active:
* [clang-format](https://clang.llvm.org/docs/ClangFormat.html)
* [clang-tidy](https://clang.llvm.org/extra/clang-tidy/)

Please install [Trunk](https://trunk.io/products/check) or the corresponding VSCode Extension. Some useful commands:
* `trunk check` to run the linter jobs
* `trunk check --ci` if you want to see if there's breaking issues
* `trunk fmt` to automatically format non-conforming files

The configuration files for all linters and tools can be found in `.trunk/config/` relative to the repository's root directory.