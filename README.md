# TYPO3 (typo3)

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
