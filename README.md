# otel-collector-dist

**otel-collector-dist** provides my own cutsom build workflow for [OpenTelemetry Collector][] and custom container images.

## Distributions

### lambda_go image

[otel-collector-dist/lambda_go][] provides a base image that includes my own build OpenTelemetry Collector for [AWS Lambda][].

It is similar to [aws-otel-lambda][] but its OpenTelemetry Collector includes datadogexporter and the configuration that works well in the Lambda runtime.

[opentelemetry collector]: https://opentelemetry.io/docs/collector/
[otel-collector-dist/lambda_go]: https://github.com/aereal/otel-collector-dist/pkgs/container/otel-collector-dist%2Flambda_go
[AWS Lambda]: https://docs.aws.amazon.com/lambda/latest/dg/welcome.html
[aws-otel-lambda]: https://github.com/aws-observability/aws-otel-lambda
