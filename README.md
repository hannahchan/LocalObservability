# LocalObservability

_LocalObservability_ is a local observability stack that based around an [OpenTelemetry Collector](https://opentelemetry.io/docs/collector) and is meant to help you develop and test observable applications on your local machine.

Spin up the _LocalObservability_ stack using [Docker Compose](https://docs.docker.com/compose) and then configure your application to send telemetry (logs, metrics or traces) to the OpenTelemetry Collector.

Then view your collected telemetry using Grafana at <http://localhost:3000>.

The stack uses [Loki](https://grafana.com/oss/loki/) for storing logs, [Mimir](https://grafana.com/oss/mimir/) for storing metrics and [Tempo](https://grafana.com/oss/tempo/) for storing traces.

You will probably need to configure the OpenTelemetry Collector to receive telemetry from your application.

## Quick Links

- [OpenTelemetry Collector - Docs](https://opentelemetry.io/docs/collector/)
- [OpenTelemetry Collector - GitHub](https://github.com/open-telemetry/opentelemetry-collector)
- [OpenTelemetry Collector Contrib - GitHub](https://github.com/open-telemetry/opentelemetry-collector-contrib)
- [OpenTelemetry Collector Releases - GitHub](https://github.com/open-telemetry/opentelemetry-collector-releases)
