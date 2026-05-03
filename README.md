# SingularityNET

SingularityNET is a decentralized AI services marketplace built on blockchain. Developers can publish AI services to the network and consumers can access them using the ASI (FET) token. The platform uses a daemon (snetd) that exposes AI applications as gRPC APIs accessible through the SingularityNET Network.

- **Website:** https://singularitynet.io
- **Developer Portal:** https://dev.singularitynet.io
- **AI Marketplace:** https://marketplace.singularitynet.io
- **Whitepaper:** https://public.singularitynet.io/whitepaper.pdf
- **GitHub:** https://github.com/singnet
- **Daemon (snetd):** https://github.com/singnet/snet-daemon
- **Python SDK:** https://github.com/singnet/snet-sdk-python

## Architecture

SingularityNET uses a layered architecture:
1. **Blockchain (Ethereum):** Registry smart contract stores organization/service metadata URIs; MPE contract manages payment channels
2. **IPFS:** Distributed storage for service metadata and gRPC proto specifications
3. **Daemon (snetd):** Wraps AI services, handles auth/payment, proxies gRPC calls
4. **Marketplace REST API:** Service discovery and metadata access (no auth required for read operations)

## APIs

| Name | Base URL |
|---|---|
| Marketplace API | https://marketplace-mt-v2.singularitynet.io |
| Daemon gRPC | Per-service endpoint (retrieved from service groups) |

## OpenAPI Specs

| Name | Description |
|---|---|
| [Marketplace API](openapi/singularitynet-marketplace-openapi.yml) | REST API for service discovery, organizations, and payment channels |

## Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [singularitynet-marketplace](capabilities/shared/singularitynet-marketplace.yaml) | SingularityNET Marketplace REST API consumed definition |

### Workflow Capabilities

| Capability | Description |
|---|---|
| [AI Service Discovery](capabilities/ai-service-discovery.yaml) | Browse organizations, discover AI services, manage payment channels |

## Rules

| Name | Description |
|---|---|
| [SingularityNET Spectral Rules](rules/singularitynet-rules.yml) | Spectral ruleset enforcing SingularityNET API conventions |

## JSON Schema

| Name | Description |
|---|---|
| [Service Schema](json-schema/singularitynet-service-schema.json) | Schema for SingularityNET AI Service resource |

## JSON Structure

| Name | Description |
|---|---|
| [Service Structure](json-structure/singularitynet-service-structure.json) | Structural documentation for Organization, Service, ServiceGroup, PaymentChannel |

## JSON-LD

| Name | Description |
|---|---|
| [SingularityNET Context](json-ld/singularitynet-context.jsonld) | JSON-LD context mapping SingularityNET terms to schema.org |

## Examples

| Name | Description |
|---|---|
| [List Services](examples/singularitynet-list-services-example.json) | Example: searching AI services on the marketplace |

## Vocabulary

| Name | Description |
|---|---|
| [SingularityNET Vocabulary](vocabulary/singularitynet-vocabulary.yml) | Domain terms for the decentralized AI marketplace |

## Maintainers

**API Evangelist**
- URL: https://apievangelist.com
- Email: info@apievangelist.com
