# appdynamics-ot-collector
AppDynamics OpenTelemetry Collector

Collector contains 
-------------------
- Core v0.29.0
- Extensions
  - OAuth2 Auth extension
- Processors
  - Resource Detection 


Building Collector
------------------

- Download **OpenTelemetry Collector Builder** binary https://github.com/open-telemetry/opentelemetry-collector-builder/releases/tag/v0.29.0
- `opentelemetry-collector-builder --config collector.builder.yaml`


Adding New Components
---------------------
- Edit `collector.builder.yaml`
- Add entry into "replaces" directive with fork/branch if you are not using from main opentelemetry source 
