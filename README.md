# Ticketmaster (ticketmaster)

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

Ticketmaster is the world's largest live entertainment ticketing company, providing access to tickets for concerts, sports, theater, and other live events globally. Their developer platform offers APIs for event discovery, ticket commerce, venue data, and partner integrations, giving developers access to over 230,000 events across dozens of countries.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ticketmaster/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ticketmaster/refs/heads/main/apis.yml)

## Tags

- Commerce
- Concerts
- Entertainment
- Events
- Sports
- Tickets
- Venues

## Timestamps

- **Created:** 2025-01-08
- **Modified:** 2026-05-19

## APIs

### Ticketmaster Discovery API

The Ticketmaster Discovery API allows developers to search for events, attractions, venues, and classifications across the Ticketmaster platform. Provides access to over 230,000 events across the United States, Canada, Mexico, Australia, New Zealand, the UK, Ireland, and Europe. Content sources include Ticketmaster, Universe, FrontGate Tickets, and Ticketmaster Resale (TMR). Authentication is via API key in the query string or header.

- **Human URL:** [https://developer.ticketmaster.com/products-and-docs/apis/discovery-api/v2/](https://developer.ticketmaster.com/products-and-docs/apis/discovery-api/v2/)
- **Base URL:** `https://app.ticketmaster.com/discovery/v2`

#### Tags

- Attractions
- Classifications
- Events
- Search
- Venues

#### Properties

- [Documentation](https://developer.ticketmaster.com/products-and-docs/apis/discovery-api/v2/)
- [Portal](https://developer.ticketmaster.com)
- [OpenAPI](openapi/ticketmaster-discovery-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Ticketmaster Commerce API

The Ticketmaster Commerce API enables developers to build ticket purchasing flows, retrieve event inventory, check seat availability, and manage ticket orders. Provides access to price ranges, ticket limits, and purchase links.

- **Human URL:** [https://developer.ticketmaster.com/products-and-docs/apis/getting-started/](https://developer.ticketmaster.com/products-and-docs/apis/getting-started/)
- **Base URL:** `https://app.ticketmaster.com/commerce/v2`

#### Tags

- Commerce
- Inventory
- Orders
- Tickets

#### Properties

- [Documentation](https://developer.ticketmaster.com/products-and-docs/apis/getting-started/)
- [OpenAPI](openapi/ticketmaster-commerce-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/ticketmaster-commerce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ticketmaster-commerce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Ticketmaster Partner API

The Ticketmaster Partner API is a restricted API for authorized distribution partners that enables reserving, purchasing, and retrieving ticket and event information programmatically. Authentication uses API key via query parameter or x-api-key header.

- **Human URL:** [https://developer.ticketmaster.com/products-and-docs/apis/partner/](https://developer.ticketmaster.com/products-and-docs/apis/partner/)
- **Base URL:** `https://app.ticketmaster.com/partners/v1`

#### Tags

- Commerce
- Partner
- Reservations
- Tickets

#### Properties

- [Documentation](https://developer.ticketmaster.com/products-and-docs/apis/partner/)
- [F A Q](https://developer.ticketmaster.com/support/partner-api-faq/)
- [Postman Collection](collections/ticketmaster-commerce.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ticketmaster-commerce.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/ticketmaster)
- [Portal](https://developer.ticketmaster.com)
- [Documentation](https://developer.ticketmaster.com/products-and-docs/)
- [Getting Started](https://developer.ticketmaster.com/products-and-docs/apis/getting-started/)
- [A P I  Explorer](https://developer.ticketmaster.com/api-explorer/v2/)
- [Website](https://www.ticketmaster.com)
- [Blog](https://developer.ticketmaster.com/blog/)
- [Twitter](https://twitter.com/ticketmaster)
- [LinkedIn](https://www.linkedin.com/company/ticketmaster)
- [Terms of Service](https://developer.ticketmaster.com/support/terms-of-use/)
- [Privacy Policy](https://www.ticketmaster.com/h/privacy.html)
- [JSON-LD](json-ld/ticketmaster-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/ticketmaster-event-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
