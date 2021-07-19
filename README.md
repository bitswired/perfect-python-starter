# Welcome

This is an **opinionated** template repository to help you implement best practices easily in your Python projects.
It's easy, for you next projects, create the repository according to this template.
Then follow instruction in the [Getting Started section](#foo).

# Getting Started

1. Rename the package name
   1. The folder named your_package_name
   2. In the packages section, line 8 in the pyproject.toml
   3. In the mypy section, line 41 in the pyproject.toml file, with your real package
2. Install pre-commit hooks `poetry run pre-commit install`
3. (Optinal) Change the language version if needed
   1. In the pyproject.toml file line 13 and 36
   2. In the .pre-commit-config.yaml file line 22

# Dependency Management and Package Builder

# Formatting

## General Format: Black

## Sort Imports: Isort

# Linting

## General Linting: Flake8

## Type Checking: Flake8 Mypy
