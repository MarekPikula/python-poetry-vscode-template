[![build](https://github.com/MarekPikula/python-poetry-vscode-template/workflows/build/badge.svg)](https://github.com/MarekPikula/python-poetry-vscode-template/actions?query=workflow%3Abuild+branch%3Amain)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/fixme.svg)](https://pypi.org/project/fixme)

# Python + Poetry + VS Code (devcontainer) template

It's a quick and easy template repository for Python projects. It's heavily
opinionated and represents personal taste of the author.

## Checklist

1. Find, check and change the following phrases:
    - *FIXME* (also lowercase),
    - *python-poetry-vscode-template*

2. Adjust the Python version in the following files:
    - .devcontainer/Dockerfile
    - pyproject.toml
    - .github/workflows/build.yaml

3. Add `PYPI_PASSWORD` secret if you want to publish to PyPI and enable the
   workflow step.

4. Set *Workflow permissions* to *Read and write permissions* in
   *Actions→General* section in project settings. Needed for devcontainer image
   build.
