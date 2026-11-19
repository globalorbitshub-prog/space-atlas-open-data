# Space Atlas open data

A free list of the world's space organisations — companies, startups, space agencies, research centres,
universities, associations, spaceports and investors — from [Space Atlas](https://spaceatlas.space), the open map
of the global space industry.

- **2,900+ organisations in 110+ countries**, verified against official sources (company websites, registers,
  agency publications). No estimates, no third-party aggregators.
- **Updated daily**: a GitHub Action refreshes the files from <https://spaceatlas.space/open-data> every day.
- **Licence: [CC BY 4.0](LICENSE)** — free to use, share and adapt, also commercially, with attribution.

## Files

| File | Format |
| --- | --- |
| [`data/space-atlas-organisations.csv`](data/space-atlas-organisations.csv) | CSV, UTF-8, one row per organisation |
| [`data/space-atlas-organisations.json`](data/space-atlas-organisations.json) | JSON with licence and attribution metadata |

## Fields

| Field | Content |
| --- | --- |
| `name` | Organisation name |
| `type` | Organisation type (startup, private company, government agency, university, research institution…) |
| `country` | Headquarters country |
| `city` | Headquarters city |
| `continent` | Headquarters continent |
| `sectors` | Space sectors, separated by semicolons (e.g. `Earth Observation & Remote Sensing; Software & Data Analytics`) |
| `profile_url` | Space Atlas profile with every site, links, sectors and more |

## How to cite

> Data: Space Atlas (https://spaceatlas.space), CC BY 4.0

For quotable figures (organisations by country, sector and type, startups, founding decades) see
[Space industry statistics](https://spaceatlas.space/space-industry-statistics).

## Need more?

The [full Space Atlas dataset](https://spaceatlas.space/pricing) adds coordinates, every additional site
(factories, ground stations, R&D centres, spaceports), websites and LinkedIn, descriptions, founding years, and
funding rounds, revenue and investors with their sources. The interactive map and all profiles are free at
<https://spaceatlas.space>.

Missing an organisation or spotted an error? [Suggest it on Space Atlas](https://spaceatlas.space/submit).
