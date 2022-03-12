# RESTler experiment

Data produced when running [RESTler](https://github.com/microsoft/restler-fuzzer) against API mock implementations generated by OAS DB.

## Overview

Each top-level directory contains everything related to a specific sample. Inside each sample's directory, the following can be found:

- RestlerResults: the output produced by RESTler for the given sample.
- annotations: the annotation file of the given sample.
- apis: the mock API of the given sample.
- samples: the OpenAPI specification of the sample.
- sinatra_logs: the logs produced by the API while being tested by RESTler.
