<div align="center">
<h1>asdf-elm</h1>
<span><a href="https://elm-lang.org">Elm</a> plugin for asdf version manager</span>
</div>
<hr />

[![Main workflow](https://github.com/asdf-community/asdf-elm/workflows/Main%20workflow/badge.svg)](https://github.com/asdf-community/asdf-elm/actions)
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors)
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
<!-- prettier-ignore -->
<table>
  <tr>
    <td align="center"><a href="https://bsky.moe"><img src="https://avatars3.githubusercontent.com/u/38746192?v=4" width="100px;" alt="BSKY"/><br /><sub><b>BSKY</b></sub></a><br /><a href="https://github.com/asdf-community/asdf-elm/commits?author=imbsky" title="Code">💻</a> <a href="https://github.com/asdf-community/asdf-elm/commits?author=imbsky" title="Documentation">📖</a> <a href="#maintenance-imbsky" title="Maintenance">🚧</a></td>
  </tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the
[all-contributors](https://github.com/all-contributors/all-contributors)
specification. Contributions of any kind welcome!

## License

&copy; Contributors Licensed under the
[Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0).
