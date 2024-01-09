# apollos-clone

## Develop

Install the package in editable mode

```
pip install -e .[dev]
```

## Testing

To run tests, install in editable mode to load module onto the PATH, then run pytest

```
pip install -e .[dev]
pytest
```

## Deploy

Build and upload

```
pip install build twine
python -m build
twine upload dist/*
```
