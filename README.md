# datasette-census-boundaries

[![PyPI](https://img.shields.io/pypi/v/datasette-census-boundaries.svg)](https://pypi.org/project/datasette-census-boundaries/)
[![Changelog](https://img.shields.io/github/v/release/eyeseast/datasette-census-boundaries?include_prereleases&label=changelog)](https://github.com/eyeseast/datasette-census-boundaries/releases)
[![Tests](https://github.com/eyeseast/datasette-census-boundaries/workflows/Test/badge.svg)](https://github.com/eyeseast/datasette-census-boundaries/actions?query=workflow%3ATest)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/eyeseast/datasette-census-boundaries/blob/main/LICENSE)

Common US Census boundaries packaged in an installable SQLite database

## Installation

Install this plugin in the same environment as Datasette.

    datasette install datasette-census-boundaries

## Usage

Usage instructions go here.

## Development

To set up this plugin locally, first checkout the code. Then create a new virtual environment:

    cd datasette-census-boundaries
    python3 -m venv venv
    source venv/bin/activate

Now install the dependencies and test dependencies:

    pip install -e '.[test]'

To run the tests:

    pytest
