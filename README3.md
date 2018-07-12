# Apcera-Prometheus-Exporter

The exporter is a standalone server. The prometheus queries for the exporter for metrics. The Exporter queries the Apcera Metrics API and reutrns the metrics on /metrics endpoint.

## Build

To Build the Exporter Docker image, Run       :	./scripts/build_image.sh

## Requirements

pip3 install -r requirements.txt

## Run server
      

To Run a local instance of the exporter, Run  :	./scripts/start_dev_server.sh
and go to 0.0.0.0:8080/metrics

