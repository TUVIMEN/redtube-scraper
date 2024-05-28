# redtube-scraper

A bash script for scraping redtube videos metadata in json.

## Requirements

 - [reliq](https://github.com/TUVIMEN/reliq)
 - [jq](https://github.com/stedolan/jq)

## Installation

    install -m 755 redtube-scraper /usr/bin

## Json format

Here's example of a [video](video-example.json).

## Usage

It works as recursive spider getting urls from every page starting from URL, and saving results in files named by their id.

    redtube-scraper DIR URL
