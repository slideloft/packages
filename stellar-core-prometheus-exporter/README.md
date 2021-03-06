# Overview

The Stellar Core Prometheus Exporter reads metrics exposed by the
stellar-core daemon and exposes them in prometheus format.

# Configuration

Optional config can be provided using CLI arguments, /etc/default/stellar-core-prometheus-exporter
or environment variables.

For list of supported options run the exporter with --help switch

# Grafana dashboard

Grafana can be used to visualise data. Example dashboards are shipped with this
package. Latest versions is also available on [grafana.com](https://grafana.com/orgs/stellar/dashboards)

Please refer to the [documentation](https://github.com/stellar/packages/blob/master/docs/monitoring.md)
for details.

# Docker image

Included Dockerfile uses apt package to deploy the exporter. Example build command:
```
docker build -t stellar-core-prometheus-exporter:latest .
```
