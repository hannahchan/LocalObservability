# LocalObservability

_LocalObservability_ is a local observability stack that based around an [OpenTelemetry Collector](https://opentelemetry.io/docs/collector) and is meant to help you develop and test observable applications on your local machine.

Spin up the _LocalObservability_ stack using [Docker Compose](https://docs.docker.com/compose) and then configure your application to send telemetry (logs, metrics or traces) to the OpenTelemetry Collector.

Then view your collected telemetry using Grafana at <http://localhost:3000>.

The stack is based on [grafana/otel-lgtm](https://grafana.com/blog/2024/03/13/an-opentelemetry-backend-in-a-docker-image-introducing-grafana/otel-lgtm/) and uses [Loki](https://grafana.com/oss/loki/) for storing logs, [Prometheus](https://prometheus.io/) for storing metrics and [Tempo](https://grafana.com/oss/tempo/) for storing traces.

The stack uses a separate OpenTelemetry Collector instance which you can configure to receive telemetry from your application.

## Quick Links

- [OpenTelemetry Collector - Docs](https://opentelemetry.io/docs/collector/)
- [OpenTelemetry Collector - GitHub](https://github.com/open-telemetry/opentelemetry-collector)
- [OpenTelemetry Collector Contrib - GitHub](https://github.com/open-telemetry/opentelemetry-collector-contrib)
- [OpenTelemetry Collector Releases - GitHub](https://github.com/open-telemetry/opentelemetry-collector-releases)
