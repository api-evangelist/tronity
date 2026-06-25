# TRONITY (tronity)

TRONITY is a connected-car platform that aggregates electric vehicle and fleet telematics across 20-plus OEM brands into one normalized REST API. The TRONITY Platform API exposes vehicle data - battery state of charge, range, odometer, location, charging sessions and trips - plus remote commands (start/stop charging, wake-up) and webhooks, secured with OAuth2.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/tronity/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/tronity/refs/heads/main/apis.yml)

## Tags

- Connected Car
- EV
- Telematics
- Fleet
- Vehicle Data

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### TRONITY Vehicles API

Lists the connected vehicles available to an authenticated app or fleet, returns per-vehicle metadata and authorized scopes, and reads VIN for an individual vehicle across 20-plus supported OEM brands.

- **Human URL:** [https://app.tronity.tech/docs](https://app.tronity.tech/docs)
- **Base URL:** `https://api.tronity.tech`

#### Tags

- Vehicles
- VIN
- Telematics

#### Properties

- [Documentation](https://help.tronity.io/hc/en-us/articles/360018514299-Are-there-any-public-application-programming-interfaces-APIs)
- [API Reference](https://app.tronity.tech/docs)
- [OpenAPI](openapi/tronity-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tronity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tronity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TRONITY Vehicle Data API

Reads normalized telematics for a vehicle - odometer, geographic location, bulk last-known state, and historical records, trips, idles and sleeps - subject to the scopes granted by the vehicle owner.

- **Human URL:** [https://app.tronity.tech/docs](https://app.tronity.tech/docs)
- **Base URL:** `https://api.tronity.tech`

#### Tags

- Vehicle Data
- Odometer
- Location

#### Properties

- [Documentation](https://help.tronity.io/hc/en-us/articles/360018514299-Are-there-any-public-application-programming-interfaces-APIs)
- [API Reference](https://app.tronity.tech/docs)
- [OpenAPI](openapi/tronity-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tronity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tronity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TRONITY Charging & Battery API

Reads battery state of charge and range, the current charging status, and the history of charging sessions with energy, cost and location detail for a connected vehicle.

- **Human URL:** [https://app.tronity.tech/docs](https://app.tronity.tech/docs)
- **Base URL:** `https://api.tronity.tech`

#### Tags

- Charging
- Battery
- State of Charge

#### Properties

- [Documentation](https://help.tronity.io/hc/en-us/articles/360018514299-Are-there-any-public-application-programming-interfaces-APIs)
- [API Reference](https://app.tronity.tech/docs)
- [OpenAPI](openapi/tronity-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tronity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tronity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TRONITY Commands API

Sends remote commands to a vehicle - start charging, stop charging and wake-up - where the vehicle and the granted write scopes permit, using OAuth2-secured POST endpoints.

- **Human URL:** [https://app.tronity.tech/docs](https://app.tronity.tech/docs)
- **Base URL:** `https://api.tronity.tech`

#### Tags

- Commands
- Remote Control
- Charging

#### Properties

- [Documentation](https://help.tronity.io/hc/en-us/articles/360018514299-Are-there-any-public-application-programming-interfaces-APIs)
- [API Reference](https://app.tronity.tech/docs)
- [OpenAPI](openapi/tronity-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tronity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tronity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TRONITY Webhooks API

Manages webhook subscriptions on an app so external systems receive HTTP callbacks for vehicle and charging events, with a shared secret for payload verification.

- **Human URL:** [https://app.tronity.tech/docs](https://app.tronity.tech/docs)
- **Base URL:** `https://api.tronity.tech`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://help.tronity.io/hc/en-us/articles/360018514299-Are-there-any-public-application-programming-interfaces-APIs)
- [API Reference](https://app.tronity.tech/docs)
- [OpenAPI](openapi/tronity-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tronity.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tronity.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/tronity)
- [LinkedIn](https://www.linkedin.com/company/tronity)
- [Website](https://www.tronity.tech)
- [Documentation](https://app.tronity.tech/docs)
- [Plans](plans/tronity-plans-pricing.yml)
- [Rate Limits](rate-limits/tronity-rate-limits.yml)
- [Fin Ops](finops/tronity-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
