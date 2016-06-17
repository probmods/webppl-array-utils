# webppl-array-utils

This package includes several array utility functions that were
removed from core WebPPL at version 0.8:

    ringForward
    ringBackward
    mapPairs2
    mapPairsC
    mapPairsNC
    mapReduce
    mapReduce1
    insertAt
    removeAt
    replaceAt
    drop
    take
    dropWhile
    takeWhile

## Installation

To globally install `webppl-array-util`, run:

    mkdir -p ~/.webppl
    npm install --prefix ~/.webppl webppl-array-util

## Usage

Once installed, you can make the functions in this package available
to `program.wppl` by running:

    webppl program.wppl --require webppl-array-utils

## Tests

Run the tests with:

    npm run test
