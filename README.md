# US Army Corps of Engineers (us-army-corps-of-engineers)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

The US Army Corps of Engineers is a federal agency that plays a critical role in managing the nation's water resources and infrastructure. They are responsible for building and maintaining dams, levees, and flood control systems, overseeing construction of ports, harbors, and waterways, and providing engineering support to military operations. USACE publishes open APIs including the CWMS Data API for water management timeseries data, the National Inventory of Dams API, and open geospatial datasets.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Water Resources
- Federal Government
- Military Engineering
- Infrastructure
- Open Data
- Geospatial Data

## Timestamps

- **Created:** 2024-11-21
- **Modified:** 2026-05-19

## APIs

### USACE CWMS Data API

The Corps Water Management System Data API (CDA) is a RESTful API providing public access to USACE water management data. It supports retrieval of timeseries data (stream flow, reservoir levels, precipitation), location information, rating tables, location levels, reservoirs, and a full data catalog. The API supports pagination, unit conversion, and multiple date/time formats (ISO 8601 or epoch milliseconds). Data is publicly available without authentication for reading.

- **Human URL:** [https://cwms-data.usace.army.mil/cwms-data/](https://cwms-data.usace.army.mil/cwms-data/)
- **Base URL:** `https://cwms-data.usace.army.mil/cwms-data`

#### Tags

- Water Resources
- Federal Government
- Water Data
- Hydrological Data
- Open Data
- Timeseries
- REST API

#### Properties

- [Documentation](https://cwms-data.usace.army.mil/cwms-data/)
- [Swagger U I](https://cwms-data.usace.army.mil/cwms-data/swagger-ui.html)
- [GitHub Repository](https://github.com/USACE/cwms-data-api)
- [A P I Documentation](https://cwms-data-api.readthedocs.io/latest/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/openapi/usace-cwms-data-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Ruleset](https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/rules/usace-cwms-data-rules.yml)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/json-schema/usace-timeseries-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/json-ld/us-army-corps-of-engineers-context.jsonld)
- [Postman Collection](collections/usace-cwms-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usace-cwms-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USACE National Inventory of Dams API

The National Inventory of Dams (NID) API provides access to the comprehensive database of US dams maintained by the US Army Corps of Engineers. The database contains information on over 70 data fields for each dam including location, size, type, purpose, hazard classification, last inspection date, and owner information. The API supports searching and filtering dam records.

- **Human URL:** [https://nid.sec.usace.army.mil/](https://nid.sec.usace.army.mil/)

#### Tags

- Dams
- Federal Government
- Water Infrastructure
- Safety
- Geospatial Data

#### Properties

- [Documentation](https://nid.sec.usace.army.mil/)
- [Swagger U I](https://nid.sec.usace.army.mil/api/developer)
- [G I S Data](https://geospatial-usace.opendata.arcgis.com/datasets/1632cb2bb23046569fbf2bc144f06764_0)
- [Postman Collection](collections/usace-cwms-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usace-cwms-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### USACE Open Data

The USACE Open Data program provides public access to geospatial data, regulatory permit information, and other datasets maintained by the US Army Corps of Engineers. Data is available through ArcGIS Open Data, data.gov, and the USACE Regulatory portal.

- **Human URL:** [https://www.usace.army.mil/open/](https://www.usace.army.mil/open/)

#### Tags

- Open Data
- Federal Government
- Geospatial Data
- Water Resources
- Infrastructure

#### Properties

- [Documentation](https://www.usace.army.mil/open/)
- [Geo Spatial Portal](https://geospatial-usace.opendata.arcgis.com/)
- [Data Gov](https://catalog.data.gov/dataset?publisher=US+Army+Corps+of+Engineers)
- [Permits Portal](https://permits.ops.usace.army.mil/)
- [Postman Collection](collections/usace-cwms-data.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/usace-cwms-data.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/us-army-corps-of-engineers)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
