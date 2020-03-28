# NZ Covid-19 Visualization

## Overview

This is a side project that I built to visualize the cluster of confirmed cases of the coronavirus disease (COVID-19) in New Zealand. Thanks to NZ Ministry of Health's excellent data collection and transparency, we can keep track of the country's progress in fighting this unprecedented crisis. It will be interesting if we can collect the data everyday and playback after a period of time to observe the changes.

## Data source

The cases data are pulled from New Zealand Ministry of Health official website.

The District Health Board geospatial data is obtained from [StatsNZ](https://datafinder.stats.govt.nz/layer/87883-district-health-board-2015/), simplified and converted into `geojson` format to be used.

## Requirements

- Python 3
- [Pipenv](https://pipenv.kennethreitz.org/en/latest/) (Package manager for Python, try it if you haven't)

## Installation and Usage

    $ pipenv install
    $ pipenv shell
    $ (covid-19) jupyter notebook