# README

This is a template for python project that includes the following files:

- .gitignore - ignore python files
- .flake8 - flake8 configuration
- .pre-commit-config.yaml - enable flake8 and black
- pyproject.toml - black configuration

## Usage:

Clone this repository:

    $ git clone https://github.com/veganjay/python-template example
    $ rm -rf example/.git/

Install pipx if you have not already done so:

    $ pip install pipx

Install pre-commit if you have not already done so:

    $ pipx install pre-commit

Enable the pre-commit hooks:

    $ cd example/
    $ git init .
    $ pre-commit install
