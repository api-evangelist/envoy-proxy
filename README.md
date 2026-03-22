# Envoy Proxy (envoy-proxy)
Envoy Proxy is an open-source edge and service proxy that is designed for cloud-native applications. It acts as a gateway for all incoming and outgoing traffic within a microservices architecture, providing functionalities such as load balancing, service discovery, encryption, authentication, and observability. Envoy Proxy is known for its high performance and low latency, making it a popular choice for companies seeking to optimize their network traffic and improve overall system efficiency. By handling the complexities of network communication, Envoy Proxy allows developers to focus on building and scaling their applications without having to worry about the intricacies of managing network traffic.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/envoy-proxy/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Proxies, Gateways

## Timestamps

- **Created:** 2026-01-02 
- **Modified:** 2026-03-18 

## APIs

### Envoy Proxy Admin API
The Envoy Proxy Administration Interface provides a local HTTP-based management API for querying and modifying various aspects of the Envoy server at runtime. It serves as a critical operational tool for monitoring, debugging, and managing Envoy proxy instances including statistics, clusters, listeners, certificates, runtime settings, logging, and health checks.

**Human URL:** [https://www.envoyproxy.io/docs/envoy/latest/operations/admin](https://www.envoyproxy.io/docs/envoy/latest/operations/admin)


#### Tags:

 - Proxies, Gateways, Service Mesh

#### Properties

- [OpenAPI](openapi/envoy-proxy-admin-api-openapi.yml)
- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/operations/admin)
- [GitHubRepository](https://github.com/envoyproxy/envoy)
- [Change Log](https://github.com/envoyproxy/envoy/releases)

### Envoy Proxy xDS Discovery API
The Envoy xDS (x Discovery Service) REST API provides endpoints for dynamically discovering and configuring Envoy proxy resources including clusters (CDS), listeners (LDS), routes (RDS), endpoints (EDS), secrets (SDS), and runtime configuration (RTDS). The xDS protocol is the foundation of Envoy's dynamic configuration model, enabling control planes to push configuration updates to Envoy instances without requiring restarts.

**Human URL:** [https://www.envoyproxy.io/docs/envoy/latest/api-docs/xds_protocol](https://www.envoyproxy.io/docs/envoy/latest/api-docs/xds_protocol)


#### Tags:

 - Proxies, Gateways, Service Mesh, Discovery

#### Properties

- [OpenAPI](openapi/envoy-proxy-xds-discovery-api-openapi.yml)
- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/api-docs/xds_protocol)
- [Reference](https://www.envoyproxy.io/docs/envoy/latest/configuration/overview/xds_api)
- [GitHubRepository](https://github.com/envoyproxy/envoy)

### Envoy Proxy Rate Limit Service API
The Envoy Rate Limit Service (RLS) is a gRPC-based API that allows Envoy to delegate rate limiting decisions to an external service. When a request matches a configured rate limit rule, Envoy calls the RLS to check whether the request should be allowed or throttled based on descriptors extracted from the request context.

**Human URL:** [https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/rate_limit_filter](https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/rate_limit_filter)


#### Tags:

 - Rate Limiting, Proxies, Service Mesh, gRPC

#### Properties

- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/rate_limit_filter)
- [Reference](https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/ratelimit/v3/rls.proto)
- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/intro/arch_overview/other_features/global_rate_limiting)
- [GitHubRepository](https://github.com/envoyproxy/envoy)

### Envoy Proxy Health Discovery Service API
The Envoy Health Discovery Service (HDS) is a gRPC-based API that enables a management server to instruct Envoy to perform health checks on behalf of the control plane and report results back. This allows centralized health state management across a fleet of Envoy instances without requiring the control plane to perform health checks directly.

**Human URL:** [https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/health/v3/hds.proto](https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/health/v3/hds.proto)


#### Tags:

 - Health, Discovery, Proxies, gRPC

#### Properties

- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/health/v3/hds.proto)
- [Reference](https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/service)
- [GitHubRepository](https://github.com/envoyproxy/envoy)

### Envoy Proxy gRPC Access Log Service API
The Envoy gRPC Access Log Service (ALS) API provides a streaming gRPC interface for receiving access log entries from Envoy instances in real time. It enables centralized log aggregation by allowing Envoy to stream HTTP and TCP access logs to a remote endpoint rather than writing them locally.

**Human URL:** [https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/accesslog/v3/als.proto](https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/accesslog/v3/als.proto)


#### Tags:

 - Access Logs, Observability, Proxies, gRPC

#### Properties

- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/accesslog/v3/als.proto)
- [Reference](https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/service)
- [GitHubRepository](https://github.com/envoyproxy/envoy)

### Envoy Proxy External Processing API
The Envoy External Processing API is a gRPC-based service that enables an external server to inspect and modify HTTP requests and responses as they pass through Envoy. This extensibility mechanism supports use cases such as custom authentication, header manipulation, body transformation, and dynamic routing decisions without requiring Envoy filter plugins.

**Human URL:** [https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/ext_proc_filter](https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/ext_proc_filter)


#### Tags:

 - Request Processing, Extensibility, Proxies, gRPC

#### Properties

- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/ext_proc_filter)
- [Reference](https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/ext_proc/v3/external_processor.proto)
- [GitHubRepository](https://github.com/envoyproxy/envoy)

### Envoy Proxy External Authorization API
The Envoy External Authorization API provides a gRPC or HTTP interface for delegating authorization decisions to an external service. When a request arrives, Envoy calls the ext_authz service, which can approve, deny, or modify the request before it is forwarded to the upstream. This enables policy-based access control enforced at the proxy layer.

**Human URL:** [https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/ext_authz_filter](https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/ext_authz_filter)


#### Tags:

 - Authorization, Security, Proxies, gRPC

#### Properties

- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/ext_authz_filter)
- [Reference](https://www.envoyproxy.io/docs/envoy/latest/api-v3/extensions/filters/http/ext_authz/v3/ext_authz.proto)
- [GitHubRepository](https://github.com/envoyproxy/envoy)

### Envoy Proxy Metrics Service API
The Envoy Metrics Service API is a gRPC-based interface for streaming Envoy's statistics and metrics to a remote metrics collection service. It allows operators to centralize telemetry data from multiple Envoy instances, supporting integration with observability platforms for monitoring proxy performance and traffic patterns.

**Human URL:** [https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/metrics/v3/metrics_service.proto](https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/metrics/v3/metrics_service.proto)


#### Tags:

 - Metrics, Observability, Proxies, gRPC

#### Properties

- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/metrics/v3/metrics_service.proto)
- [Reference](https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/service)
- [GitHubRepository](https://github.com/envoyproxy/envoy)

### Envoy Proxy Tap Service API
The Envoy Tap Service API provides a mechanism for intercepting and recording HTTP and TCP traffic passing through Envoy. The tap filter matches requests and responses based on configurable conditions and streams the captured data to a sink such as a gRPC service or local file, enabling debugging, auditing, and traffic analysis use cases.

**Human URL:** [https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/tap_filter](https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/tap_filter)


#### Tags:

 - Traffic Capture, Debugging, Proxies, gRPC

#### Properties

- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/configuration/http/http_filters/tap_filter)
- [Reference](https://www.envoyproxy.io/docs/envoy/latest/api-v3/service/tap/v3/tap.proto)
- [GitHubRepository](https://github.com/envoyproxy/envoy)

## Common Properties

- [Website](https://www.envoyproxy.io/)
- [Documentation](https://www.envoyproxy.io/docs/envoy/latest/)
- [Getting Started](https://www.envoyproxy.io/docs/envoy/latest/start/start)
- [Blog](https://blog.envoyproxy.io/)
- [Change Log](https://github.com/envoyproxy/envoy/releases)
- [GitHub Organization](https://github.com/envoyproxy)
- [GitHubRepository](https://github.com/envoyproxy/envoy)
- [Community](https://www.envoyproxy.io/community)
- [Security](https://github.com/envoyproxy/envoy/blob/main/SECURITY.md)
- [JSON-LD](json-ld/envoy-proxy-context.jsonld)
- [JSONSchema](json-schema/envoy-proxy-cluster.json)
- [JSONSchema](json-schema/envoy-proxy-listener.json)
- [JSONSchema](json-schema/envoy-proxy-route.json)
- [JSONSchema](json-schema/envoy-proxy-endpoint.json)
- [Issue Tracker](https://github.com/envoyproxy/envoy/issues)
- [Community](https://envoyslack.cncf.io/)
- [Community](https://www.cncf.io/projects/envoy/)
- [Reference](https://www.envoyproxy.io/docs/envoy/latest/api-v3/api)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
