# atk4/community

Community maintained extensions for [atk4/data](https://github.com/atk4/data) and [atk4/ui](https://github.com/atk4/ui).  

[![Build](https://github.com/atk4/community/actions/workflows/test-unit.yml/badge.svg?branch=develop)](https://github.com/atk4/community/actions?query=branch:develop)
[![CodeCov](https://codecov.io/gh/atk4/community/branch/develop/graph/badge.svg)](https://codecov.io/gh/atk4/community)
[![GitHub release](https://img.shields.io/github/release/atk4/community.svg)](https://github.com/atk4/community/releases)

## Installation

Run

```
composer require atk4/community
```

to require this and official `atk4/data` and `atk4/ui` packages.

## Documentation

Source code itself and demos are the documentation. If you miss some usecase and once you figured out the solution, feel free to contribute a demo.

## Support

This repository is created from atk4 developers for atk4 developers. Please respect everyone interests and always use constructive tone of language. Before you ask for something, make sure tried to figure out the answer by yourself.

For discussion use [Discord](https://discord.gg/QVKSk2B).

For reporting issues use [GitHub issues](https://github.com/atk4/community/issues). If you seek a commercial support, mention this in your issue explicitly.

Feature requests are welcomed but noone is going to serve you. The best way to express an interest in some feature is to contribute a code.

## Contributions

For contributions use [GitHub pull requests](https://github.com/atk4/community/pulls).

A pull request must either fix some bug or implement a new feature. Either way a test is required.

New data feature must be placed under `Atk4\Community\Data\Xxx` namespace and fully covered with an unit test(s).

New UI feature must be placed under `Atk4\Community\Ui\Xxx` namespace and fully covered with a Behat test(s).

Please keep LoC and comments to a minimum to make review, maintenance and usage easier.
