# newrelic-istio-adapter
This adapter is used to upload telemetry data which is collected by Istio Envoy proxy to NewRelic backend. It is different from compiled in adapters. You can run it as a separated process out of mixer process. The adapter communicates with Mixer, parse and send metric data to the real backend -- NewRelic.
