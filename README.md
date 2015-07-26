[![Build Status][ci-img]][ci-url]
[![Coverage Status][cov-img]][cov-url]

# Ship Postfix Logs to Elasticsearch

Parses postfix log files from log files into a normalized JSON document and saves them to Elasticsearch.

## Install

    npm i log-ship-elasticsearch-postfix


## Features

- [x] drop in modules for: reader, parser, and elasticsearch
- [x] config file is human friendly ini



[ci-img]: https://travis-ci.org/DoubleCheck/log-ship-elasticsearch-postfix.svg
[ci-url]: https://travis-ci.org/DoubleCheck/log-ship-elasticsearch-postfix
[cov-img]: https://coveralls.io/repos/DoubleCheck/log-ship-elasticsearch-postfix/badge.svg
[cov-url]: https://coveralls.io/github/DoubleCheck/log-ship-elasticsearch-postfix
