# Penpot (penpot)

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

Penpot is an open-source design and prototyping platform built for design and code collaboration, offering a self-hostable alternative to Figma. It provides a REST RPC API that enables developers to programmatically access and manage projects, files, pages, components, and design assets. Authentication is handled via personal access tokens, and the platform supports outbound webhooks for event-driven integrations triggered by file changes, comments, and other workspace activity. Penpot also offers a plugin system and an MCP server for AI-assisted design-to-code workflows, making it a flexible integration target for modern development toolchains.

- **APIs.json:** https://raw.githubusercontent.com/api-evangelist/penpot/refs/heads/main/apis.yml
- **Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=penpot-api-evangelist&utm_content=repo

## Tags

Design, Prototyping, Open Source, Self-Hosted, Figma Alternative, UI Design, Collaboration, Design Systems

## APIs

| Name | Description | Human URL | Base URL |
|---|---|---|---|
| Penpot RPC API | Internal RPC-style REST API for programmatic access to projects, files, pages, and components | https://penpot.app/integrations-api | https://design.penpot.app/api/rpc/command/ |
| Penpot Webhooks | Outbound webhooks for event-driven integrations on file changes, comments, and workspace activity | https://help.penpot.app/technical-guide/integration/ | https://design.penpot.app/api/rpc/command/ |
| Penpot Plugin API | Plugin system for building custom extensions that integrate with the Penpot editor | https://doc.plugins.penpot.app/ | https://doc.plugins.penpot.app/ |

## Plans / Rate Limits / FinOps

| Resource | Path |
|---|---|
| Plans & Pricing | [plans/penpot-plans-pricing.yml](plans/penpot-plans-pricing.yml) |
| Rate Limits | [rate-limits/penpot-rate-limits.yml](rate-limits/penpot-rate-limits.yml) |
| FinOps | [finops/penpot-finops.yml](finops/penpot-finops.yml) |

**Pricing summary:** Free Professional cloud plan (up to 8 users, 10 GB storage); Unlimited at $7/user/month (capped at $175/month); Enterprise at $25/user/month (minimum $950/month). Self-hosted Professional is free and open-source. Private Server at $50,000/year.

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common

| Type | URL |
|---|---|
| Website | https://penpot.app/ |
| Documentation | https://help.penpot.app/technical-guide/integration/ |
| GitHub Org | https://github.com/penpot |
| LinkedIn | https://www.linkedin.com/company/penpotdesign |
| Blog | https://penpot.app/blog |
| Pricing | https://penpot.app/pricing |
| X | https://x.com/penpotapp |

## Maintainers

| Name | Email |
|---|---|
| Kin Lane | kin@apievangelist.com |
