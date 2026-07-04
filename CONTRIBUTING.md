# Contributing to PromptForge

Thank you for your interest in contributing to PromptForge!

We welcome contributions of all kinds, including bug reports, feature requests, documentation improvements, tests, and code.

## Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/promptforge.git
cd promptforge
```

Create and activate a virtual environment:

### Linux / macOS

```bash
python -m venv .venv
source .venv/bin/activate
```

### Windows

```bash
python -m venv .venv
.venv\Scripts\activate
```

Install the development dependencies:

```bash
pip install -e .[dev]
```

## Running Tests

Run all tests:

```bash
pytest
```

Run tests with coverage:

```bash
pytest --cov
```

## Code Style

Before submitting a pull request, format and check the project:

```bash
black .
ruff check .
mypy .
```

## Branch Naming

Use descriptive branch names.

Examples:

* feature/compiler
* feature/parser
* fix/lexer-bug
* docs/readme

## Commit Messages

Follow conventional commits.

Examples:

```text
feat: add lexer support for variables
fix: correct parser error handling
docs: improve README
test: add lexer unit tests
```

## Pull Requests

Before opening a Pull Request:

* Make sure all tests pass.
* Format the code.
* Keep Pull Requests focused on a single feature or fix.
* Update documentation when necessary.

## Reporting Bugs

When reporting a bug, please include:

* Operating System
* Python version
* Steps to reproduce
* Expected behavior
* Actual behavior

## Feature Requests

Feature requests are welcome.

Please explain:

* What problem you are trying to solve.
* Why the feature is useful.
* A possible implementation if you have one.

## License

By contributing to PromptForge, you agree that your contributions will be licensed under the MIT License.
