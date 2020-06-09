# PythonTemplate
Python project template for generic libraries.

* VS Code project code-workspace
* pytest
* flake8
* mypy
* GitHub build workflow
* Makefile

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
