# SAP BRIM (Billing and Revenue Innovation Management) (sap-brim-billing-and-revenue-innovation-management)

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

SAP BRIM (Billing and Revenue Innovation Management) is a comprehensive solution for order-to-cash processes, subscription management, usage-based pricing, and revenue management. It enables businesses to manage complex billing scenarios, subscription lifecycle, and revenue recognition.

**APIs.json:** [https://www.sap.com/products/financial-management/billing-revenue-innovation-mgmt.html](https://www.sap.com/products/financial-management/billing-revenue-innovation-mgmt.html)

## Tags

- Billing
- Enterprise
- Order to Cash
- Revenue Management
- SAP
- Subscription Management
- Usage-Based Pricing

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### SAP Convergent Charging API

API for real-time charging and rating of usage-based services. Supports complex pricing models, prepaid and postpaid scenarios.

- **Human URL:** [https://help.sap.com/docs/SAP_CONVERGENT_CHARGING](https://help.sap.com/docs/SAP_CONVERGENT_CHARGING)
- **Base URL:** `https://api.sap.com/convergent-charging`

#### Tags

- Charging
- Rating
- Real-Time
- Usage-Based Pricing

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_CONVERGENT_CHARGING)
- [OpenAPI](https://api.sap.com/api/convergent_charging/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/sap-brim-convergent-charging-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-brim-convergent-charging.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-brim-convergent-charging.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://help.sap.com/docs/SAP_CONVERGENT_CHARGING/authentication)

### SAP Convergent Invoicing API

API for creating, managing, and processing invoices from multiple sources. Supports complex billing scenarios, invoice consolidation, and flexible output formats.

- **Human URL:** [https://help.sap.com/docs/SAP_CONVERGENT_INVOICING](https://help.sap.com/docs/SAP_CONVERGENT_INVOICING)
- **Base URL:** `https://api.sap.com/convergent-invoicing`

#### Tags

- Billing
- Invoice Management
- Invoicing

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_CONVERGENT_INVOICING)
- [OpenAPI](https://api.sap.com/api/convergent_invoicing/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Sandbox](https://api.sap.com/api/convergent_invoicing/tryout)
- [Postman Collection](collections/sap-brim-convergent-charging.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-brim-convergent-charging.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sap-brim-subscription-billing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-brim-subscription-billing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Subscription Billing API

API for managing subscription lifecycle, including creation, modification, renewal, and cancellation. Supports various billing frequencies and subscription models.

- **Human URL:** [https://help.sap.com/docs/SAP_SUBSCRIPTION_BILLING](https://help.sap.com/docs/SAP_SUBSCRIPTION_BILLING)
- **Base URL:** `https://api.sap.com/subscription-billing`

#### Tags

- Lifecycle Management
- Recurring Billing
- Subscriptions

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_SUBSCRIPTION_BILLING)
- [OpenAPI](https://api.sap.com/api/subscription_billing/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/sap-brim-subscription-billing-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/sap-brim-subscription-billing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-brim-subscription-billing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [A P I  Console](https://api.sap.com/api/subscription_billing/console)
- [Reference](https://api.sap.com/package/SAPHybrisRevenueCloud/rest)
- [Getting Started](https://help.sap.com/doc/13f339973aee49e4a59f153b3c8299d8/2025-12-15/en-US/SAP_Subscription_Billing_API_Guide.pdf)
- [JSON Schema](json-schema/sap-brim-subscription-schema.json) — [JSON Schema](https://json-schema.org/specification)

### SAP Contract Accounts Receivable and Payable API

API for managing customer accounts, payment processing, dunning, and dispute management. Core component for financial customer relationship management.

- **Human URL:** [https://help.sap.com/docs/SAP_CONTRACT_ACCOUNTS_RECEIVABLE_PAYABLE](https://help.sap.com/docs/SAP_CONTRACT_ACCOUNTS_RECEIVABLE_PAYABLE)
- **Base URL:** `https://api.sap.com/fica`

#### Tags

- Accounts Receivable
- Dunning
- Financial Accounting
- Payments

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_CONTRACT_ACCOUNTS_RECEIVABLE_PAYABLE)
- [OpenAPI](https://api.sap.com/api/fica/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Integration  Guide](https://help.sap.com/docs/SAP_FICA/integration)
- [Postman Collection](collections/sap-brim-convergent-charging.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-brim-convergent-charging.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sap-brim-subscription-billing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-brim-subscription-billing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP BRIM Usage Data Intake API

API for ingesting high-volume usage data from various sources. Supports batch and real-time processing of usage events for rating and billing.

- **Human URL:** [https://help.sap.com/docs/SAP_BRIM_USAGE_DATA_INTAKE](https://help.sap.com/docs/SAP_BRIM_USAGE_DATA_INTAKE)
- **Base URL:** `https://api.sap.com/usage-data-intake`

#### Tags

- Data Ingestion
- Mediation
- Usage Data

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_BRIM_USAGE_DATA_INTAKE)
- [OpenAPI](https://api.sap.com/api/usage_data_intake/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Technical  Specifications](https://help.sap.com/docs/SAP_BRIM_USAGE_DATA_INTAKE/specs)
- [Postman Collection](collections/sap-brim-convergent-charging.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-brim-convergent-charging.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sap-brim-subscription-billing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-brim-subscription-billing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Revenue Accounting and Reporting API

API for revenue recognition according to IFRS 15 and ASC 606 standards. Manages performance obligations, revenue allocation, and compliance reporting.

- **Human URL:** [https://help.sap.com/docs/SAP_REVENUE_ACCOUNTING_REPORTING](https://help.sap.com/docs/SAP_REVENUE_ACCOUNTING_REPORTING)
- **Base URL:** `https://api.sap.com/revenue-accounting`

#### Tags

- ASC 606
- Compliance
- IFRS 15
- Revenue Recognition

#### Properties

- [Documentation](https://help.sap.com/docs/SAP_REVENUE_ACCOUNTING_REPORTING)
- [OpenAPI](https://api.sap.com/api/revenue_accounting/overview) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Compliance  Guide](https://help.sap.com/docs/SAP_REVENUE_ACCOUNTING_REPORTING/compliance)
- [Postman Collection](collections/sap-brim-convergent-charging.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-brim-convergent-charging.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sap-brim-subscription-billing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-brim-subscription-billing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SAP Subscription Order Management API

API for managing subscription-based orders within the SAP BRIM suite, supporting complex offerings that combine physical products, services, and usage-based fees with full lifecycle management.

- **Human URL:** [https://help.sap.com/docs/BRIM](https://help.sap.com/docs/BRIM)
- **Base URL:** `https://api.sap.com/subscription-order-management`

#### Tags

- Lifecycle Management
- Order Management
- Subscription Orders

#### Properties

- [Documentation](https://help.sap.com/docs/BRIM)
- [Postman Collection](collections/sap-brim-convergent-charging.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-brim-convergent-charging.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/sap-brim-subscription-billing.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/sap-brim-subscription-billing.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://api.sap.com)
- [OpenAPI](openapi/sap-brim-convergent-charging-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](openapi/sap-brim-subscription-billing-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON-LD](json-ld/sap-brim-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/sap-brim-subscription-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/sap-brim-subscription-structure.json)
- [JSON Structure](json-structure/sap-brim-rating-request-structure.json)
- [Spectral Rules](rules/sap-brim-rules.yml)
- [Vocabulary](vocabulary/sap-brim-vocabulary.yml)
- [Getting Started](https://help.sap.com/docs/SAP_BRIM/getting-started)
- [Authentication](https://help.sap.com/docs/SAP_BRIM/authentication)
- [Support](https://support.sap.com)
- [Terms of Service](https://www.sap.com/about/legal/terms-of-use.html)
- [Privacy Policy](https://www.sap.com/about/legal/privacy.html)
- [Status Page](https://www.sap.com/about/trust-center/cloud-service-status.html)
- [Community](https://community.sap.com)
- [Blog](https://blogs.sap.com)
- [Website](https://www.sap.com/products/financial-management/billing-revenue-innovation-management.html)
- [Documentation](https://help.sap.com/docs/BRIM)
- [S D Ks](https://developers.sap.com/)
- [GitHub Organization](https://github.com/SAP)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/sap)
- [Sign Up](https://developers.sap.com/)
- [YouTube](https://www.youtube.com/@sapdevs)
- [Learning](https://learning.sap.com/)
- [Onboarding](https://support.sap.com/en/product/onboarding-resource-center/brim.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
