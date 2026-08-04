# Itch.io (itch-io)

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

Itch.io is an indie game marketplace and community platform where developers can publish, sell, and distribute games, assets, and creative tools. Its REST API provides authenticated access to game metadata, developer profile information, bundle and download key management, purchase verification, community ratings, and game distribution data. The API supports OAuth 2.0 implicit flow and API key authentication to enable integrations with developer tools, game launchers, and third-party services.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/itch-io/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/itch-io/refs/heads/main/apis.yml)

## Tags

- Games
- Indie Games
- Game Distribution
- Game Marketplace
- Developers

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Itch.io API

The itch.io server-side API provides authenticated access to user profiles, uploaded games, download key validation, purchase lookup, and build version retrieval. Authentication is via API key or short-lived JWT tokens using the Authorization Bearer header. Responses are JSON with snake_case naming and RFC 3339 dates.

- **Human URL:** [https://itch.io/docs/api/overview](https://itch.io/docs/api/overview)
- **Base URL:** `https://api.itch.io`

#### Tags

- Games
- Indie Games
- Downloads
- Purchases
- Profiles

#### Properties

- [Documentation](https://itch.io/docs/api/serverside)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/itch-io/refs/heads/main/openapi/openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [Website](https://itch.io)
- [Documentation](https://itch.io/docs/api/overview)
- [Git Hub Org](https://github.com/itchio)
- [LinkedIn](https://www.linkedin.com/company/itchio)
- [Blog](https://itch.io/blog)
- [Pricing](https://itch.io/docs/creators/pricing)
- [Status Page](https://www.saashub.com/itch-io-status)
- [X (Twitter)](https://twitter.com/itchio)
- [Plans](https://raw.githubusercontent.com/api-evangelist/itch-io/refs/heads/main/plans/plans.yml)
- [Rate Limits](https://raw.githubusercontent.com/api-evangelist/itch-io/refs/heads/main/rate-limits/rate-limits.yml)
- [Fin Ops](https://raw.githubusercontent.com/api-evangelist/itch-io/refs/heads/main/finops/finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
