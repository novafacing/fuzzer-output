# Standard Fuzzer Output Proposal

## Requirements

* The standard should be easy for fuzzers to adopt
* The standard should be easy for users to consume
* The standard should support extra fields
* The standard should be usable for many types of fuzzer
* The standard should be reasonable to write by hand

## The SARIF Format

SARIF is a specification in JSON schema for JSON and YAML formatted documents to
describe the results of using static analysis tools on code and binary objects. This
format provides several key tools which can be adapted to use for dynamic analysis tools
such as fuzzers as well.

### Support

SARIF is an open format published by OASIS, and is used by several key corporate tools,
notably GitHub, which supports uploading SARIF results for ingest into dashboards for
vulnerability and defect management.

## Streaming Log Format


## Results Format