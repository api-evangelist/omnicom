# Omnicom Group (omnicom)

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

Omnicom Group Inc. (NYSE: OMC) is the world's largest marketing and sales communications holding company, formed in its current shape when Omnicom completed its acquisition of Interpublic Group on 26 November 2025. It operates across advertising, media, precision marketing, commerce, public relations, healthcare, branding, experiential and production in more than 100 countries. The Omni platform, built and operated by Annalect, is positioned as an AI-driven marketing intelligence platform. The corporate site moved from omnicomgroup.com to omc.com, which now 301-redirects the legacy domain.

This repository captures the APIs, developer tools, and machine-readable API artifacts for Omnicom.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/omnicom/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Fortune 500
- Advertising
- Marketing
- Holding Company
- Media
- Public Relations
- Marketing Technology
- Commerce
- Data and Analytics

## Timestamps

- **Created:** 2026-03-21
- **Modified:** 2026-08-12

## APIs

No public APIs. As of the 2026-08-12 probe Omnicom publishes no developer portal, API reference, OpenAPI/AsyncAPI/GraphQL document, SDK, MCP server or A2A agent card on any host it controls. `api.omc.com`, `developer.omc.com` and `docs.omc.com` do not resolve in DNS; `www.omc.com` returns HTTP 404 for `/openapi.json`, `/llms.txt` and every `/.well-known/*` path; the Omni platform host `omni.omc.com` is an Angular single-page app that 301-redirects every unknown path to `/home/` and then serves the same HTML shell (a catch-all, not a document). See `x-coverage` in `apis.yml`.

## Common Properties

- [Website](https://www.omc.com)
- [LinkedIn](https://www.linkedin.com/company/omnicom)
- [Newsroom](https://www.omc.com/news/)
- [Investor Relations](https://investor.omc.com)
- [Terms of Service](https://www.omc.com/terms-of-use/)
- [Privacy Policy](https://www.omc.com/privacy-notice/)
- [GitHub Organization](https://github.com/annalect)
- [Domain Security](security/omnicom-domain-security.yml)
- [llms.txt](llms/omnicom-llms.txt)

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
