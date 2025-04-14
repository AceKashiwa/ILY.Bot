# ILY_Bot

[![License](https://img.shields.io/badge/license-MIT-green)](./LICENSE)
[![Python](https://img.shields.io/badge/python-3.9%2B-blue)](https://www.python.org/)
[![NoneBot2](https://img.shields.io/badge/NoneBot2-v2.4.2-green)](https://nonebot.dev/)
[![pdm-managed](https://img.shields.io/endpoint?url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fpdm-project%2F.github%2Fbadge.json)](https://pdm-project.org)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)

## About

`ILY_Bot` is a personal bot project built with [NoneBot2](https://nonebot.dev/). It is designed for learning and experimenting with Python and bot development frameworks.

## Installation

1. Ensure you have Python 3.9 or above installed.
2. Install dependencies using [PDM](https://pdm-project.org/):

   ```bash
   powershell -ExecutionPolicy ByPass -c "irm https://pdm-project.org/install-pdm.py | py -"
   pdm install
   ```

## How to start

1. generate project using `nb create` .
2. create your plugin using `nb plugin create` .
3. writing your plugins under `src/plugins` folder.
4. run your bot using `nb run --reload` .

## Documentation

See [Docs](https://nonebot.dev/)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
