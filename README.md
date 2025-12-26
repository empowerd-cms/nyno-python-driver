# nyno (Python driver)
Python client for Nyno (https://nyno.dev) server.

## Installation
```bash
pip install nyno # or: uv add nyno


## Usage
from nyno import NynoClient

client = NynoClient(credentials="change_me")


# Build package
uv run python -m build

# Upload
uv run python -m twine upload dist/*          

# PyPI
https://pypi.org/project/nyno/
