# Apcera-Prometheus-Exporter

The exporter is a standalone server. The prometheus queries for the exporter for metrics. The Exporter queries the Apcera Metrics API and reutrns the metrics on /metrics endpoint.

## Build

To Build the Exporter Docker image, Run       :	./scripts/build_image.sh

## Requirements

pip3 install -r requirements.txt

## Run

To Run a local instance of the exporter, Run  :	./scripts/start_dev_server.sh
and go to 0.0.0.0:8080/metrics




### List of all the ENV variables

1. API_ENDPOINT

2. LDAP_HOST

3. DEBUG

4. PORT 

5. ACCESS_TOKEN

6. QUERY_HEALTH

7. USER_CRED
