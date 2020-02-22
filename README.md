<div align="center">
<h1>asdf-elm</h1>
<span><a href="https://elm-lang.org">Elm</a> plugin for asdf version manager</span>
</div>
<hr />

[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/asdf-community/asdf-elm/Main%20workflow?style=flat-square)](https://github.com/asdf-community/asdf-elm/actions)
[![All Contributors](https://img.shields.io/badge/all_contributors-3-orange.svg?style=flat-square)](#contributors)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![License](https://img.shields.io/github/license/asdf-community/asdf-elm?style=flat-square&color=brightgreen)](https://github.com/asdf-community/asdf-elm/blob/master/LICENSE)

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

## Contributors

Thanks goes to these wonderful people
([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://bsky.moe"><img src="https://avatars3.githubusercontent.com/u/38746192?v=4" width="100px;" alt=""/><br /><sub><b>BSKY</b></sub></a><br /><a href="https://github.com/asdf-community/asdf-elm/commits?author=imbsky" title="Code">💻</a> <a href="https://github.com/asdf-community/asdf-elm/commits?author=imbsky" title="Documentation">📖</a> <a href="#maintenance-imbsky" title="Maintenance">🚧</a> <a href="#infra-imbsky" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
    <td align="center"><a href="https://github.com/brianvanburken"><img src="https://avatars1.githubusercontent.com/u/1044316?v=4" width="100px;" alt=""/><br /><sub><b>Brian van Burken</b></sub></a><br /><a href="https://github.com/asdf-community/asdf-elm/commits?author=brianvanburken" title="Code">💻</a> <a href="https://github.com/asdf-community/asdf-elm/commits?author=brianvanburken" title="Documentation">📖</a></td>
    <td align="center"><a href="https://haritaso.me"><img src="https://avatars2.githubusercontent.com/u/35331195?v=4" width="100px;" alt=""/><br /><sub><b>Haritaso</b></sub></a><br /><a href="#infra-Haritaso" title="Infrastructure (Hosting, Build-Tools, etc)">🚇</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the
[all-contributors](https://github.com/all-contributors/all-contributors)
specification. Contributions of any kind welcome!

## License

Licensed under the
[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).
