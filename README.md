# Dynamic (dynamic-xyz)

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

Dynamic is a wallet and authentication platform offering embedded wallets, social/email/passkey login, MPC signers, and a Backend / Admin REST API for managing users, wallets, and sessions. Provides SDKs across Web, React, React Native, Flutter, Swift, Kotlin, Node.js, Unity.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/dynamic-xyz/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/dynamic-xyz/refs/heads/main/apis.yml)

## Tags

- Web3
- Wallets
- Authentication
- Embedded Wallets
- MPC

## Timestamps

- **Created:** 2026-05-08
- **Modified:** 2026-05-08

## APIs

### Dynamic Backend API

REST API for backend integrations: list users and wallets, manage policies, validate JWTs, fetch auth events, manage environments.

- **Human URL:** [https://docs.dynamic.xyz/api-reference/overview](https://docs.dynamic.xyz/api-reference/overview)
- **Base URL:** `https://app.dynamicauth.com/api/v0`

#### Tags

- REST
- Admin

#### Properties

- [Documentation](https://docs.dynamic.xyz/api-reference/overview)
- [Postman Collection](collections/dynamic-xyz.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynamic-xyz.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynamic Wallets API

REST API to provision, sign, and manage server-controlled wallets across EVM, Solana, and other chains.

- **Human URL:** [https://docs.dynamic.xyz/wallets/server-wallets/overview](https://docs.dynamic.xyz/wallets/server-wallets/overview)
- **Base URL:** `https://app.dynamicauth.com/api/v0`

#### Tags

- REST
- Wallets

#### Properties

- [Documentation](https://docs.dynamic.xyz/wallets/server-wallets/overview)
- [Postman Collection](collections/dynamic-xyz.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynamic-xyz.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Dynamic Webhooks

Webhook delivery of auth, user, wallet, and session events. Subscriptions managed through dashboard and Backend API.

- **Human URL:** [https://docs.dynamic.xyz/developer-dashboard/webhooks](https://docs.dynamic.xyz/developer-dashboard/webhooks)
- **Base URL:** `https://app.dynamicauth.com/api/v0`

#### Tags

- Webhooks

#### Properties

- [Documentation](https://docs.dynamic.xyz/developer-dashboard/webhooks)
- [Postman Collection](collections/dynamic-xyz.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/dynamic-xyz.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/dynamic-labs)
- [LinkedIn](https://www.linkedin.com/company/dynamiclabs)
- [Website](https://www.dynamic.xyz/)
- [Plans](plans/dynamic-xyz-plans-pricing.yml)
- [Rate Limits](rate-limits/dynamic-xyz-rate-limits.yml)
- [Fin Ops](finops/dynamic-xyz-finops.yml)
- [Integrations](https://www.dynamic.xyz/partners)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
