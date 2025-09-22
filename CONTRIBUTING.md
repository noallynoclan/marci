# Contributing to marci

Thanks for contributing! Please follow these steps:

1. Fork the repo and create a feature branch.
2. Install dev dependencies: `pip install -e .[dev]`.
3. Run tests with `pytest` and ensure `ruff` and `black` pass.
4. Submit a PR with a clear description and update `CHANGELOG.md` if needed.

## Development quickstart

```bash
python -m venv .venv
. .venv/Scripts/Activate.ps1
pip install -U pip
pip install -e .[dev]
pytest -q
```
