[![Python](https://github.com/MarekPikula/python-poetry-vscode-template/actions/workflows/python.yaml/badge.svg)](https://github.com/MarekPikula/python-poetry-vscode-template/actions/workflows/python.yaml)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/fixme.svg)](https://pypi.org/project/fixme)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

# Python + Poetry + VS Code (devcontainer) template

It's a quick and easy template repository for Python projects. It's heavily
opinionated and represents personal taste of the author.

## Checklist

1. Find, check and change the following phrases:
    - *FIXME* (also lowercase),
    - *python-poetry-vscode-template*

1. Adjust the Python version in the following files:
    - .devcontainer/Dockerfile
    - pyproject.toml
    - .github/workflows/build.yaml

1. Add `PYPI_PASSWORD` secret if you want to publish to PyPI and enable the
   workflow step.

1. Set *Workflow permissions* to *Read and write permissions* in
   *Actions→General* section in project settings. Needed for devcontainer image
   build.
