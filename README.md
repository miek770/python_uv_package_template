# My Python Package Project Template

This is a Python package project template that combines the following libraries:

- `black`: To automate formatting.
- `pre-commit`: To active pre-commit hooks, including `black`.
- `pytest`: To test the project.
- `twine`: To publish to PyPI, for systems with older `uv`.

> The rest of the readme is meant to be used as a template for package projects. The information is otherwise irrelevant for this template.

## Installation

Install the package from [PyPI](https://pypi.org/) with [pip](https://pypi.org/project/pip/) using:

```
pip install <pkg>
```

## Usage

### Examples

## Contributing

Contributions are welcome; please:

- Use [uv](https://github.com/astral-sh/uv).
- Run `uv sync` to install the development environment.
- Run `uv run pre-commit install` to active the pre-commit hooks, including [black](https://github.com/psf/black).
- Ensure [pytest](https://docs.pytest.org/en/stable/) runs without failures with `make tests`.
- Be nice.

The source code is hosted at `<homepage>`.

## License

`<pkg>` is licensed under the MIT License. See [LICENSE](LICENSE) file for details.
