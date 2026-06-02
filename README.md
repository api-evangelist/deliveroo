# Deliveroo (deliveroo)

A British online food delivery company operating across the United Kingdom, Europe, Asia, and the Middle East. Deliveroo's Developer Portal exposes three API suites — Partner Platform, Retail Platform, and Signature — that restaurants, grocers, and merchants use to integrate menus, orders, sites, and on-demand courier delivery.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/deliveroo/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=deliveroo-api-evangelist&utm_content=repo)

## Tags:

 - Food Delivery, Grocery, Marketplace, Logistics, Restaurants

## Timestamps

- **Created:** 2026-05-05
- **Modified:** 2026-06-02

## APIs

### Deliveroo Order API
Manages restaurant orders and rider lifecycle events in real time, delivered via webhooks. Part of the Partner Platform Suite.

**Human URL:** [https://api-docs.deliveroo.com/v2.0/docs](https://api-docs.deliveroo.com/v2.0/docs)

**Base URL:** https://api.developers.deliveroo.com

#### Tags:

 - Orders, Webhooks, Restaurants, Real-Time, Riders

#### Properties

- [Documentation](https://api-docs.deliveroo.com/v2.0/docs)
- [Webhooks](https://api-docs.deliveroo.com/v2.0/docs)
- [OpenAPI](openapi/deliveroo-order-api-openapi.yml)
- [AsyncAPI](asyncapi/deliveroo-webhooks-asyncapi.yml)
- [NaftikoCapability](capabilities/order-api-orders.yaml)
- [NaftikoCapability](capabilities/order-api-sync-status.yaml)

### Deliveroo Menu API
Publishes and maintains restaurant menus including stock levels, prices, POS identifiers, and allergen data.

**Human URL:** [https://api-docs.deliveroo.com/v2.0/docs](https://api-docs.deliveroo.com/v2.0/docs)

**Base URL:** https://api.developers.deliveroo.com

#### Tags:

 - Menus, Pricing, Stock, Allergens, POS, Restaurants

#### Properties

- [Documentation](https://api-docs.deliveroo.com/v2.0/docs)
- [OpenAPI](openapi/deliveroo-menu-api-openapi.yml)
- [NaftikoCapability](capabilities/menu-api-menus.yaml)

### Deliveroo Site API
Controls a merchant site's open/close status, operating hours, and workload mode. Shared by Partner Platform and Signature suites.

**Human URL:** [https://api-docs.deliveroo.com/v2.0/docs](https://api-docs.deliveroo.com/v2.0/docs)

**Base URL:** https://api.developers.deliveroo.com

#### Tags:

 - Sites, Restaurants, Hours, Status, Operations

#### Properties

- [Documentation](https://api-docs.deliveroo.com/v2.0/docs)
- [OpenAPI](openapi/deliveroo-site-api-openapi.yml)
- [NaftikoCapability](capabilities/site-api-opening-hours.yaml)

### Deliveroo Catalogue API
Retail Platform Suite API for managing master grocery catalogues of up to 30,000 items per merchant.

**Human URL:** [https://api-docs.deliveroo.com/v2.0/docs](https://api-docs.deliveroo.com/v2.0/docs)

**Base URL:** https://api.developers.deliveroo.com

#### Tags:

 - Catalogue, Grocery, Retail, Products, Inventory

#### Properties

- [Documentation](https://api-docs.deliveroo.com/v2.0/docs)
- [OpenAPI](openapi/deliveroo-catalogue-api-openapi.yml)
- [NaftikoCapability](capabilities/catalogue-api-catalogue.yaml)
- [NaftikoCapability](capabilities/catalogue-api-pricing.yaml)

### Deliveroo Picking API
Retail Platform Suite picking flow that lets grocery operators process incoming orders, remove unavailable items, propose substitutions, and accept or reject orders.

**Human URL:** [https://api-docs.deliveroo.com/v2.0/docs](https://api-docs.deliveroo.com/v2.0/docs)

**Base URL:** https://api.developers.deliveroo.com

#### Tags:

 - Picking, Grocery, Retail, Order Fulfillment, Substitutions

#### Properties

- [Documentation](https://api-docs.deliveroo.com/v2.0/docs)
- [OpenAPI](openapi/deliveroo-picking-api-openapi.yml)
- [NaftikoCapability](capabilities/picking-api-picking.yaml)

### Deliveroo Signature API
Lets merchants request on-demand delivery by Deliveroo couriers for orders originating in their own apps, websites, or channels.

**Human URL:** [https://api-docs.deliveroo.com/v2.0/docs](https://api-docs.deliveroo.com/v2.0/docs)

**Base URL:** https://api.developers.deliveroo.com

#### Tags:

 - On-Demand Delivery, Couriers, Logistics, Merchant Integration, Custom Apps

#### Properties

- [Documentation](https://api-docs.deliveroo.com/v2.0/docs)
- [OpenAPI](openapi/deliveroo-signature-api-openapi.yml)
- [NaftikoCapability](capabilities/signature-api-quotes.yaml)
- [NaftikoCapability](capabilities/signature-api-orders.yaml)
- [NaftikoCapability](capabilities/signature-api-deliveries.yaml)

## Common Properties

- [GitHubOrganization](https://github.com/deliveroo)
- [LinkedIn](https://www.linkedin.com/company/deliveroo)
- [Website](https://deliveroo.co.uk/)
- [DeveloperPortal](https://developers.deliveroo.com/)
- [Documentation](https://api-docs.deliveroo.com/v2.0/docs)
- [SignupURL](https://developers.deliveroo.com/)
- [Authentication](https://api-docs.deliveroo.com/v2.0/docs)
- [PrivacyPolicy](https://deliveroo.co.uk/privacy)
- [TermsOfService](https://deliveroo.co.uk/legal)
- [Support](https://deliveroo.co.uk/help)
- [Blog](https://deliveroo.co.uk/blog)
- [Spectral](rules/deliveroo-spectral-rules.yml)
- [Vocabulary](vocabulary/deliveroo-vocabulary.yml)
- [Plans](plans/deliveroo-plans-pricing.yml)
- [RateLimits](rate-limits/deliveroo-rate-limits.yml)
- [FinOps](finops/deliveroo-finops.yml)

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Deliveroo Order API](openapi/deliveroo-order-api-openapi.yml)
- [Deliveroo Menu API](openapi/deliveroo-menu-api-openapi.yml)
- [Deliveroo Site API](openapi/deliveroo-site-api-openapi.yml)
- [Deliveroo Catalogue API](openapi/deliveroo-catalogue-api-openapi.yml)
- [Deliveroo Picking API](openapi/deliveroo-picking-api-openapi.yml)
- [Deliveroo Signature API](openapi/deliveroo-signature-api-openapi.yml)

### AsyncAPI

- [Deliveroo Webhooks](asyncapi/deliveroo-webhooks-asyncapi.yml)

### JSON Schema

17 JSON Schema files extracted from the OpenAPI and AsyncAPI specs are available in [json-schema/](json-schema/).

### JSON Structure

17 JSON Structure files converted from the JSON Schema files are available in [json-structure/](json-structure/).

### JSON-LD

- [deliveroo-order-api-context.jsonld](json-ld/deliveroo-order-api-context.jsonld)
- [deliveroo-menu-api-context.jsonld](json-ld/deliveroo-menu-api-context.jsonld)
- [deliveroo-site-api-context.jsonld](json-ld/deliveroo-site-api-context.jsonld)
- [deliveroo-catalogue-api-context.jsonld](json-ld/deliveroo-catalogue-api-context.jsonld)
- [deliveroo-picking-api-context.jsonld](json-ld/deliveroo-picking-api-context.jsonld)
- [deliveroo-signature-api-context.jsonld](json-ld/deliveroo-signature-api-context.jsonld)
- [deliveroo-webhooks-context.jsonld](json-ld/deliveroo-webhooks-context.jsonld)

### Examples

17 example payloads generated from the JSON Schema files are available in [examples/](examples/).

## Capabilities

Self-contained Naftiko capabilities, one per business surface (OpenAPI tag), each exposing both a REST and an MCP adapter routed through its own inline consumes block.

| Capability | API | Tools | Persona |
|----------|-----|-------|---------|
| [Order Lifecycle](capabilities/order-api-orders.yaml) | Order API | 1 | POS Integrator |
| [Order Sync Reporting](capabilities/order-api-sync-status.yaml) | Order API | 1 | POS Integrator |
| [Menu Management](capabilities/menu-api-menus.yaml) | Menu API | 2 | Restaurant Operator |
| [Site Availability](capabilities/site-api-opening-hours.yaml) | Site API | 1 | Restaurant Operator |
| [Grocery Catalogue](capabilities/catalogue-api-catalogue.yaml) | Catalogue API | 1 | Grocery Retailer |
| [Site Pricing](capabilities/catalogue-api-pricing.yaml) | Catalogue API | 1 | Grocery Retailer |
| [Grocery Picking](capabilities/picking-api-picking.yaml) | Picking API | 5 | Grocery Picker |
| [Signature Quotes](capabilities/signature-api-quotes.yaml) | Signature API | 1 | Merchant Integrator |
| [Signature Orders](capabilities/signature-api-orders.yaml) | Signature API | 1 | Merchant Integrator |
| [Signature Deliveries](capabilities/signature-api-deliveries.yaml) | Signature API | 1 | Merchant Integrator |

## Vocabulary

- [Deliveroo Vocabulary](vocabulary/deliveroo-vocabulary.yml) — Unified taxonomy mapping 6 resources, 7 actions, 10 workflows, and 5 personas across operational (OpenAPI) and capability (Naftiko) dimensions.

## Rules

- [Deliveroo Spectral Rules](rules/deliveroo-spectral-rules.yml) — 31 rules across info, servers, paths, operations, parameters, responses, schemas, security, tags, and HTTP-method categories enforcing Deliveroo API conventions.

## Commercial

- [Plans & Pricing](plans/deliveroo-plans-pricing.yml) — Marketplace commission tiers (standard / exclusive / own-driver), Retail Platform, and Signature per-delivery pricing using API Commons Plans 0.1.
- [Rate Limits](rate-limits/deliveroo-rate-limits.yml) — Per-order, per-site, and per-catalogue request limits using API Commons Rate Limits 0.1.
- [FinOps](finops/deliveroo-finops.yml) — FOCUS-aligned take-rate billing model and meters using the FinOps Framework.

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
