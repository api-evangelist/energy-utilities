# Energy and Utilities (energy-utilities)

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
