# US Army Corps of Engineers

The US Army Corps of Engineers (USACE) is a federal agency responsible for managing the nation's water resources and infrastructure, building and maintaining dams, levees, and flood control systems, overseeing construction of ports, harbors, and waterways, and providing engineering support to military operations. USACE publishes open APIs including the CWMS Data API for real-time water management data, the National Inventory of Dams API, and open geospatial datasets.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/us-army-corps-of-engineers/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Water Resources, Federal Government, Military Engineering, Infrastructure, Open Data, Geospatial Data

## Timestamps

- **Created:** 2024-11-21
- **Modified:** 2026-05-03

## APIs

### USACE CWMS Data API

The Corps Water Management System Data API (CDA) is a RESTful API providing public access to USACE water management data including timeseries, locations, ratings, levels, reservoirs, and data catalogs.

**Human URL:** [https://cwms-data.usace.army.mil/cwms-data/](https://cwms-data.usace.army.mil/cwms-data/)

#### Tags

- Water Resources, Federal Government, Water Data, Hydrological Data, Open Data, Timeseries, REST API

#### Properties

- [Documentation](https://cwms-data.usace.army.mil/cwms-data/)
- [Swagger UI](https://cwms-data.usace.army.mil/cwms-data/swagger-ui.html)
- [GitHub Repository](https://github.com/USACE/cwms-data-api)
- [API Documentation](https://cwms-data-api.readthedocs.io/latest/)
- [OpenAPI](openapi/usace-cwms-data-openapi.yml)
- [Spectral Rules](rules/usace-cwms-data-rules.yml)
- [Naftiko Capability](capabilities/water-data.yaml)
- [JSON Schema](json-schema/usace-timeseries-schema.json)
- [JSON-LD Context](json-ld/us-army-corps-of-engineers-context.jsonld)

### USACE National Inventory of Dams API

The National Inventory of Dams (NID) API provides access to the comprehensive database of US dams with 70+ data fields per dam.

**Human URL:** [https://nid.sec.usace.army.mil/](https://nid.sec.usace.army.mil/)

#### Tags

- Dams, Federal Government, Water Infrastructure, Safety, Geospatial Data

#### Properties

- [Documentation](https://nid.sec.usace.army.mil/)
- [Swagger UI](https://nid.sec.usace.army.mil/api/developer)
- [GIS Data](https://geospatial-usace.opendata.arcgis.com/datasets/1632cb2bb23046569fbf2bc144f06764_0)

### USACE Open Data

The USACE Open Data program provides public access to geospatial data, regulatory permit information, and other datasets.

**Human URL:** [https://www.usace.army.mil/open/](https://www.usace.army.mil/open/)

#### Tags

- Open Data, Federal Government, Geospatial Data, Water Resources, Infrastructure

#### Properties

- [Documentation](https://www.usace.army.mil/open/)
- [GeoSpatial Portal](https://geospatial-usace.opendata.arcgis.com/)
- [Data.gov](https://catalog.data.gov/dataset?publisher=US+Army+Corps+of+Engineers)
- [Permits Portal](https://permits.ops.usace.army.mil/)

## Artifacts

### OpenAPI

- [USACE CWMS Data API](openapi/usace-cwms-data-openapi.yml)

### Spectral Rules

- [USACE CWMS Data Rules](rules/usace-cwms-data-rules.yml)

### Capabilities

- [Water Data Capability](capabilities/water-data.yaml)
- [Shared: CWMS Data](capabilities/shared/cwms-data.yaml)

### JSON Schema

- [USACE Timeseries Schema](json-schema/usace-timeseries-schema.json)
- [USACE Location Schema](json-schema/usace-location-schema.json)

### JSON Structure

- [USACE Timeseries Structure](json-structure/usace-timeseries-structure.json)

### JSON-LD

- [USACE Context](json-ld/us-army-corps-of-engineers-context.jsonld)

### Examples

- [Get Timeseries Example](examples/usace-cwms-data-get-timeseries-example.json)
- [Get Locations Example](examples/usace-cwms-data-get-locations-example.json)

### Vocabulary

- [USACE Vocabulary](vocabulary/us-army-corps-of-engineers-vocabulary.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
