# Energy and Utilities (energy-utilities)

Energy and Utilities is a topic profile in the API Evangelist Network cataloging the API surfaces that move data across the modern electricity, gas, and water value chain. It indexes utility data integration APIs, grid and wholesale market operator APIs, federal energy data programs, renewable energy research APIs, weather APIs that drive grid demand and solar forecasting, EV charging interoperability protocols, and the Green Button family of customer energy data standards. The repo provides a baseline catalog plus shared semantics (JSON Schema, JSON-LD, vocabulary, examples) for the meter reading / energy data point that ties every one of these surfaces together.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/energy-utilities/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/energy-utilities/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Aggregator
- **Access:** 3rd-Party

## Tags

- Energy
- Utilities
- Electricity
- Grid
- Smart Meter
- Meter Data
- Green Button
- Demand Response
- DERMS
- EV Charging
- ISO/RTO
- Renewable Energy
- Solar
- Wind
- Weather
- Open Data

## Timestamps

- **Created:** 2025-05-11
- **Modified:** 2026-05-23

## APIs

### Utility Data Integration APIs

Third-party platforms that authenticate against retail electric, gas, and water utilities to retrieve customer meter, interval, and billing data on behalf of a consumer or business. These APIs collapse the thousands of US utility back-office systems into a single REST surface, typically aligned with the Green Button standard.

- **Human URL:** [https://utilityapi.com/](https://utilityapi.com/)

#### Tags

- Utility Data
- Meter Data
- Billing Data
- Green Button
- Authorization

#### Properties

- [Documentation](https://utilityapi.com/docs)
- [Documentation](https://docs.bayou.energy/)
- [Documentation](https://docs.arcadia.com/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/utilityapi/refs/heads/main/openapi/utilityapi-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Reference](https://www.arcadia.com/arc)
- [Postman Collection](collections/energy-utilities.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/energy-utilities.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### ISO and RTO Wholesale Market APIs

Independent System Operators and Regional Transmission Organizations publish locational marginal prices, load forecasts, generation mix, ancillary services awards, and capacity market data through public data portals and (where available) REST APIs. These are the primary sources for wholesale electricity market data in North America.

- **Human URL:** [https://oasis.caiso.com/](https://oasis.caiso.com/)

#### Tags

- Wholesale Market
- LMP
- Grid Operator
- Load Forecast
- Ancillary Services

#### Properties

- [Documentation](https://www.caiso.com/library/oasis-technical-specifications)
- [Documentation](https://developer.ercot.com/)
- [Reference](https://apiexplorer.ercot.com/)
- [Documentation](https://dataminer2.pjm.com/)
- [Reference](https://data-exchange.misoenergy.org/)
- [Reference](https://www.iso-ne.com/isoexpress/)
- [Postman Collection](collections/energy-utilities.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/energy-utilities.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EIA Open Data API

The U.S. Energy Information Administration publishes time-series data covering electricity, natural gas, petroleum, coal, nuclear outages, renewables, and international energy through APIv2. Datasets are organized by major energy category and accessed with an api.data.gov key.

- **Human URL:** [https://www.eia.gov/opendata/](https://www.eia.gov/opendata/)
- **Base URL:** `https://api.eia.gov/v2`

#### Tags

- Open Data
- Federal
- Electricity
- Natural Gas
- Petroleum
- Time Series

#### Properties

- [Documentation](https://www.eia.gov/opendata/documentation.php)
- [Sign Up](https://www.eia.gov/opendata/register.php)
- [Reference](https://www.eia.gov/opendata/browser/)
- [Postman Collection](collections/energy-utilities.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/energy-utilities.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### NREL Developer Network APIs

The National Renewable Energy Laboratory exposes a developer network of REST APIs covering solar resource (NSRDB, PVWatts), wind resource, alternative fuel stations, utility rates (URDB), transportation, buildings, and geothermal data. Authentication uses an api.data.gov key shared with other federal data programs.

- **Human URL:** [https://developer.nrel.gov/](https://developer.nrel.gov/)
- **Base URL:** `https://developer.nrel.gov/api`

#### Tags

- Renewable Energy
- Solar
- Wind
- Utility Rates
- Alternative Fuel

#### Properties

- [Documentation](https://developer.nrel.gov/docs/)
- [Sign Up](https://developer.nrel.gov/signup/)
- [Reference](https://nsrdb.nrel.gov/)
- [Postman Collection](collections/energy-utilities.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/energy-utilities.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Weather APIs for Grid and Solar

Weather APIs that feed grid-demand modelling, renewable generation forecasts, and outage operations. Includes the National Weather Service public API (no authentication, GeoJSON), OpenWeather solar irradiance and panel-output products, and commercial providers offering historical and predictive weather data used by utilities, ISOs, and energy traders.

- **Human URL:** [https://api.weather.gov/](https://api.weather.gov/)
- **Base URL:** `https://api.weather.gov`

#### Tags

- Weather
- Solar Irradiance
- Forecast
- GeoJSON
- Grid Demand

#### Properties

- [Documentation](https://www.weather.gov/documentation/services-web-api)
- [Documentation](https://openweathermap.org/api/solar-energy-prediction)
- [Documentation](https://openweathermap.org/api/one-call-3)
- [Postman Collection](collections/energy-utilities.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/energy-utilities.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### EV Charging Interoperability Protocols

Open protocols that govern communication between EV charging stations, charging management systems, and roaming hubs. OCPP is the charger-to-back-office protocol from the Open Charge Alliance. OCPI is the back-office-to-back-office roaming protocol. ISO 15118 handles vehicle-to-charger plug-and-charge. These specifications are the API contract for the EV charging network.

- **Human URL:** [https://openchargealliance.org/protocols/open-charge-point-protocol/](https://openchargealliance.org/protocols/open-charge-point-protocol/)

#### Tags

- EV Charging
- OCPP
- OCPI
- Roaming
- Smart Charging

#### Properties

- [Documentation](https://openchargealliance.org/protocols/open-charge-point-protocol/)
- [Documentation](https://evroaming.org/ocpi-protocol/)
- [Repository](https://github.com/ocpi/ocpi)
- [Repository](https://github.com/openchargealliance)
- [Postman Collection](collections/energy-utilities.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/energy-utilities.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### OpenADR Demand Response

OpenADR is an open, two-way information exchange model and Smart Grid standard for automating demand response and orchestrating distributed energy resources. The OpenADR Alliance publishes profile specifications, schema files, sample payloads, and test plans for utilities, aggregators, and DER vendors. OpenADR 3.0 is the current generation.

- **Human URL:** [https://www.openadr.org/](https://www.openadr.org/)

#### Tags

- Demand Response
- DER
- Smart Grid
- Standard

#### Properties

- [Documentation](https://www.openadr.org/specification)
- [Reference](https://www.openadr.org/openadr-30)
- [Postman Collection](collections/energy-utilities.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/energy-utilities.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Green Button (CMD / DMD / ESPI / CDS)

Green Button is the consumer energy data standard for utilities and third-party solution providers. Connect My Data (CMD) is the machine-to-machine sharing flow. Download My Data (DMD) is the user-initiated export flow. The Energy Services Provider Interface (ESPI) defines the underlying REST and Atom payloads (UsagePoint, MeterReading, IntervalBlock, ReadingType). The Consumer Data Specification (CDS) is the working group's next-generation profile.

- **Human URL:** [https://www.greenbuttonalliance.org/](https://www.greenbuttonalliance.org/)

#### Tags

- Green Button
- ESPI
- CDS
- Consumer Data
- Authorization
- OAuth2

#### Properties

- [Documentation](https://greenbuttonalliance.github.io/OpenESPI-GreenButton-API-Documentation/API/)
- [Repository](https://github.com/GreenButtonAlliance)
- [Reference](https://www.greenbuttonalliance.org/developer-resources)
- [Postman Collection](collections/energy-utilities.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/energy-utilities.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Distributed Energy Resource Management APIs

DERMS platforms aggregate, monitor, dispatch, and optimize distributed energy resources such as rooftop solar, behind-the-meter batteries, EV chargers, and controllable loads. DERMS API surfaces typically wrap OpenADR for event signaling, IEEE 2030.5 (SEP 2.0) for device-level control, and proprietary REST APIs for telemetry, enrollment, and settlement.

- **Human URL:** [https://www.openadr.org/](https://www.openadr.org/)

#### Tags

- DERMS
- DER
- Aggregation
- VPP
- IEEE 2030.5

#### Properties

- [Reference](https://standards.ieee.org/ieee/2030.5/5897/)
- [Reference](https://www.openadr.org/openadr-30)
- [Postman Collection](collections/energy-utilities.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/energy-utilities.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Topic Page](https://apievangelist.com/topics/energy-utilities/)
- [Website](https://apievangelist.com/)
- [Network](https://network.apievangelist.com/)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/energy-utilities/refs/heads/main/json-ld/energy-utilities-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/energy-utilities/refs/heads/main/json-schema/energy-utilities-meter-reading-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/energy-utilities/refs/heads/main/json-schema/energy-utilities-energy-data-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/energy-utilities/refs/heads/main/json-schema/energy-utilities-usage-point-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](https://raw.githubusercontent.com/api-evangelist/energy-utilities/refs/heads/main/json-structure/energy-utilities-meter-reading-structure.json)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/energy-utilities/refs/heads/main/vocabulary/energy-utilities-vocabulary.yml)
- [Examples](https://raw.githubusercontent.com/api-evangelist/energy-utilities/refs/heads/main/examples/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
