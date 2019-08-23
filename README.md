# Support-Backend API Tests

This project contains smoke/functional tests for Support Backend APIs. These will be run across all the mentioned markets.

## Prerequisite

The following must be installed

* newman

#### To run the tests
- ./newmantests -e envName -c <collection name | all> -m <market name | all>
- All the environment file values, collection names and market names are picked from properties.json
- Whenever any new parameter is added, the same need to be added to the properties.json




