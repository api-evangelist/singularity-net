# SingularityNET (singularity-net)

SingularityNET is a decentralized AI services marketplace built on blockchain. Developers can publish AI services to the network and consumers can access them using the ASI (FET) token. The platform uses a daemon (snetd) that exposes AI applications as gRPC APIs accessible through the SingularityNET Network, with a REST API for marketplace interaction and service discovery.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/singularity-net/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/singularity-net/refs/heads/main/apis.yml)

## Tags

- Artificial Intelligence
- Blockchain
- Decentralized AI
- AI Marketplace
- Web3

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### SingularityNET Daemon API

The SingularityNET Daemon (snetd) exposes an AI service as an API accessible through the SingularityNET Network. The daemon handles blockchain interaction for payment authorization using Multi-Party Escrow (MPE) contracts and routes API calls to the underlying AI service via gRPC.

- **Human URL:** [https://dev.singularitynet.io/docs/products/DecentralizedAIPlatform/Daemon/daemon-api/](https://dev.singularitynet.io/docs/products/DecentralizedAIPlatform/Daemon/daemon-api/)
- **Base URL:** `https://services.singularitynet.io`

#### Tags

- AI Services
- gRPC
- Blockchain
- Payment Channels
- Daemon

#### Properties

- [Documentation](https://dev.singularitynet.io/docs/products/DecentralizedAIPlatform/Daemon/daemon-api/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/singularity-net/refs/heads/main/openapi/singularitynet-marketplace-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [GitHub Organization](https://github.com/singnet)
- [Daemon Git Hub](https://github.com/singnet/snet-daemon)
- [Python S D K](https://github.com/singnet/snet-sdk-python)
- [Authentication](https://dev.singularitynet.io/docs/products/DecentralizedAIPlatform/SDK/sdk-concept/)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/singularity-net/refs/heads/main/rules/singularitynet-rules.yml)
- [Postman Collection](collections/singularitynet-marketplace.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/singularitynet-marketplace.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SingularityNET Marketplace API

The SingularityNET AI Marketplace REST API provides service discovery, organization management, and metadata access for the decentralized AI network. Allows consumers to browse available AI services, retrieve service metadata, and access pricing information.

- **Human URL:** [https://dev.singularitynet.io/docs/products/AIMarketplace/](https://dev.singularitynet.io/docs/products/AIMarketplace/)
- **Base URL:** `https://marketplace.singularitynet.io`

#### Tags

- AI Marketplace
- Service Discovery
- Organizations
- Metadata

#### Properties

- [Documentation](https://dev.singularitynet.io/docs/products/AIMarketplace/)
- [GitHub Organization](https://github.com/singnet)
- [Postman Collection](collections/singularitynet-marketplace.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/singularitynet-marketplace.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/singularitynet)
- [GitHub Organization](https://github.com/singnet)
- [Developer Portal](https://dev.singularitynet.io)
- [Documentation](https://dev.singularitynet.io/docs/products/DecentralizedAIPlatform/)
- [A I Marketplace](https://marketplace.singularitynet.io)
- [Whitepaper](https://public.singularitynet.io/whitepaper.pdf)
- [Python S D K](https://github.com/singnet/snet-sdk-python)
- [Daemon Git Hub](https://github.com/singnet/snet-daemon)
- [Terms of Service](https://singularitynet.io/terms-of-service)
- [Privacy Policy](https://singularitynet.io/privacy-policy)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
