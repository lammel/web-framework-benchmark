# Web Framework Benchmark

## Installation

- `go get github.com/lammel/web-framework-benchmark`

## Running Benchmark

```sh
go test -bench=.
```

## Tested Frameworks

Currently [Echo v4](https://github.com/labstack/echo) and [Gin](https://github.com/gin-gonic/gin) are the frameworks tested with benchmarks for predefined router configurations.

To add more frameworks add the required wrapper for route handling and benchmark execution to `router_test.go`
