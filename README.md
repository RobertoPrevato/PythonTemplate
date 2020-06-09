![Build](https://github.com/RobertoPrevato/PythonTemplate/workflows/Build/badge.svg)

# Python project template
Python project template for generic libraries.

* VS Code project code-workspace
* pytest
* flake8
* mypy
* GitHub build workflow
* Makefile
* setup.py starter file

## Getting started

```
# create Python virtual environment
python -m venv venv

# activate environment (Linux):
source venv/bin/activate

# activate environment (Windows):
venv\Scripts\activate

# install dependencies
pip install -r requirements.txt
```

## Makefile

```
# run tests:
make test

# run tests and write test coverage output
mate testcov
```

Manual releases:

```
# install dependencies for twine (once)
make prepforbuild

# create distribution package
make artifacts

# upload to the test pypi
make testrelease

# upload to pypi
make release
```
