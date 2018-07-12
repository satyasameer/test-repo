# Prometheus

Define alert rules in first_rules.yml

To configure the endpoints of the Exporter and the Alertmanager, change the url in prometheus.yml. You can also add multiple targets to monitor.

## Build

To build the Promethus Docker image run:        Docker build -t prometheus .
