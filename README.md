# sf-tree-history

Tracking the history of trees in San Francisco.

This repository [uses CircleCI](https://circleci.com/gh/simonw/sf-tree-history) to retrieve the [official CSV file of trees in San Francisco](https://data.sfgov.org/City-Infrastructure/Street-Tree-List/tkzw-k3nq) once a day and track any changes to it over time using the git commit history.

It uses [csv-diff](https://github.com/simonw/csv-diff) to generate human-readable commit messages.

You can see recent changes to the CSV file here: https://github.com/simonw/sf-tree-history/commits/master
