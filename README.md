# postman-test-suite

## Setup

1. Get environment file `env.json`

2. Get data file `APIAutomationCreds-Releasetestbed.csv`

3. install newman

```
npm install
```

## Run Tests

```
newman run -k tests/postman-test-suite.postman_collection.json -d APIAutomationCreds-Releasetestbed.csv -e env.json
```
