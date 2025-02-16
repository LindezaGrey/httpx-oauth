# HTTPX OAuth

<p align="center">
    <em>Async OAuth client using HTTPX</em>
</p>

[![build](https://github.com/frankie567/httpx-oauth/workflows/Build/badge.svg)](https://github.com/frankie567/httpx-oauth/actions)
[![codecov](https://codecov.io/gh/frankie567/httpx-oauth/branch/master/graph/badge.svg)](https://codecov.io/gh/frankie567/httpx-oauth)
[![PyPI version](https://badge.fury.io/py/httpx-oauth.svg)](https://badge.fury.io/py/httpx-oauth)

<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-10-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

<p align="center">
<a href="https://github.com/sponsors/frankie567"><img src="https://md-btn.deta.dev/button.svg?text=Buy%20me%20a%20coffee%20%E2%98%95%EF%B8%8F&bg=ef4444&w=200&h=50"></a>
</p>

---

**Documentation**: <a href="https://frankie567.github.io/httpx-oauth/" target="_blank">https://frankie567.github.io/httpx-oauth/</a>

**Source Code**: <a href="https://github.com/frankie567/httpx-oauth" target="_blank">https://github.com/frankie567/httpx-oauth</a>

---

## Installation

```bash
pip install httpx-oauth
```


## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center"><a href="http://francoisvoron.com"><img src="https://avatars.githubusercontent.com/u/1144727?v=4?s=100" width="100px;" alt=""/><br /><sub><b>François Voron</b></sub></a><br /><a href="#maintenance-frankie567" title="Maintenance">🚧</a></td>
      <td align="center"><a href="http://xaviertorello.cat"><img src="https://avatars.githubusercontent.com/u/8709244?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Xavi Torelló</b></sub></a><br /><a href="https://github.com/frankie567/httpx-oauth/commits?author=XaviTorello" title="Code">💻</a></td>
      <td align="center"><a href="https://github.com/fullonic"><img src="https://avatars.githubusercontent.com/u/13336073?v=4?s=100" width="100px;" alt=""/><br /><sub><b>dbf</b></sub></a><br /><a href="https://github.com/frankie567/httpx-oauth/commits?author=fullonic" title="Code">💻</a></td>
      <td align="center"><a href="http://www.kentonparton.com"><img src="https://avatars.githubusercontent.com/u/20202312?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Kenton Parton</b></sub></a><br /><a href="https://github.com/frankie567/httpx-oauth/commits?author=KentonParton" title="Code">💻</a></td>
      <td align="center"><a href="https://github.com/stepan-chatalyan"><img src="https://avatars.githubusercontent.com/u/78931407?v=4?s=100" width="100px;" alt=""/><br /><sub><b>stepan-chatalyan</b></sub></a><br /><a href="https://github.com/frankie567/httpx-oauth/commits?author=stepan-chatalyan" title="Code">💻</a></td>
      <td align="center"><a href="https://github.com/Forst"><img src="https://avatars.githubusercontent.com/u/369699?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Foster Snowhill</b></sub></a><br /><a href="https://github.com/frankie567/httpx-oauth/commits?author=Forst" title="Code">💻</a></td>
      <td align="center"><a href="https://hatcher.work"><img src="https://avatars.githubusercontent.com/u/24600763?v=4?s=100" width="100px;" alt=""/><br /><sub><b>William Hatcher</b></sub></a><br /><a href="https://github.com/frankie567/httpx-oauth/commits?author=williamhatcher" title="Code">💻</a></td>
    </tr>
    <tr>
      <td align="center"><a href="https://github.com/thewchan"><img src="https://avatars.githubusercontent.com/u/49702524?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Matt Chan</b></sub></a><br /><a href="#platform-thewchan" title="Packaging/porting to new platform">📦</a></td>
      <td align="center"><a href="http://meka.rs"><img src="https://avatars.githubusercontent.com/u/610855?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Goran Mekić</b></sub></a><br /><a href="#platform-mekanix" title="Packaging/porting to new platform">📦</a></td>
      <td align="center"><a href="joonas.io"><img src="https://avatars.githubusercontent.com/u/9527681?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Joona Yoon</b></sub></a><br /><a href="https://github.com/frankie567/httpx-oauth/commits?author=joonas-yoon" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

## Development

### Setup environment

You should create a virtual environment and activate it:

```bash
python -m venv venv/
```

```bash
source venv/bin/activate
```

And then install the development dependencies:

```bash
pip install -r requirements.dev.txt
```

### Run unit tests

You can run all the tests with:

```bash
make test
```

Alternatively, you can run `pytest` yourself:

```bash
pytest
```

### Lint the code

Execute the following command to apply `isort` and `black` formatting and run typecheck:

```bash
make lint
```

## License

This project is licensed under the terms of the MIT license.
