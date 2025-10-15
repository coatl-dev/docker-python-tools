# docker-python-tools

[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/coatl-dev/docker-python-tools/coatl.svg)](https://results.pre-commit.ci/latest/github/coatl-dev/docker-python-tools/coatl)

This repository is a collection of Docker images containing tools Python 2.7 and
3.12.

## Catalog

### python-tools:2.7-build

Use this Docker image to build and upload Python packages with Python 2.7, using
the following tools:

- `build`: Creates distribution packages (like `.whl` and `.tar.gz`) from your
  Python project.
- `twine`: Securely uploads these packages to PyPI or other package indexes.

### python-tools:3.12-build

Use this Docker image to build and upload Python packages with Python 3.12, using
the following tools:

- `build`: Creates distribution packages (like `.whl` and `.tar.gz`) from your
  Python project.
- `twine`: Securely uploads these packages to PyPI or other package indexes.

### python-tools:2.7-pip-tools

Use this Docker image for running `pip-compile` or `pip-sync` on your Python 2.7
project.
