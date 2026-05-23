# Energy and Utilities (energy-utilities)

Energy and Utilities is a topic profile in the API Evangelist Network cataloging the API surfaces that move data across the modern electricity, gas, and water value chain. It indexes utility data integration APIs, grid and wholesale market operator APIs, federal energy data programs, renewable energy research APIs, weather APIs that drive grid demand and solar forecasting, EV charging interoperability protocols, and the Green Button family of customer energy data standards.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/energy-utilities/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **x-type:** topic
- **Position:** Aggregator

## Tags

Energy, Utilities, Electricity, Grid, Smart Meter, Meter Data, Green Button, Demand Response, DERMS, EV Charging, ISO/RTO, Renewable Energy, Solar, Wind, Weather, Open Data

## Timestamps

- **Created:** 2025-05-11
- **Modified:** 2026-05-23

## Sub-Topics

| Sub-Topic | Coverage |
|---|---|
| **Utility Data Integration APIs** | Arcadia Arc, Bayou Energy, UtilityAPI - third-party REST surfaces that authenticate against retail utilities and return Green Button aligned meter, interval, and billing data. |
| **ISO and RTO Wholesale Market APIs** | CAISO OASIS, ERCOT Developer Portal, PJM Data Miner 2, MISO Data Exchange, ISO-NE ISO Express - LMPs, load forecasts, generation mix, ancillary services, capacity. |
| **EIA Open Data API** | U.S. Energy Information Administration APIv2 - electricity, natural gas, petroleum, coal, nuclear outages, renewables, international energy time series. |
| **NREL Developer Network APIs** | National Renewable Energy Laboratory - NSRDB solar irradiance, PVWatts, Wind Resource, Utility Rate Database (URDB), Alternative Fuel Stations, Geothermal. |
| **Weather APIs for Grid and Solar** | NWS api.weather.gov (no-auth GeoJSON), OpenWeather Solar Irradiance and Solar Panel Energy Prediction, One Call 3.0. |
| **EV Charging Interoperability** | OCPP (charger to CMS), OCPI (CPO to eMSP roaming), ISO 15118 (vehicle to charger plug-and-charge). |
| **OpenADR Demand Response** | Open, two-way smart-grid standard for automating DR and orchestrating DERs. OpenADR 3.0 is current. |
| **Green Button (CMD / DMD / ESPI / CDS)** | Consumer energy data standard. ESPI defines the underlying REST/Atom payload (UsagePoint, MeterReading, IntervalBlock, ReadingType). |
| **DERMS APIs** | Distributed Energy Resource Management - typically wrap OpenADR for signaling and IEEE 2030.5 for device control. |

## Core Artifacts

This topic repo focuses on shared semantics for the **meter reading / energy data point** - the atom that every API in the catalog ultimately emits or consumes.

| Artifact | Path |
|---|---|
| Catalog index | [apis.yml](apis.yml) |
| MeterReading JSON Schema | [json-schema/energy-utilities-meter-reading-schema.json](json-schema/energy-utilities-meter-reading-schema.json) |
| EnergyDataPoint JSON Schema | [json-schema/energy-utilities-energy-data-point-schema.json](json-schema/energy-utilities-energy-data-point-schema.json) |
| UsagePoint JSON Schema | [json-schema/energy-utilities-usage-point-schema.json](json-schema/energy-utilities-usage-point-schema.json) |
| MeterReading JSON Structure | [json-structure/energy-utilities-meter-reading-structure.json](json-structure/energy-utilities-meter-reading-structure.json) |
| JSON-LD Context | [json-ld/energy-utilities-context.jsonld](json-ld/energy-utilities-context.jsonld) |
| Vocabulary | [vocabulary/energy-utilities-vocabulary.yml](vocabulary/energy-utilities-vocabulary.yml) |
| Examples | [examples/](examples/) |

## Example Payloads

- [UtilityAPI 15-min interval reading](examples/meter-reading-utilityapi-example.json)
- [Green Button ESPI hourly delivered reading](examples/meter-reading-green-button-espi-example.json)
- [CAISO SP15 real-time LMP](examples/energy-data-point-caiso-lmp-example.json)
- [EIA NYISO hourly load](examples/energy-data-point-eia-load-example.json)
- [NREL NSRDB solar irradiance sample](examples/energy-data-point-nrel-solar-irradiance-example.json)
- [OCPI EV charging session energy](examples/energy-data-point-ev-charging-session-example.json)
- [Residential UsagePoint with PV + battery DERs](examples/usage-point-electricity-residential-example.json)

## Common Properties

- [Topic Page](https://apievangelist.com/topics/energy-utilities/)
- [API Evangelist](https://apievangelist.com/)
- [Network](https://network.apievangelist.com/)
- [JSON-LD Context](json-ld/energy-utilities-context.jsonld)
- [Vocabulary](vocabulary/energy-utilities-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
