# datasette-tiles

[![PyPI](https://img.shields.io/pypi/v/datasette-tiles.svg)](https://pypi.org/project/datasette-tiles/)
[![Changelog](https://img.shields.io/github/v/release/simonw/datasette-tiles?include_prereleases&label=changelog)](https://github.com/simonw/datasette-tiles/releases)
[![Tests](https://github.com/simonw/datasette-tiles/workflows/Test/badge.svg)](https://github.com/simonw/datasette-tiles/actions?query=workflow%3ATest)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](https://github.com/simonw/datasette-tiles/blob/main/LICENSE)

Datasette plugin for serving MBTiles map tiles

## Installation

Install this plugin in the same environment as Datasette.

    $ datasette install datasette-tiles

## Demo

You can try this plugin out at https://datasette-tiles-demo.datasette.io/-/tiles

## Usage

This plugin scans all database files connected to Datasette to see if any of them are valid MBTiles databases.

It can 
