# OpenFaaS Golang HTTP template with Go Modules

This repository contains an updated version of the `golang-http` template for
newer versions of Go, using go modules.

One further addition is the inclusion of `Host` and `Path` strings in the
incoming request, which are required for e.g. function endpoint authorization.

## Quick Start

To get started, simply pull the template:

```
$ faas template pull https://github.com/adaptant-labs/openfaas-golang-http-gomod-template
```

## Licensing

Released under the terms of the MIT License.
