# pystream-rs
[![v0.0.1](https://img.shields.io/badge/version-v0.0.1-blue.svg)](https://github.com/nachatz/pystream-rs)
[![License](https://img.shields.io/badge/license-Apache%202-brightgreen.svg)](https://github.com/nachatz/pystream-rs/blob/master/LICENSE.txt)


Streaming interfaces using highly optimized I/O with Rust bindings to Python.

&nbsp; 
## Prerequisites for development

Before you begin, ensure you have met the following requirements:

- **[Poetry](https://python-poetry.org/)**: Make sure you have Poetry, a Python dependency management and packaging tool, installed on your system. You can install it by following the instructions on the Poetry website. This will handle all of the environments for your application to eradicate the need of local versioning, ensuring all developers have a safe and immediate environment.

- **[Python](https://www.python.org/downloads/)**: This project requires Python. You can download the latest version of Python from the official Python website.

- **[Rust](https://www.rust-lang.org/tools/install)**: For development, Rust is required for pyo3 bindings.


## Make commands

This project includes a set of make commands to help you manage your development tasks. Here are the available commands:


- `make install`: Install project dependencies, including development extras.

- `make fmt`: Format code using Black. Use the FLAGS variable to pass additional formatting options. Example: make fmt FLAGS="--exclude some_folder".

- `make mypy`: Run MyPy type checking.

- `make pylint`: Run pylint for code analysis.

- `make check`: Run formatting and type checking (fmt and mypy).

- `make validate`: Run full validation, including checks, tests, and coverage.