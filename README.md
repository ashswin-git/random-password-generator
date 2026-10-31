# Random Password Generator

![Python](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)
![Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)

Day 1 of a 100-day lightweight Python project series.

A small command-line tool that creates strong, random passwords using Python's `secrets` module (cryptographically secure).

## Features

- Configurable password length
- Generate one or many passwords at once
- Toggle lowercase, uppercase, digits, and symbols
- Guarantees at least one character from each selected set
- Optional shell-friendly symbol set
- Zero third-party dependencies

## Built with

- **Language:** Python 3.10+
- **Standard library:** `secrets`, `string`, `argparse`
- No third-party packages

Part of the [daily-code](https://github.com/ashswin-git/daily-code) 100-day series (Day 1).

## Installation

```bash
git clone https://github.com/ashswin-git/random-password-generator.git
cd random-password-generator
python3 main.py --help
```

No `pip install` step is required.

## Usage

```bash
# Default: one 16-character password
python3 main.py

# Custom length
python3 main.py --length 24

# Generate 5 passwords
python3 main.py --count 5 --length 20

# Letters and digits only
python3 main.py --no-symbols

# Shell-friendlier symbols
python3 main.py --symbols-only-safe
```

## Example

```text
$ python3 main.py --length 20 --count 3
kP9@mX2!qL7#vR4$wN8t
H3b$Y6n&Q1c*Z8f@M5pW
aR7!uT4#jK9$eL2%wP6x
```

## Requirements

- Python 3.10+
- Standard library only

## License

No license file has been added yet.
