# MapTiler (maptiler)

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

MapTiler is a map hosting and geospatial API platform providing vector tiles, satellite imagery, geocoding, static maps, elevation data, geolocation, and coordinate transformation via REST APIs and SDKs for web, mobile, and server-side developers. Based in Switzerland, MapTiler powers mapping for startups, enterprises, and GIS professionals worldwide through its MapTiler Cloud service.

APIs.json: https://raw.githubusercontent.com/api-evangelist/maptiler/refs/heads/main/apis.yml

Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=maptiler-api-evangelist&utm_content=repo

## Tags

Maps, Geospatial, Tiles, Vector Tiles, Satellite Imagery, Geocoding, Reverse Geocoding, Static Maps, Elevation, Geolocation, Coordinate Transformation, GIS, Mapping Platform

## APIs

| Name | Description |
|---|---|
| Maps API | Access MapTiler Cloud map styles including embeddable viewers, style configuration, raster tiles, and OGC-compatible endpoints |
| Tiles API | Delivers tile datasets including satellite imagery, terrain, and vector or raster tile collections via XYZ, OGC API - Tiles, and WMTS |
| Geocoding API | Forward and reverse geocoding to search for places and addresses globally; batch support for up to 50 queries |
| Static Maps API | Generates static non-interactive map images in PNG, JPG, or WebP with optional markers and paths (paid plans only) |
| Elevation API | Accurate altitude above mean sea level for up to 50 coordinate pairs per request in meters or feet |
| Geolocation API | Approximate location detection from IP address including country, city, coordinates, and timezone |
| Coordinates API | Search the EPSG coordinate system database and transform coordinates between projections for up to 50 pairs per request |

## Plans, Rate Limits, and FinOps

| Resource | Description |
|---|---|
| [Plans and Pricing](plans/maptiler-plans-pricing.yml) | Four tiers: Free ($0), Flex ($25/mo), Unlimited ($295/mo), and Custom. Priced on sessions, requests, and storage. |
| [Rate Limits](rate-limits/maptiler-rate-limits.yml) | Monthly session and request quotas per plan. Free plan suspends on overage; paid plans charge per-unit overages. |
| [FinOps](finops/maptiler-finops.yml) | FOCUS-aligned cost optimization guidance including tile caching, lazy initialization, batch geocoding, and API key segmentation. |

## Timestamps

- Created: 2026-06-12
- Modified: 2026-06-12

## Common

| Type | URL |
|---|---|
| Website | https://www.maptiler.com/ |
| Documentation | https://docs.maptiler.com/ |
| GitHub | https://github.com/maptiler |
| LinkedIn | https://www.linkedin.com/company/maptiler/ |
| Blog | https://www.maptiler.com/news/ |
| Pricing | https://www.maptiler.com/cloud/pricing/ |
| Status Page | https://status.maptiler.com |
| X | https://x.com/MapTiler |

## Maintainers

| Name | Email |
|---|---|
| Kin Lane | kin@apievangelist.com |
