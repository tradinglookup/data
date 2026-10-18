# TradingLookup data

Tables built from what trading firms state in public, each row tied to the page it came from and the day it was read.

## In this repo
| File | What it is |
|---|---|
| `cfd-loss-rates.csv` | One row per CFD provider: the share of retail accounts its risk warning says lose money, the warning text, source URL, read date and a SHA-256 of the saved page text |
| `cfd-loss-rates-history.csv` | Earlier quarterly figures recovered from Internet Archive captures |
| `cfd-loss-rates-summary.json` | Headline numbers and release status |
| `cfd-loss-rates.datapackage.json` | Frictionless Data Package schema |

**Status:** v1.0.0, provisional. 31 providers read from the UK on 6 October 2026, 7 updated on 13 October 2026. An automated second read matched 16 figures and contradicted none; the rest await a human check.

## Cite it
See `CITATION.cff`. The Zenodo DOI goes here once it's minted.

## Licence
Data: CC BY 4.0. Credit "TradingLookup" and link to https://tradinglookup.com/brokers/cfd-loss-rates/.

## Corrections
Open an issue, or email hello@tradinglookup.com with the row and the source you think is right.
