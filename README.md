# Solo.io

Solo.io provides enterprise infrastructure for cloud-native and AI-native environments, including API gateways, service mesh, and agentic AI infrastructure built on Envoy, Istio, and Kubernetes. Products include kgateway (API gateway), Istio-based service mesh, agentgateway (AI gateway), kagent (AI agents for Kubernetes), and agentregistry (MCP registries).

**URL:** [https://raw.githubusercontent.com/api-evangelist/solo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/solo/refs/heads/main/apis.yml)

## Tags

AI Gateway, Agentic AI, API Gateway, Envoy, Istio, Kubernetes, MCP, Service Mesh

## APIs

### Solo Enterprise for kgateway

Kubernetes-native ingress controller and next-generation API gateway built on Envoy Proxy, supporting the Kubernetes Gateway API for traffic management, security, and transformation.

- **Documentation:** [https://docs.solo.io/kgateway/](https://docs.solo.io/kgateway/)
- **CRDs:** AuthConfig, DirectResponse, GatewayParameters, Gateway, HttpListenerOption, ListenerOption, MatchableHttpGateway, MatchableTcpGateway, RouteOption, RouteTable, VirtualHostOption, VirtualService, Proxy, Settings, Upstream, UpstreamGroup, RateLimitConfig, TCPRoute

### Solo Enterprise for Istio

Enterprise service mesh built on Istio with Ambient Mesh support for multi-cluster service connectivity.

- **Documentation:** [https://docs.solo.io/gloo-mesh/latest/](https://docs.solo.io/gloo-mesh/latest/)

### Solo Enterprise for agentgateway

AI connectivity and governance gateway for agents and LLMs supporting MCP, OpenAI, Anthropic, Bedrock, Vertex AI, Ollama, and vLLM.

- **Documentation:** [https://docs.solo.io/agentgateway](https://docs.solo.io/agentgateway)
- **CRDs:** AgentgatewayBackend, AgentgatewayParameters, AgentgatewayPolicy

### Solo Enterprise for kagent

Enterprise AI agent framework for Kubernetes with observability, security, and multi-LLM support.

- **Documentation:** [https://docs.solo.io/kagent-enterprise/latest](https://docs.solo.io/kagent-enterprise/latest)

## Artifacts

### JSON Schemas

- [json-schema/solo-agentgateway-backend-schema.json](json-schema/solo-agentgateway-backend-schema.json) — AgentgatewayBackend resource
- [json-schema/solo-gloo-upstream-schema.json](json-schema/solo-gloo-upstream-schema.json) — Gloo Upstream resource
- [json-schema/solo-gloo-virtual-service-schema.json](json-schema/solo-gloo-virtual-service-schema.json) — Gloo VirtualService resource

### JSON Structures

- [json-structure/solo-kgateway-structure.json](json-structure/solo-kgateway-structure.json) — kgateway CRD structure documentation
- [json-structure/solo-agentgateway-structure.json](json-structure/solo-agentgateway-structure.json) — agentgateway CRD structure documentation

### JSON-LD

- [json-ld/solo-context.jsonld](json-ld/solo-context.jsonld) — Linked data context for Solo.io resources

### Examples

- [examples/solo-agentgateway-backend-example.json](examples/solo-agentgateway-backend-example.json) — AgentgatewayBackend for OpenAI
- [examples/solo-gloo-upstream-kube-example.json](examples/solo-gloo-upstream-kube-example.json) — Gloo Kubernetes Upstream

### Vocabulary

- [vocabulary/solo-vocabulary.yml](vocabulary/solo-vocabulary.yml) — Solo.io enterprise platform vocabulary

## Kubernetes CRDs

| Kind | Group | Version | File |
|------|-------|---------|------|
| AuthConfig | enterprise.gloo.solo.io | v1 | [crd/solo-gloo-enterprise-gloo-solo-io-v1-authconfig.yaml](crd/solo-gloo-enterprise-gloo-solo-io-v1-authconfig.yaml) |
| Gateway | gateway.solo.io | v1 | [crd/solo-gloo-gateway-solo-io-v1-gateway.yaml](crd/solo-gloo-gateway-solo-io-v1-gateway.yaml) |
| VirtualService | gateway.solo.io | v1 | [crd/solo-gloo-gateway-solo-io-v1-virtualservice.yaml](crd/solo-gloo-gateway-solo-io-v1-virtualservice.yaml) |
| RouteTable | gateway.solo.io | v1 | [crd/solo-gloo-gateway-solo-io-v1-routetable.yaml](crd/solo-gloo-gateway-solo-io-v1-routetable.yaml) |
| Upstream | gloo.solo.io | v1 | [crd/solo-gloo-gloo-solo-io-v1-upstream.yaml](crd/solo-gloo-gloo-solo-io-v1-upstream.yaml) |
| RateLimitConfig | ratelimit.solo.io | v1alpha1 | [crd/solo-gloo-ratelimit-config.yaml](crd/solo-gloo-ratelimit-config.yaml) |
| AgentgatewayBackend | agentgateway.dev | v1alpha1 | [crd/solo-agentgateway-agentgatewaybackends.yaml](crd/solo-agentgateway-agentgatewaybackends.yaml) |
| AgentgatewayPolicy | agentgateway.dev | v1alpha1 | [crd/solo-agentgateway-agentgatewaypolicies.yaml](crd/solo-agentgateway-agentgatewaypolicies.yaml) |

## Common Properties

- [Website](https://www.solo.io/)
- [Documentation](https://www.solo.io/docs)
- [Blog](https://www.solo.io/blog)
- [Pricing](https://www.solo.io/pricing)
- [GitHub Organization](https://github.com/solo-io)
- [Academy](https://www.solo.io/academy)
- [Support](https://support.solo.io/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
