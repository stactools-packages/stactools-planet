# stactools-planet

![CI](https://github.com/stactools-packages/planet/actions/workflows/continuous-integration.yml/badge.svg?branch=main)
![PyPI](https://img.shields.io/pypi/v/stactools-planet)

A "planet" command extension for [stactools](https://github.com/stac-utils/stactools).

Note that the new recommended path to get STAC metadata for Planet orders is to request it as part of the API call, see 
[planet order delivery docs](https://developers.planet.com/apis/orders/delivery/#stac-metadata). STAC metadata from the
Planet API should be considered 'official' - this repo was made before Planet supported STAC output.

## Installation

```
python -m pip install stactools-planet
```

## Usage

```
stac planet --help
```

```
Usage: stac planet [OPTIONS] COMMAND [ARGS]...

Options:
  --help  Show this message and exit.

Commands:
  convert-order  Convert Planet Order data to STAC Collection
```
