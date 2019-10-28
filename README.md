<div align="center">
<h1>asdf-elm 📦</h1>
<span><a href="https://elm-lang.org">Elm</a> plugin for asdf version manager</span>
</div>
<hr />

[![Main workflow](https://github.com/asdf-community/asdf-elm/workflows/Main%20workflow/badge.svg)](https://github.com/asdf-community/asdf-elm/actions)
[![Average time to resolve an issue](https://isitmaintained.com/badge/resolution/asdf-community/asdf-elm.svg)](https://isitmaintained.com/project/asdf-community/asdf-elm 'Average time to resolve an issue')
[![Percentage of issues still open](https://isitmaintained.com/badge/open/asdf-community/asdf-elm.svg)](https://isitmaintained.com/project/asdf-community/asdf-elm 'Percentage of issues still open')
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![License](https://img.shields.io/github/license/asdf-community/asdf-elm?color=brightgreen)](https://github.com/asdf-community/asdf-elm/blob/master/LICENSE)

## Prerequirements

- Make sure you have the required dependencies installed:
  - curl
  - git
  - gunzip

## Installation

```bash
asdf plugin-add elm https://github.com/asdf-community/asdf-elm.git
```

## Usage

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to
install & manage versions.

## Useful information

asdf uses the `.tool-versions` for auto-switching between software versions. To
ease migration, you can have it read `elm.json` or `elm-package.json` file to
find out what version of Elm should be used. This only works with the exact
version. To do this, add the following to `~/.asdfrc`:

```
legacy_version_file = yes
```
