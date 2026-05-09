# Available .WORLD One-Word Domains (9,413)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-9%2C413%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .world one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **9,413 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 9,413 domains · **Median ask:** $9.50 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-09  
**Canonical page:** `https://unique.domains/domains/tld/world`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/world?utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./world.csv">CSV</a> / <a href="./world.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .WORLD search](https://unique.domains/domains/tld/world?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .WORLD search](https://unique.domains/domains/tld/world?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .WORLD one-word domain catalog.

### Files

- `world.csv` — public CSV extract (1,000 rows)
- `world.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/world-oneword-domains/main/world.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar   |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------- |
| Acup.world      | available | $52.98    | —             | 80             | 5      | 5      | namecheap   |
| barup.world     | available | $5.99     | —             | 82             | 2      | 6      | name.com    |
| forces.world    | available | $5.99     | —             | 82             | 12     | 6      | name.com    |
| geton.world     | available | $5.99     | —             | 82             | 10     | 6      | name.com    |
| reebok.world    | available | $5.99     | —             | 89             | 10     | 6      | name.com    |
| QandA.world     | available | $52.98    | —             | 80             | 10     | 7      | namecheap   |
| toneup.world    | available | $5.99     | —             | 80             | 5      | 7      | name.com    |
| stirup.world    | available | $5.99     | —             | 82             | 3      | 7      | name.com    |
| rumcake.world   | available | $5.99     | —             | 81             | 3      | 8      | name.com    |
| surebet.world   | available | $5.99     | —             | 82             | 8      | 8      | name.com    |
| chaitea.world   | available | $5.99     | —             | 86             | 3      | 8      | name.com    |
| dogstail.world  | available | $5.99     | —             | 94             | 1      | 8      | name.com    |
| getjiggy.world  | available | $5.99     | —             | 80             | 2      | 9      | name.com    |
| midautumn.world | available | $5.99     | —             | 80             | 2      | 9      | name.com    |
| getiton.world   | available | $5.99     | —             | 84             | 3      | 9      | name.com    |
| makes.world     | available | $5.99     | —             | 66             | 17     | 5      | name.com    |
| easy.world      | resell    | —         | —             | 84             | 67     | 4      | Porkbun LLC |
| Jim.world       | premium   | $92.40    | $92.40        | 78             | 28     | 3      | namecheap   |
| types.world     | available | $5.99     | —             | 54             | 14     | 5      | name.com    |
| tech.world      | resell    | —         | —             | 86             | 48     | 4      | Porkbun LLC |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 9,413 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/world?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/world?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain` — Fully qualified domain name.
- `status` — Current acquisition state for the domain in the public extract.
- `purchase_price` — Visible purchase price when available.
- `renewal_price` — Visible renewal price when available.
- `attractiveness` — Composite naming score used as a decision-support signal.
- `demand` — Relative buyer-pressure score when available.
- `length` — Character count without the TLD.
- `registrar` — Registrar name when known.
- `created_at` — Creation timestamp when known.
- `expires_at` — Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This selection is entirely made up of one-word .world domains. The set ranges from dictionary-style terms and action words to more unusual constructions such as Acup.world, forces.world, toneup.world, pierogi.world, and QandA.world. For founders, the main question is whether a name is memorable, easy to say, and specific enough to own with confidence. For investors, the key test is whether the word has credible buyer appeal at the asking level. A median ask of 9.5 keeps pricing grounded, but name quality still varies sharply. Be especially careful with terms that may lean generic, awkward, or trademark-sensitive.

- All domains in this set use the .world extension
- 9,390 one-word names; median ask is 9.5
- Check pronunciation, recall, and category fit
- Avoid obvious trademark conflicts like branded terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .WORLD One-Word Domains*. Version 2026-05-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .WORLD page](https://unique.domains/domains/tld/world?utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
