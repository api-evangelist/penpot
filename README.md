# Penpot (penpot)

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
