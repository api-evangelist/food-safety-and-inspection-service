# Food Safety and Inspection Service (food-safety-and-inspection-service)

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

The Food Safety and Inspection Service (FSIS) is a branch of the United States Department of Agriculture (USDA) responsible for ensuring the safety of the nation's commercial supply of meat, poultry, and egg products. FSIS publishes a Recall API that provides machine-readable access to recall and public health alert records.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/food-safety-and-inspection-service/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/food-safety-and-inspection-service/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Federal Government
- Food
- Food Safety
- Inspections
- Recalls
- Meat
- Poultry
- Eggs

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-19

## APIs

### FSIS Recall API

The FSIS Recall API returns a JSON list of recall and public health alert records for meat, poultry, and egg products. The endpoint is open and unauthenticated; the full dataset is returned on each request.

- **Human URL:** [https://www.fsis.usda.gov/science-data/developer-resources/recall-api](https://www.fsis.usda.gov/science-data/developer-resources/recall-api)
- **Base URL:** `https://www.fsis.usda.gov/fsis/api`

#### Tags

- Recalls
- Food Safety
- Public Health Alerts

#### Properties

- [Documentation](https://www.fsis.usda.gov/science-data/developer-resources/recall-api)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/food-safety-and-inspection-service/refs/heads/main/openapi/fsis-recall-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Capabilities](https://raw.githubusercontent.com/api-evangelist/food-safety-and-inspection-service/refs/heads/main/capabilities/fsis-recall-capabilities.yml)
- [Rules](https://raw.githubusercontent.com/api-evangelist/food-safety-and-inspection-service/refs/heads/main/rules/fsis-recall-rules.yml)
- [Postman Collection](collections/fsis-recall.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fsis-recall.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/usda-fsis)
- [Website](https://www.fsis.usda.gov/)
- [Documentation](https://www.fsis.usda.gov/science-data/developer-resources/recall-api)
- [Recalls](https://www.fsis.usda.gov/recalls)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
