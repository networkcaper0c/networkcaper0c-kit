# networkcaper0c-kit

Validate JSON files and print a normalized form.

Small, dependency-free Python utility package generated for day-to-day file chores.
Standard library only — no third-party imports.

## Install

```bash
pip install -e .
```

## Usage

```bash
python -m networkcaper0c_kit.cli --help
```

```python
from networkcaper0c_kit.core import Networkcaper0cTool

tool = Networkcaper0cTool()
print(tool)
```

## Layout

```
networkcaper0c_kit/
  __init__.py
  core.py
  cli.py
tests/
  test_core.py
```

## License

MIT © 2026 networkcaper0c
