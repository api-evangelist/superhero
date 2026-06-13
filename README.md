# Superhero API

APIs.json 0.19 provider profile for the Superhero API — a free REST API providing comprehensive data on 731 superheroes and villains from Marvel, DC, and other comic universes.

## Overview

The Superhero API (superheroapi.com) gives developers programmatic access to character data including power stats, biography, appearance, work, connections, and portrait images. Authentication uses a personal access token embedded in the request URL, obtained by signing in with GitHub at superheroapi.com.

**Base URL:** `https://superheroapi.com/api.php/{access-token}/{character-id}`

## Endpoints

| Endpoint | Description |
|----------|-------------|
| `/{token}/{id}` | Full character record |
| `/{token}/{id}/powerstats` | Intelligence, strength, speed, durability, power, combat |
| `/{token}/{id}/biography` | Full name, alter egos, first appearance, publisher, alignment |
| `/{token}/{id}/appearance` | Gender, race, height, weight, eye color, hair color |
| `/{token}/{id}/work` | Occupation and base of operations |
| `/{token}/{id}/connections` | Group affiliations and relatives |
| `/{token}/{id}/image` | Portrait image URL |
| `/{token}/search/{name}` | Search characters by name |

## Artifacts

- `apis.yml` — APIs.json 0.19 index
- `plans/superhero-plans-pricing.yml` — API Commons Plans schema
- `rate-limits/superhero-rate-limits.yml` — API Commons Rate Limits schema
- `finops/superhero-finops.yml` — FinOps Framework FOCUS-aligned definition

## Maintainer

Kin Lane &lt;kin@apievangelist.com&gt;
