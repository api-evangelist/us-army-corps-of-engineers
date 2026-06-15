# US Army Corps of Engineers (us-army-corps-of-engineers)

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
