# Telemetry Controller

The Telemetry Controller is responsible for managing (collect, store, analyse, visualize) metrics and logs in an ICOS Controller.

It is constituted by multiple components:
- Thanos: for long-term storage of metrics
- OpenSearch: for long-term storage of logs
- AlertManager: for setting rules and receiving alerts on violations
- Grafana: for visualizing the data
- OpenTelemetry Collector: to receive data from ICOS Agents

## Installation

The component is distributed as an Helm Chart. The source and the documentation for the chart is at `deploy/charts/telemetry-controller`

# Legal
The ICOS Telemetry Controller is released under the Apache 2.0 license.
Copyright © 2022-2024 Engineering Ingegneria Informatica S.p.A. All rights reserved.

🇪🇺 This work has received funding from the European Union's HORIZON research and innovation programme under grant agreement No. 101070177.
