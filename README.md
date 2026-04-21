# Solo.io (solo)
Solo.io provides enterprise infrastructure for cloud-native and AI-native environments, including API gateways, service mesh, and agentic AI infrastructure built on Envoy, Istio, and Kubernetes. Products include kgateway (API gateway), Istio-based service mesh, agentgateway (AI gateway), kagent (AI agents for Kubernetes), and agentregistry (MCP registries).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/solo/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - API Gateway, Service Mesh, Envoy, Istio, Kubernetes, AI Gateway, Agentic AI, MCP

## Timestamps

- **Created:** 2026-03-27
- **Modified:** 2026-04-21

## APIs

### Solo Enterprise for kgateway
Kubernetes-native ingress controller and next-generation API gateway built on Envoy Proxy, supporting the Kubernetes Gateway API for traffic management, security, and transformation.

**Human URL:** [https://docs.solo.io/kgateway/](https://docs.solo.io/kgateway/)

#### Tags:

 - API Gateway, Kubernetes, Envoy, Ingress Controller, Gateway API

#### Properties

- [Documentation](https://docs.solo.io/kgateway/)
- [Getting Started](https://docs.solo.io/kgateway/latest/quickstart/)
- [API Reference](https://docs.solo.io/kgateway/latest/reference/api/)
- [Authentication](https://docs.solo.io/kgateway/latest/security/)
- [Gloo Gateway Repository](https://github.com/solo-io/gloo)
- [Go Client](https://github.com/solo-io/kgateway-client)
- [AuthConfig CRD](crd/solo-gloo-enterprise-gloo-solo-io-v1-authconfig.yaml)
- [DirectResponse CRD](crd/solo-gloo-gateway-gloo-solo-io-directresponses.yaml)
- [GatewayParameters CRD](crd/solo-gloo-gateway-gloo-solo-io-gatewayparameters.yaml)
- [Gateway CRD](crd/solo-gloo-gateway-solo-io-v1-gateway.yaml)
- [HttpListenerOption CRD](crd/solo-gloo-gateway-solo-io-v1-httplisteneroption.yaml)
- [ListenerOption CRD](crd/solo-gloo-gateway-solo-io-v1-listeneroption.yaml)
- [MatchableHttpGateway CRD](crd/solo-gloo-gateway-solo-io-v1-matchablehttpgateway.yaml)
- [MatchableTcpGateway CRD](crd/solo-gloo-gateway-solo-io-v1-matchabletcpgateway.yaml)
- [RouteOption CRD](crd/solo-gloo-gateway-solo-io-v1-routeoption.yaml)
- [RouteTable CRD](crd/solo-gloo-gateway-solo-io-v1-routetable.yaml)
- [VirtualHostOption CRD](crd/solo-gloo-gateway-solo-io-v1-virtualhostoption.yaml)
- [VirtualService CRD](crd/solo-gloo-gateway-solo-io-v1-virtualservice.yaml)
- [Proxy CRD](crd/solo-gloo-gloo-solo-io-v1-proxy.yaml)
- [Settings CRD](crd/solo-gloo-gloo-solo-io-v1-settings.yaml)
- [Upstream CRD](crd/solo-gloo-gloo-solo-io-v1-upstream.yaml)
- [UpstreamGroup CRD](crd/solo-gloo-gloo-solo-io-v1-upstreamgroup.yaml)
- [RateLimitConfig CRD](crd/solo-gloo-ratelimit-config.yaml)
- [TCPRoute CRD](crd/solo-kgateway-tcproute-crd.yaml)

### Solo Enterprise for Istio
Enterprise service mesh solution built on Istio for connecting, securing, and observing microservices across multiple clusters and clouds, including Istio Ambient Mesh support.

**Human URL:** [https://docs.solo.io/gloo-mesh/latest/](https://docs.solo.io/gloo-mesh/latest/)

#### Tags:

 - Service Mesh, Istio, Multi-Cluster, Zero Trust, Ambient Mesh

#### Properties

- [Documentation](https://docs.solo.io/gloo-mesh/latest/)

### Solo Enterprise for agentgateway
AI connectivity and governance gateway for agents and LLMs, supporting traffic routing, load balancing, failover, guardrails, and MCP server connectivity across providers including OpenAI, Anthropic, Amazon Bedrock, Azure OpenAI, Gemini, Vertex AI, Ollama, and vLLM.

**Human URL:** [https://docs.solo.io/agentgateway](https://docs.solo.io/agentgateway)

#### Tags:

 - AI Gateway, LLM, MCP, Agentic AI, Guardrails

#### Properties

- [Documentation](https://docs.solo.io/agentgateway)
- [Getting Started](https://docs.solo.io/agentgateway/latest/quickstart/)
- [Authentication](https://docs.solo.io/agentgateway/latest/security/)
- [Agentgateway Repository](https://github.com/solo-io/agentgateway-new-ui)
- [AgentgatewayBackend CRD](crd/solo-agentgateway-agentgatewaybackends.yaml)
- [AgentgatewayParameters CRD](crd/solo-agentgateway-agentgatewayparameters.yaml)
- [AgentgatewayPolicy CRD](crd/solo-agentgateway-agentgatewaypolicies.yaml)

### Solo Enterprise for kagent
Enterprise AI agent framework for Kubernetes that enables building, managing, and scaling intelligent agents with observability, security, human-in-the-loop workflows, and support for multiple LLM providers.

**Human URL:** [https://docs.solo.io/kagent-enterprise/latest](https://docs.solo.io/kagent-enterprise/latest)

#### Tags:

 - AI Agents, Kubernetes, LLM, Agentic AI

#### Properties

- [Documentation](https://docs.solo.io/kagent-enterprise/latest)
- [Getting Started](https://docs.solo.io/kagent-enterprise/latest/quickstart/)

## Common Properties

- [Website](https://www.solo.io/)
- [Documentation](https://www.solo.io/docs)
- [Portal](https://www.solo.io/get-started)
- [Pricing](https://www.solo.io/pricing)
- [Blog](https://www.solo.io/blog)
- [GitHub Organization](https://github.com/solo-io)
- [Academy](https://www.solo.io/academy)
- [Training](https://www.solo.io/resources/lab)
- [Webinars](https://www.solo.io/resources/webinar)
- [Customers](https://www.solo.io/customers)
- [Security](https://www.solo.io/security)
- [Privacy Policy](https://www.solo.io/privacy-policy/)
- [Legal](https://legal.solo.io/)
- [Support](https://support.solo.io/)
- [LinkedIn](https://www.linkedin.com/company/solo.io)
- [X](https://twitter.com/soloio_inc)
- [YouTube](https://www.youtube.com/soloio)
- [Solo-Kit Operator Framework](https://github.com/solo-io/solo-kit)
- [Ingress to Gateway Migration Tool](https://github.com/solo-io/ingress2gateway)
- [Developer Portal Starter](https://github.com/solo-io/dev-portal-starter)
- [External Auth Plugins](https://github.com/solo-io/ext-auth-plugins)
- [MCP Flow Examples](https://github.com/solo-io/enterprise-mcp-flow)
- [Workshops](https://github.com/solo-io/workshops)

## Features

| Name | Description |
|------|-------------|
| Kubernetes Gateway API | Native support for the Kubernetes Gateway API standard for traffic management. |
| Envoy Proxy | Built on Envoy Proxy for high-performance traffic handling and extensibility. |
| Istio Ambient Mesh | Sidecar-less service mesh using Istio Ambient mode for simplified operations. |
| Multi-Cluster Networking | Connect and secure services across multiple Kubernetes clusters and clouds. |
| Zero Trust Security | End-to-end mTLS, JWT validation, OAuth, OPA, and external auth for zero-trust architectures. |
| AI Gateway | Route, load balance, and apply guardrails to LLM provider traffic. |
| MCP Server Connectivity | Connect AI agents to MCP servers and manage agent-to-agent communication. |
| Rate Limiting | Advanced rate limiting for API and AI traffic. |
| OpenTelemetry Observability | Built-in tracing, metrics, and access logging via OpenTelemetry. |
| Traffic Transformation | Request and response transformation, header manipulation, and content-based routing. |

## Use Cases

| Name | Description |
|------|-------------|
| API Gateway Modernization | Replace legacy API gateways with a Kubernetes-native, Envoy-based gateway. |
| Service Mesh Adoption | Adopt Istio service mesh for microservice security and observability. |
| Multi-Cloud Connectivity | Connect services across AWS, GCP, Azure, and on-premises environments. |
| AI Agent Infrastructure | Build, deploy, and manage AI agents securely in Kubernetes. |
| LLM Gateway | Centralize LLM provider access with routing, failover, and cost controls. |

## Integrations

| Name | Description |
|------|-------------|
| Envoy Proxy | Core proxy engine powering kgateway and agentgateway. |
| Istio | Service mesh foundation for multi-cluster networking and security. |
| Kubernetes | Native integration with Kubernetes for deployment and configuration. |
| OpenAI | LLM provider integration for AI gateway routing. |
| Anthropic | Claude LLM provider integration for AI gateway routing. |
| Amazon Bedrock | AWS Bedrock LLM provider integration. |
| Azure OpenAI | Azure-hosted OpenAI LLM provider integration. |
| Google Vertex AI | Google Cloud Vertex AI LLM provider integration. |
| OpenTelemetry | Observability integration for tracing, metrics, and logging. |
| ArgoCD | GitOps deployment support for Solo products. |

## Kubernetes CRDs

Kubernetes Custom Resource Definitions defining the declarative API surface.

| Kind | Group | Version | Scope | File |
|------|-------|---------|-------|------|
| AuthConfig | enterprise.gloo.solo.io | v1 | Namespaced | [solo-gloo-enterprise-gloo-solo-io-v1-authconfig.yaml](crd/solo-gloo-enterprise-gloo-solo-io-v1-authconfig.yaml) |
| DirectResponse | gateway.gloo.solo.io | v1alpha1 | Namespaced | [solo-gloo-gateway-gloo-solo-io-directresponses.yaml](crd/solo-gloo-gateway-gloo-solo-io-directresponses.yaml) |
| GatewayParameters | gateway.gloo.solo.io | v1alpha1 | Namespaced | [solo-gloo-gateway-gloo-solo-io-gatewayparameters.yaml](crd/solo-gloo-gateway-gloo-solo-io-gatewayparameters.yaml) |
| Gateway | gateway.solo.io | v1 | Namespaced | [solo-gloo-gateway-solo-io-v1-gateway.yaml](crd/solo-gloo-gateway-solo-io-v1-gateway.yaml) |
| HttpListenerOption | gateway.solo.io | v1 | Namespaced | [solo-gloo-gateway-solo-io-v1-httplisteneroption.yaml](crd/solo-gloo-gateway-solo-io-v1-httplisteneroption.yaml) |
| ListenerOption | gateway.solo.io | v1 | Namespaced | [solo-gloo-gateway-solo-io-v1-listeneroption.yaml](crd/solo-gloo-gateway-solo-io-v1-listeneroption.yaml) |
| MatchableHttpGateway | gateway.solo.io | v1 | Namespaced | [solo-gloo-gateway-solo-io-v1-matchablehttpgateway.yaml](crd/solo-gloo-gateway-solo-io-v1-matchablehttpgateway.yaml) |
| MatchableTcpGateway | gateway.solo.io | v1 | Namespaced | [solo-gloo-gateway-solo-io-v1-matchabletcpgateway.yaml](crd/solo-gloo-gateway-solo-io-v1-matchabletcpgateway.yaml) |
| RouteOption | gateway.solo.io | v1 | Namespaced | [solo-gloo-gateway-solo-io-v1-routeoption.yaml](crd/solo-gloo-gateway-solo-io-v1-routeoption.yaml) |
| RouteTable | gateway.solo.io | v1 | Namespaced | [solo-gloo-gateway-solo-io-v1-routetable.yaml](crd/solo-gloo-gateway-solo-io-v1-routetable.yaml) |
| VirtualHostOption | gateway.solo.io | v1 | Namespaced | [solo-gloo-gateway-solo-io-v1-virtualhostoption.yaml](crd/solo-gloo-gateway-solo-io-v1-virtualhostoption.yaml) |
| VirtualService | gateway.solo.io | v1 | Namespaced | [solo-gloo-gateway-solo-io-v1-virtualservice.yaml](crd/solo-gloo-gateway-solo-io-v1-virtualservice.yaml) |
| Proxy | gloo.solo.io | v1 | Namespaced | [solo-gloo-gloo-solo-io-v1-proxy.yaml](crd/solo-gloo-gloo-solo-io-v1-proxy.yaml) |
| Settings | gloo.solo.io | v1 | Namespaced | [solo-gloo-gloo-solo-io-v1-settings.yaml](crd/solo-gloo-gloo-solo-io-v1-settings.yaml) |
| Upstream | gloo.solo.io | v1 | Namespaced | [solo-gloo-gloo-solo-io-v1-upstream.yaml](crd/solo-gloo-gloo-solo-io-v1-upstream.yaml) |
| UpstreamGroup | gloo.solo.io | v1 | Namespaced | [solo-gloo-gloo-solo-io-v1-upstreamgroup.yaml](crd/solo-gloo-gloo-solo-io-v1-upstreamgroup.yaml) |
| RateLimitConfig | ratelimit.solo.io | v1alpha1 | Namespaced | [solo-gloo-ratelimit-config.yaml](crd/solo-gloo-ratelimit-config.yaml) |
| TCPRoute | gateway.networking.k8s.io | v1alpha2 | Namespaced | [solo-kgateway-tcproute-crd.yaml](crd/solo-kgateway-tcproute-crd.yaml) |
| AgentgatewayBackend | agentgateway.dev | v1alpha1 | Namespaced | [solo-agentgateway-agentgatewaybackends.yaml](crd/solo-agentgateway-agentgatewaybackends.yaml) |
| AgentgatewayParameters | agentgateway.dev | v1alpha1 | Namespaced | [solo-agentgateway-agentgatewayparameters.yaml](crd/solo-agentgateway-agentgatewayparameters.yaml) |
| AgentgatewayPolicy | agentgateway.dev | v1alpha1 | Namespaced | [solo-agentgateway-agentgatewaypolicies.yaml](crd/solo-agentgateway-agentgatewaypolicies.yaml) |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
