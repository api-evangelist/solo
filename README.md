# Solo.io

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
