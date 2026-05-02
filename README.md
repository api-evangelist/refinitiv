# Refinitiv

Refinitiv, an LSEG (London Stock Exchange Group) business, provides financial market data, infrastructure, and analytics to businesses and financial professionals worldwide. The Refinitiv Data Platform offers REST APIs for historical pricing, real-time data, ESG scores, news, compliance screening, and symbology.

**Human URL:** [https://developers.lseg.com](https://developers.lseg.com)

**Developer Portal:** [https://developers.lseg.com/en/api-catalog](https://developers.lseg.com/en/api-catalog)

## Tags

- Financial Data
- Market Data
- ESG
- News
- Compliance
- Screening
- Analytics

## APIs

### Refinitiv Data Platform (RDP) API
Cloud-enabled REST API for pricing, ESG, news, quantitative analytics, symbology, and search.

- [OpenAPI](openapi/refinitiv-data-platform-openapi.yml)
- [Documentation](https://developers.lseg.com/en/api-catalog/refinitiv-data-platform/refinitiv-data-platform-apis/documentation)

### DataScope Select REST API
Bulk extraction platform for prices, corporate actions, reference data, and historical data.

- [OpenAPI](openapi/refinitiv-datascope-select-openapi.yml)
- [Documentation](https://developers.lseg.com/en/api-catalog/datascope-select/datascope-select-rest-api/documentation)

### PermID Entity Search API
Entity search, intelligent tagging, and record matching for organizations and instruments.

- [OpenAPI](openapi/refinitiv-permid-entity-search-openapi.yml)
- [Documentation](https://developers.lseg.com/en/api-catalog/open-perm-id/permid-entity-search/documentation)

### World-Check One API
Entity screening against the World-Check risk intelligence database for KYC and AML.

- [OpenAPI](openapi/refinitiv-world-check-one-openapi.yml)
- [Documentation](https://developers.lseg.com/en/api-catalog/customer-and-third-party-screening/world-check-one-api/documentation)

### LSEG Real-Time WebSocket API
WebSocket API for real-time streaming pricing and news data.

- [AsyncAPI](asyncapi/refinitiv-real-time-websocket-asyncapi.yml)
- [Documentation](https://developers.lseg.com/en/api-catalog/real-time-opnsrc/websocket-api/documentation)

## Artifacts

### OpenAPI Specifications

| Specification | Description |
|---------------|-------------|
| [Data Platform API](openapi/refinitiv-data-platform-openapi.yml) | Pricing, ESG, news, symbology, search |
| [DataScope Select API](openapi/refinitiv-datascope-select-openapi.yml) | Bulk data extraction |
| [PermID Entity Search API](openapi/refinitiv-permid-entity-search-openapi.yml) | Entity search and tagging |
| [Qual-ID API](openapi/refinitiv-qual-id-openapi.yml) | Identity verification |
| [World-Check One API](openapi/refinitiv-world-check-one-openapi.yml) | Compliance screening |

### AsyncAPI Specifications

| Specification | Description |
|---------------|-------------|
| [Real-Time WebSocket API](asyncapi/refinitiv-real-time-websocket-asyncapi.yml) | Streaming market data |

### Rules

| Ruleset | Description |
|---------|-------------|
| [Refinitiv Rules](rules/refinitiv-rules.yml) | Spectral ruleset for Refinitiv API conventions |

### Capabilities

| Capability | Description |
|------------|-------------|
| [Financial Market Data](capabilities/financial-market-data.yaml) | Pricing, ESG, news, symbology via Data Platform |
| [Compliance Screening](capabilities/compliance-screening.yaml) | World-Check screening and PermID entity research |

**Shared Definitions:**
- [Data Platform](capabilities/shared/data-platform.yaml)
- [World-Check One](capabilities/shared/world-check-one.yaml)
- [PermID](capabilities/shared/permid.yaml)

### JSON Schema

| Schema | Description |
|--------|-------------|
| [Instrument Schema](json-schema/refinitiv-instrument-schema.json) | Financial instrument with identifiers and pricing |
| [ESG Score Schema](json-schema/refinitiv-esg-score-schema.json) | ESG pillar and combined scores |
| [News Article Schema](json-schema/refinitiv-news-article-schema.json) | News headline and story structure |
| [Screening Case Schema](json-schema/refinitiv-screening-case-schema.json) | World-Check screening case |

### JSON Structure

| Structure | Description |
|-----------|-------------|
| [Data Platform Structure](json-structure/refinitiv-data-platform-structure.json) | Overview of all API endpoints and domains |

### JSON-LD

| Context | Description |
|---------|-------------|
| [Refinitiv Context](json-ld/refinitiv-context.jsonld) | JSON-LD context for financial data semantics |

### Examples

| Example | Description |
|---------|-------------|
| [Get Pricing Snapshots](examples/refinitiv-get-pricing-snapshots-example.json) | Real-time pricing snapshot for multiple instruments |
| [Screen Entity](examples/refinitiv-world-check-screen-entity-example.json) | World-Check entity screening request/response |

### Vocabulary

| Vocabulary | Description |
|------------|-------------|
| [Refinitiv Vocabulary](vocabulary/refinitiv-vocabulary.yml) | Domain vocabulary for Refinitiv APIs and financial data |

## Common Properties

- [Developer Portal](https://developers.lseg.com)
- [Community](https://community.developers.refinitiv.com/)
- [GitHub Organization](https://github.com/Refinitiv-API-Samples)
- [Terms of Service](https://developers.lseg.com/en/terms-and-conditions)
- [Privacy Policy](https://www.lseg.com/en/policies/privacy-statement)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
