# TYPO3 (typo3)

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

TYPO3 is an open-source enterprise PHP content management system providing REST APIs via the TYPO3 Headless extension and get.typo3.org release API for managing pages, content elements, media, navigation, and site configuration. The headless JSON content API delivers structured page and content data to decoupled frontend applications such as PWAs and SPAs.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/typo3/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/typo3/refs/heads/main/apis.yml)

## Tags

- CMS
- Content Management
- Enterprise
- PHP
- Headless
- JSON API
- Open Source

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### TYPO3 Headless JSON Content API

The TYPO3 Headless extension provides a JSON API for delivering page content, navigation structures, layouts, and media to decoupled frontend applications. Responds with JSON when the Accept header is set to application/json, enabling hybrid HTML and headless deployments from a single TYPO3 instance.

- **Human URL:** [https://docs.typo3.org/p/friendsoftypo3/headless/main/en-us/Index.html](https://docs.typo3.org/p/friendsoftypo3/headless/main/en-us/Index.html)
- **Base URL:** `https://example.typo3.org`

#### Tags

- Content
- Pages
- Navigation
- JSON
- Headless
- PWA

#### Properties

- [Documentation](https://docs.typo3.org/p/friendsoftypo3/headless/main/en-us/Index.html)
- [GitHub Repository](https://github.com/TYPO3-Headless/headless)
- [Extensions](https://extensions.typo3.org/extension/headless)

### TYPO3 Releases REST API

The get.typo3.org REST API provides information on available TYPO3 CMS releases, versions, and upgrade paths. Used internally by the TYPO3 Core to check for available upgrades and download new versions, this public API exposes structured release metadata for all supported TYPO3 versions.

- **Human URL:** [https://get.typo3.org/api/doc](https://get.typo3.org/api/doc)
- **Base URL:** `https://get.typo3.org/api`

#### Tags

- Releases
- Versions
- Upgrades
- CMS

#### Properties

- [Documentation](https://get.typo3.org/api/doc)
- [OpenAPI](openapi/typo3-releases-openapi.json) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Base U R L](https://get.typo3.org/api)

### TYPO3 REST API Extension (t3api)

The sourcebroker/t3api extension provides an easy-to-configure REST API layer for TYPO3 Extbase models. APIs are configured with PHP annotations on classes, properties, and methods, with partial support for JSON-LD and Hydra for auto-discoverable frontend applications.

- **Human URL:** [https://docs.typo3.org/p/sourcebroker/t3api/main/en-us/](https://docs.typo3.org/p/sourcebroker/t3api/main/en-us/)
- **Base URL:** `https://example.typo3.org`

#### Tags

- REST
- Extbase
- Extensions
- JSON-LD
- Hydra

#### Properties

- [Documentation](https://docs.typo3.org/p/sourcebroker/t3api/main/en-us/)
- [Getting Started](https://docs.typo3.org/p/sourcebroker/t3api/main/en-us/GettingStarted/Index.html)

## Common Properties

- [Website](https://typo3.org)
- [Documentation](https://docs.typo3.org)
- [Git Hub Org](https://github.com/TYPO3)
- [LinkedIn](https://www.linkedin.com/company/typo3-gmbh)
- [Blog](https://typo3.com/blog)
- [Pricing](https://typo3.com/typo3-cms/what-is-typo3/open-source/licenses)
- [Status Page](https://status.typo3.org)
- [X (Twitter)](https://twitter.com/typo3)
- [Plans](plans/typo3-plans-pricing.yml)
- [Rate Limits](rate-limits/typo3-rate-limits.yml)
- [Fin Ops](finops/typo3-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
