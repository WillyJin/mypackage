# packaging_test

[![PyPI](https://img.shields.io/pypi/v/packaging_test.svg)][pypi status]
[![Status](https://img.shields.io/pypi/status/packaging_test.svg)][pypi status]
[![Python Version](https://img.shields.io/pypi/pyversions/packaging_test)][pypi status]
[![License](https://img.shields.io/pypi/l/packaging_test)][license]

[![Read the documentation at https://packaging_test.readthedocs.io/](https://img.shields.io/readthedocs/packaging_test/latest.svg?label=Read%20the%20Docs)][read the docs]
[![Tests](https://github.com/WillyJin/packaging_test/actions/workflows/python-test.yml/badge.svg)][tests]
[![Codecov](https://codecov.io/gh/WillyJin/packaging_test/branch/main/graph/badge.svg)][codecov]

[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)][pre-commit]
[![Black](https://img.shields.io/badge/code%20style-black-000000.svg)][black]

[pypi status]: https://pypi.org/project/packaging_test/
[read the docs]: https://packaging_test.readthedocs.io/
[tests]: https://github.com/WillyJin/packaging_test/actions?workflow=Tests
[codecov]: https://app.codecov.io/gh/WillyJin/packaging_test
[pre-commit]: https://github.com/pre-commit/pre-commit
[black]: https://github.com/psf/black

## Installation

You can install _mypackage_ via [pip] from [PyPI]:

```console
$ pip install mypackage
```

## Contributing

Contributions are very welcome.
To learn more, see the [Contributor Guide][Contributor Guide].

## License

Distributed under the terms of the [MIT license][License],
_mypackage_ is free and open source software.

## Issues

If you encounter any problems,
please [file an issue][Issue Tracker] along with a detailed description.


<!-- github-only -->

[command-line reference]: https://packaging_test.readthedocs.io/en/latest/usage.html
[License]: https://github.com/WillyJin/packaging_test/blob/main/LICENSE
[Contributor Guide]: https://github.com/WillyJin/packaging_test/blob/main/CONTRIBUTING.md
[Issue Tracker]: https://github.com/WillyJin/packaging_test/issues


## Building the Documentation

You can build the documentation locally by installing the documentation Conda environment:

```bash
conda env create -f docs/environment.yml
```

activating the environment

```bash
conda activate sphinx_packaging_test
```

and [running the build command](https://www.sphinx-doc.org/en/master/man/sphinx-build.html#sphinx-build):

```bash
sphinx-build docs _build/html --builder=singlehtml --jobs=auto --write-all; open _build/html/index.html
```