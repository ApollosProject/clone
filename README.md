# apollos-clone

## Develop

Install the package in editable mode

```
pip install -e .
```

## Deploy

Build and upload

```
pip install build twine
python -m build
twine upload dist/*
```
