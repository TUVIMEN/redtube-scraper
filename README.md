# redtube-scraper

A bash script for scraping redtube video metadata in json.

## Requirements

 - [reliq](https://github.com/TUVIMEN/reliq)
 - [jq](https://github.com/stedolan/jq)

## Installation

    install -m 755 redtube-scraper /usr/bin

## Json format

Here's example of a [video](video-example.json).

## Usage

It works as recursive spider getting urls from every page starting from URL.

    redtube-scraper DIR URL
