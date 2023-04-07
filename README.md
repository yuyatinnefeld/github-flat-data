# Bitcoin Price ETL via Github Flat Data

## [Flat Data Viewer](https://flatgithub.com/yuyatinnefeld/github-flat-data)

## About Github Flat Data
Flat Data eschews the complexity of many tools in the data/ETL space in favor of something simple and flexible enough for many workloads, but which requires no user-maintained infrastructure. While Flat has a ton of utility for developers, we want to make it easier for scientists, journalists, and other developer-adjacent audiences to develop lightweight, data-driven apps.

## Setup

1. create a public github repo
2. give persmissions to github-actions[bot]
- check if "Read and write permissions" are enabled in Settings -> Actions -> General -> Workflow permissions
3. write .github/workflows/flat.yml
4. write a btc-price-postprocessed.json to store the fetched data
5. write an empty btc-price.json which is updated through postprocess.js
