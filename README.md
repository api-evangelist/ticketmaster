# Ticketmaster

Ticketmaster is the world's largest live entertainment ticketing company, providing access to tickets for concerts, sports, theater, and other live events globally. Their developer platform offers APIs for event discovery, ticket commerce, venue data, and partner integrations, giving developers access to over 230,000 events across dozens of countries.

**Website:** [https://www.ticketmaster.com](https://www.ticketmaster.com)  
**Developer Portal:** [https://developer.ticketmaster.com](https://developer.ticketmaster.com)

## APIs

| API | Description | Docs |
|-----|-------------|------|
| Ticketmaster Discovery API | Search events, attractions, venues, and classifications | [Docs](https://developer.ticketmaster.com/products-and-docs/apis/discovery-api/v2/) |
| Ticketmaster Commerce API | Ticket offers, pricing, and availability | [Docs](https://developer.ticketmaster.com/products-and-docs/apis/getting-started/) |
| Ticketmaster Partner API | Reserved for authorized distribution partners | [Docs](https://developer.ticketmaster.com/products-and-docs/apis/partner/) |

## OpenAPI Specifications

| Spec | Path |
|------|------|
| Ticketmaster Discovery API | [openapi/ticketmaster-discovery-openapi.yml](openapi/ticketmaster-discovery-openapi.yml) |
| Ticketmaster Commerce API | [openapi/ticketmaster-commerce-openapi.yml](openapi/ticketmaster-commerce-openapi.yml) |

## JSON Schemas

| Schema | Path |
|--------|------|
| Ticketmaster Event | [json-schema/ticketmaster-event-schema.json](json-schema/ticketmaster-event-schema.json) |
| Ticketmaster Venue | [json-schema/ticketmaster-venue-schema.json](json-schema/ticketmaster-venue-schema.json) |

## JSON Structure

| Structure | Path |
|-----------|------|
| Ticketmaster Event Structure | [json-structure/ticketmaster-event-structure.json](json-structure/ticketmaster-event-structure.json) |

## JSON-LD

| Context | Path |
|---------|------|
| Ticketmaster Context | [json-ld/ticketmaster-context.jsonld](json-ld/ticketmaster-context.jsonld) |

## Examples

| Example | Path |
|---------|------|
| Search Events | [examples/ticketmaster-search-events-example.json](examples/ticketmaster-search-events-example.json) |
| Search Venues | [examples/ticketmaster-search-venues-example.json](examples/ticketmaster-search-venues-example.json) |
| Get Event Offers | [examples/ticketmaster-get-event-offers-example.json](examples/ticketmaster-get-event-offers-example.json) |

## Spectral Rules

| Ruleset | Path |
|---------|------|
| Ticketmaster API Rules | [rules/ticketmaster-rules.yml](rules/ticketmaster-rules.yml) |

## Naftiko Capabilities

### Shared API Definitions

| API | Path |
|-----|------|
| Ticketmaster Discovery | [capabilities/shared/ticketmaster-discovery.yaml](capabilities/shared/ticketmaster-discovery.yaml) |
| Ticketmaster Commerce | [capabilities/shared/ticketmaster-commerce.yaml](capabilities/shared/ticketmaster-commerce.yaml) |

### Workflow Capabilities

| Workflow | APIs | Description |
|----------|------|-------------|
| [Event Discovery and Ticketing](capabilities/event-discovery-and-ticketing.yaml) | Discovery + Commerce | Search events, venues, attractions, and check ticket availability |

## Vocabulary

| Vocabulary | Path |
|------------|------|
| Ticketmaster Vocabulary | [vocabulary/ticketmaster-vocabulary.yml](vocabulary/ticketmaster-vocabulary.yml) |
