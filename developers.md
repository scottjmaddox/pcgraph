# PCGraph Developer Documentation

## Installing dev dependencies

```sh
rm -rf .venv
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip hatchling hatch-vcs
pip install ".[test]"
```

## Testing

```sh
pytest -v
```
