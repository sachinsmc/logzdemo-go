# logzdemo-go
Golang logz.io demo

## Setup & Installation

Create account on logz and get Account Token key update key in config account_token.

Donwload and run the OpenTelemetry Collector 

[Intel OSX](https://github.com/open-telemetry/opentelemetry-collector-contrib/releases/download/v0.33.0/otelcontribcol_darwin_amd64)

[Silicon OSX](https://github.com/open-telemetry/opentelemetry-collector-contrib/releases/download/v0.33.0/otelcontribcol_darwin_arm64)

```bash
./otelcontribcol_darwin_amd64 --config config.yaml
```

Run go webserver

```bash
go run *.go
```

[Check logz tracing](https://app.logz.io/#/dashboard/kibana)

