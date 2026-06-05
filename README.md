# Deliveroo (deliveroo)

A British online food delivery company operating across the United Kingdom, Europe, Asia, and the Middle East. Deliveroo's Developer Portal exposes three API suites — Partner Platform, Retail Platform, and Signature — that restaurants, grocers, and merchants use to integrate menus, orders, sites, and on-demand courier delivery.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/deliveroo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/deliveroo/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Food Delivery
- Grocery
- Marketplace
- Logistics
- Restaurants

## Timestamps

- **Created:** 2026-05-05
- **Modified:** 2026-06-02

## APIs

### Deliveroo Order API

The Deliveroo Order API is part of the Partner Platform Suite and manages restaurant orders and rider lifecycle events in real time. Orders and rider status updates are delivered to integrators via webhooks so that POS, kitchen display, and fulfillment systems can stay in sync without polling. Authentication uses OAuth-based credentials provisioned through the Deliveroo Developer Portal.

- **Human URL:** [https://api-docs.deliveroo.com/v2.0/docs](https://api-docs.deliveroo.com/v2.0/docs)
- **Base URL:** `https://api.developers.deliveroo.com`

#### Tags

- Orders
- Webhooks
- Restaurants
- Real-Time
- Riders

#### Properties

- [Documentation](https://api-docs.deliveroo.com/v2.0/docs)
- [Webhooks](https://api-docs.deliveroo.com/v2.0/docs)
- [OpenAPI](openapi/deliveroo-order-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/deliveroo-order-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/deliveroo-order-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [AsyncAPI](asyncapi/deliveroo-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)

### Deliveroo Menu API

The Deliveroo Menu API lets Partner Platform integrators publish and maintain restaurant menus, including stock levels, prices, POS identifiers, and allergen data. Menu updates can be pushed in near real time so that the consumer-facing Deliveroo experience reflects merchant inventory and pricing changes.

- **Human URL:** [https://api-docs.deliveroo.com/v2.0/docs](https://api-docs.deliveroo.com/v2.0/docs)
- **Base URL:** `https://api.developers.deliveroo.com`

#### Tags

- Menus
- Pricing
- Stock
- Allergens
- POS
- Restaurants

#### Properties

- [Documentation](https://api-docs.deliveroo.com/v2.0/docs)
- [OpenAPI](openapi/deliveroo-menu-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/deliveroo-menu-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/deliveroo-menu-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Deliveroo Site API

The Deliveroo Site API controls a merchant site's open/close status, operating hours, and workload mode (e.g., busy, paused). It is shared by both the Partner Platform Suite and the Signature Suite so that restaurants and merchants can govern fulfillment availability programmatically from their own systems.

- **Human URL:** [https://api-docs.deliveroo.com/v2.0/docs](https://api-docs.deliveroo.com/v2.0/docs)
- **Base URL:** `https://api.developers.deliveroo.com`

#### Tags

- Sites
- Restaurants
- Hours
- Status
- Operations

#### Properties

- [Documentation](https://api-docs.deliveroo.com/v2.0/docs)
- [OpenAPI](openapi/deliveroo-site-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/deliveroo-site-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/deliveroo-site-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Deliveroo Catalogue API

The Deliveroo Catalogue API is part of the Retail Platform Suite and manages master grocery catalogues of up to 30,000 items per merchant. Retailers use it to publish product data, variations, and availability across one or more retail sites operating on Deliveroo.

- **Human URL:** [https://api-docs.deliveroo.com/v2.0/docs](https://api-docs.deliveroo.com/v2.0/docs)
- **Base URL:** `https://api.developers.deliveroo.com`

#### Tags

- Catalogue
- Grocery
- Retail
- Products
- Inventory

#### Properties

- [Documentation](https://api-docs.deliveroo.com/v2.0/docs)
- [OpenAPI](openapi/deliveroo-catalogue-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/deliveroo-catalogue-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/deliveroo-catalogue-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Deliveroo Picking API

The Deliveroo Picking API supports the Retail Platform Suite picking flow, letting grocery operators process incoming orders, remove unavailable items, propose substitutions, and accept or reject orders prior to handoff to a courier.

- **Human URL:** [https://api-docs.deliveroo.com/v2.0/docs](https://api-docs.deliveroo.com/v2.0/docs)
- **Base URL:** `https://api.developers.deliveroo.com`

#### Tags

- Picking
- Grocery
- Retail
- Order Fulfillment
- Substitutions

#### Properties

- [Documentation](https://api-docs.deliveroo.com/v2.0/docs)
- [OpenAPI](openapi/deliveroo-picking-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/deliveroo-picking-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/deliveroo-picking-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Deliveroo Signature API

The Deliveroo Signature API powers the Signature Suite, which lets merchants request on-demand delivery by Deliveroo couriers for orders that originate in their own apps, websites, or channels — for example, a restaurant's branded ordering app dispatching a Deliveroo rider.

- **Human URL:** [https://api-docs.deliveroo.com/v2.0/docs](https://api-docs.deliveroo.com/v2.0/docs)
- **Base URL:** `https://api.developers.deliveroo.com`

#### Tags

- On-Demand Delivery
- Couriers
- Logistics
- Merchant Integration
- Custom Apps

#### Properties

- [Documentation](https://api-docs.deliveroo.com/v2.0/docs)
- [OpenAPI](openapi/deliveroo-signature-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/deliveroo-signature-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/deliveroo-signature-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/deliveroo)
- [LinkedIn](https://www.linkedin.com/company/deliveroo)
- [Website](https://deliveroo.co.uk/)
- [Developer Portal](https://developers.deliveroo.com/)
- [Documentation](https://api-docs.deliveroo.com/v2.0/docs)
- [Signup U R L](https://developers.deliveroo.com/)
- [Authentication](https://api-docs.deliveroo.com/v2.0/docs)
- [Privacy Policy](https://deliveroo.co.uk/privacy)
- [Terms of Service](https://deliveroo.co.uk/legal)
- [Support](https://deliveroo.co.uk/help)
- [Blog](https://deliveroo.co.uk/blog)
- [Spectral Rules](rules/deliveroo-spectral-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)
- [Vocabulary](vocabulary/deliveroo-vocabulary.yml)
- [Plans](plans/deliveroo-plans-pricing.yml)
- [Rate Limits](rate-limits/deliveroo-rate-limits.yml)
- [Fin Ops](finops/deliveroo-finops.yml)
