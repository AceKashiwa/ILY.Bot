# ILY_Bot

[![License](https://img.shields.io/badge/license-MIT-green)](./LICENSE)
[![Python](https://img.shields.io/badge/python-3.9%2B-blue)](https://www.python.org/)
[![NoneBot2](https://img.shields.io/badge/NoneBot2-v2.4.2-green)](https://nonebot.dev/)
[![pdm-managed](https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fpdm-project%2F.github%2Fbadge.json)](https://pdm-project.org)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)

## About

`ILY_Bot` is a personal bot project built with [NoneBot2](https://nonebot.dev/). It is designed for learning and experimenting with Python and bot development frameworks.

## Features

- **Console Adapter**: Supports Console adapter for local testing.
- **Plugin Management**: Load plugins directly from `pyproject.toml`.
- **Code Quality**: Integrated with `ruff` for linting and formatting.
- **Extensibility**: Easily create and manage custom plugins.

## Installation

1. Ensure you have Python 3.9 or above installed.
2. Install dependencies using [PDM](https://pdm-project.org/):

   ```bash
   powershell -ExecutionPolicy ByPass -c "irm https://pdm-project.org/install-pdm.py | py -"
   pdm install
   ```

## How to Start

1. Generate a project using `nb create`.
2. Create your plugin using `nb plugin create`.
3. Write your plugins under the `src/plugins` folder.
4. Run your bot using:

   ```bash
   nb run --reload
   ```

## Changelog

### v0.1.1

- **Feature**: Added support for the Console adapter.
- **Feature**: Support loading plugin configurations from `pyproject.toml`.
- **Improvement**: Enhanced code formatting with `ruff`.
- **Bugfix**: Fixed compatibility issues.

## Documentation

For detailed documentation, visit the [NoneBot2 Docs](https://nonebot.dev/).

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
