# apollos-clone

## Develop

Install the package in editable mode

```
pip install -e .[dev]
```

## Deploy

Build and upload

```
pip install build twine
python -m build
twine upload dist/*
```
