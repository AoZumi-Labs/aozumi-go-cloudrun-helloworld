# AOZUMI Go Cloud Run Hello World fixture

A public, deployable Go web sample copied from [`GoogleCloudPlatform/golang-samples/run/helloworld`](https://github.com/GoogleCloudPlatform/golang-samples/tree/main/run/helloworld) at upstream commit `2b3125cd62992691f6dec8e86a65c926b1f6ae9e`. The source files and Apache-2.0 license are retained; this repository is for deployment compatibility testing.

```sh
go test ./...
go run .
```

The app reads `PORT` (default `8080`) and `NAME` (default `World`) and serves `GET /`.
