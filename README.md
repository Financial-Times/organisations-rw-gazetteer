# Gazetteer Reader/Writer 
[![Circle CI](https://circleci.com/gh/Financial-Times/ces-gazetteer-rw.svg?style=shield)](https://circleci.com/gh/Financial-Times/ces-gazetteer-rw)[![Go Report Card](https://goreportcard.com/badge/github.com/Financial-Times/ces-gazetteer-rw)](https://goreportcard.com/report/github.com/Financial-Times/ces-gazetteer-rw) [![Coverage Status](https://coveralls.io/repos/github/Financial-Times/ces-gazetteer-rw/badge.svg)](https://coveralls.io/github/Financial-Times/ces-gazetteer-rw)
 
__An API for reading/writing concepts to the gazeteer api

## Installation

For the first time:

`go get github.com/Financial-Times/ces-gazetteer-rw`

or update:

`go get -u github.com/Financial-Times/ces-gazetteer-rw`


## Running

TODO

## Endpoints

TODO: Add examples

### PUT /UUID
TODO
### GET /UUID
Gets a given representation of a concept from the CES gazetteet given a UUID
If not found, you'll get a 404 response.

### DELETE /UUID
Will return 204 if successful, 404 if not found

### Admin endpoints

Healthchecks: [http://localhost:8080/__health](http://localhost:8080/__health)
Ping: [http://localhost:8080/ping](http://localhost:8080/ping) or [http://localhost:8080/__ping](http://localhost:8080/__ping)
Build Info: [http://localhost:8080/build-info](http://localhost:8080/build-info) or [http://localhost:8080/build-info](http://localhost:8080/__build-info) 
GTG: [http://localhost:8080/build-info](http://localhost:8080/__gtg) 
