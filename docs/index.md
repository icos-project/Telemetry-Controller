# Telemetry Controller

The Telemetry Controller is responsible for managing (collect, store, analyse, visualize) metrics and logs in an ICOS Controller.

It is constituted by multiple components:
- Thanos: for long-term storage of metrics
- OpenSearch: for long-term storage of logs
- AlertManager: for setting rules and receiving alerts on violations
- Grafana: for visualizing the data
- OpenTelemetry Collector: to receive data from ICOS Agents


## Installation

The Telemetry Controller is part of the ICOS Controller Suite and is installed and configured toghether with it.