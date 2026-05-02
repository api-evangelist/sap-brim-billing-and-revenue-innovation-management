# SAP BRIM (Billing and Revenue Innovation Management)

SAP BRIM is a comprehensive solution for order-to-cash processes, subscription management, usage-based pricing, and revenue management. It enables businesses to manage complex billing scenarios, subscription lifecycle, and revenue recognition.

**URL:** https://www.sap.com/products/financial-management/billing-revenue-innovation-mgmt.html

## Tags

Billing, Enterprise, Order to Cash, Revenue Management, SAP, Subscription Management, Usage-Based Pricing

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-02

## APIs

### SAP Convergent Charging API

API for real-time charging and rating of usage-based services. Supports complex pricing models, prepaid and postpaid scenarios.

- **Base URL:** https://api.sap.com/convergent-charging/v1
- **Human URL:** https://help.sap.com/docs/SAP_CONVERGENT_CHARGING
- **OpenAPI:** [openapi/sap-brim-convergent-charging-openapi.yml](openapi/sap-brim-convergent-charging-openapi.yml)

### SAP Subscription Billing API

API for managing subscription lifecycle including creation, modification, renewal, and cancellation.

- **Base URL:** https://api.sap.com/subscription-billing/v1
- **Human URL:** https://help.sap.com/docs/SAP_SUBSCRIPTION_BILLING
- **OpenAPI:** [openapi/sap-brim-subscription-billing-openapi.yml](openapi/sap-brim-subscription-billing-openapi.yml)

### SAP Convergent Invoicing API

API for creating, managing, and processing invoices from multiple sources.

- **Human URL:** https://help.sap.com/docs/SAP_CONVERGENT_INVOICING

### SAP Contract Accounts Receivable and Payable API

API for managing customer accounts, payment processing, dunning, and dispute management.

- **Human URL:** https://help.sap.com/docs/SAP_CONTRACT_ACCOUNTS_RECEIVABLE_PAYABLE

### SAP BRIM Usage Data Intake API

API for ingesting high-volume usage data from various sources.

- **Human URL:** https://help.sap.com/docs/SAP_BRIM_USAGE_DATA_INTAKE

### SAP Revenue Accounting and Reporting API

API for revenue recognition according to IFRS 15 and ASC 606 standards.

- **Human URL:** https://help.sap.com/docs/SAP_REVENUE_ACCOUNTING_REPORTING

## Artifacts

### OpenAPI Specifications

| API | File |
|-----|------|
| SAP Convergent Charging API | [openapi/sap-brim-convergent-charging-openapi.yml](openapi/sap-brim-convergent-charging-openapi.yml) |
| SAP Subscription Billing API | [openapi/sap-brim-subscription-billing-openapi.yml](openapi/sap-brim-subscription-billing-openapi.yml) |

### Capabilities

Workflow-oriented Naftiko capability compositions:

| Workflow | Description |
|----------|-------------|
| [Subscription Lifecycle Management](capabilities/subscription-lifecycle-management.yaml) | End-to-end subscription management including onboarding, plan selection, and lifecycle transitions |
| [Usage-Based Charging](capabilities/usage-based-charging.yaml) | Real-time usage rating, convergent charging, and balance management |

**Shared per-API definitions (`capabilities/shared/`):**

- [convergent-charging.yaml](capabilities/shared/convergent-charging.yaml) — SAP BRIM Convergent Charging API
- [subscription-billing.yaml](capabilities/shared/subscription-billing.yaml) — SAP BRIM Subscription Billing API

### Rules

- [rules/sap-brim-rules.yml](rules/sap-brim-rules.yml) — Spectral ruleset for SAP BRIM API conventions

### JSON Schema

- [json-schema/sap-brim-subscription-schema.json](json-schema/sap-brim-subscription-schema.json)

### JSON Structure

- [json-structure/sap-brim-subscription-structure.json](json-structure/sap-brim-subscription-structure.json)
- [json-structure/sap-brim-rating-request-structure.json](json-structure/sap-brim-rating-request-structure.json)

### JSON-LD

- [json-ld/sap-brim-context.jsonld](json-ld/sap-brim-context.jsonld)

### Examples

- [examples/sap-brim-list-subscriptions-example.json](examples/sap-brim-list-subscriptions-example.json)
- [examples/sap-brim-rate-usage-event-example.json](examples/sap-brim-rate-usage-event-example.json)

### Vocabulary

- [vocabulary/sap-brim-vocabulary.yml](vocabulary/sap-brim-vocabulary.yml)

## Common Resources

- **Portal:** https://api.sap.com
- **Documentation:** https://help.sap.com/docs/BRIM
- **Getting Started:** https://help.sap.com/docs/SAP_BRIM/getting-started
- **Authentication:** https://help.sap.com/docs/SAP_BRIM/authentication
- **Support:** https://support.sap.com
- **Community:** https://community.sap.com
- **Website:** https://www.sap.com/products/financial-management/billing-revenue-innovation-management.html
- **Terms of Service:** https://www.sap.com/about/legal/terms-of-use.html
- **Privacy Policy:** https://www.sap.com/about/legal/privacy.html

## Maintainers

- **Kin Lane** — kin@apievangelist.com
