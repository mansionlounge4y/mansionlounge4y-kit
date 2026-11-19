# mansionlounge4y-kit

Summarize numeric CSV columns (n / min / max / mean).

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m mansionlounge4y_kit.cli --help
```

```python
from mansionlounge4y_kit.core import Mansionlounge4yTool

tool = Mansionlounge4yTool()
print(tool)
```

## Layout

```
mansionlounge4y_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 mansionlounge4y
