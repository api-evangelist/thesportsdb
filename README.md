# TheSportsDB

An open, crowd-sourced sports database of artwork and metadata with a free sports API in JSON format. TheSportsDB provides comprehensive data on sports leagues, teams, players, events, venues, and season standings across hundreds of sports worldwide.

**URL:** [https://raw.githubusercontent.com/api-evangelist/thesportsdb/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/thesportsdb/refs/heads/main/apis.yml)

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Sports
- Database
- Free
- Open Data
- Teams
- Players
- Events

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-05-03

## APIs

### TheSportsDB API

An open, crowd-sourced sports database providing data on sports leagues, teams, players, events, venues, and standings with a free JSON API.

**Human URL:** [https://www.thesportsdb.com/](https://www.thesportsdb.com/)

**Base URL:** https://www.thesportsdb.com/api/v1/json/3

#### Tags

- Sports
- Database
- Free
- Teams
- Players
- Events
- Leagues

#### Operations

| Method | Path | Summary |
|--------|------|---------|
| GET | /searchteams.php | Search Teams |
| GET | /searchplayers.php | Search Players |
| GET | /searchevents.php | Search Events |
| GET | /searchvenues.php | Search Venues |
| GET | /all_leagues.php | List All Leagues |
| GET | /all_sports.php | List All Sports |
| GET | /search_all_teams.php | List All Teams |
| GET | /search_all_leagues.php | Search All Leagues |
| GET | /lookupleague.php | Lookup League |
| GET | /lookupteam.php | Lookup Team |
| GET | /lookupplayer.php | Lookup Player |
| GET | /lookupevent.php | Lookup Event |
| GET | /eventsnext.php | Get Next Team Events |
| GET | /eventslast.php | Get Last Team Events |
| GET | /eventsseason.php | Get Season Events |
| GET | /lookuptable.php | Lookup Table |
| GET | /search_all_seasons.php | List All Seasons |

#### Properties

- [Documentation](https://www.thesportsdb.com/documentation)
- [Website](https://www.thesportsdb.com/)
- [OpenAPI](openapi/thesportsdb-openapi.yml)
- [JSON Schema](json-schema/thesportsdb-team-schema.json)
- [JSON-LD](json-ld/thesportsdb-context.jsonld)
- [JSON Structure](json-structure/thesportsdb-structure.json)
- [Spectral Rules](rules/thesportsdb-rules.yml)
- [Capabilities](capabilities/sports-data.yaml)
- [Vocabulary](vocabulary/thesportsdb-vocabulary.yml)

## Artifacts

### OpenAPI Specs

- [TheSportsDB API](openapi/thesportsdb-openapi.yml)

### JSON Schemas

- [Team](json-schema/thesportsdb-team-schema.json)

### JSON Structure

- [TheSportsDB Structure](json-structure/thesportsdb-structure.json)

### JSON-LD

- [TheSportsDB Context](json-ld/thesportsdb-context.jsonld)

### Examples

- [Search Teams](examples/thesportsdb-search-teams-example.json)
- [Get Next Team Events](examples/thesportsdb-get-next-team-events-example.json)

### Spectral Rules

- [TheSportsDB Rules](rules/thesportsdb-rules.yml)

### Capabilities

- [Sports Data](capabilities/sports-data.yaml)

**Shared Definitions:**

- [TheSportsDB API](capabilities/shared/thesportsdb-api.yaml)

### Vocabulary

- [TheSportsDB Vocabulary](vocabulary/thesportsdb-vocabulary.yml)

## Common Properties

- [Website](https://www.thesportsdb.com/)
- [Documentation](https://www.thesportsdb.com/documentation)
- [Sign Up](https://www.thesportsdb.com/register)
- [Pricing](https://www.thesportsdb.com/patreon)
- [API Examples](https://www.thesportsdb.com/docs_api_examples)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
