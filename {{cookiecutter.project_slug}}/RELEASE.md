# Making a new release of}

## Manual release

### Python package

This project can be distributed as Python
packages. Before generating a package, we first need to install `build`.

```bash
pip install build twine hatch
```

Bump the version using `hatch`.

```bash
hatch version <new-version>
```

To create a Python source package (`.tar.gz`) and the binary package (`.whl`) in the `dist/` directory, do:

```bash
rm -rf dist/*
python -m build
```

> `python setup.py sdist bdist_wheel` is deprecated and will not work for this package.

Then to upload the package to PyPI, do:

```bash
twine upload dist/*
```
