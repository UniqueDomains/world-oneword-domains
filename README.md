# Available .WORLD One-Word Domains (16,074)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-16%2C074%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .world one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **16,074 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 16,074 domains · **Median ask:** $6.30 · **High-demand under $2,500:** 0

**Last updated:** 2026-09-04
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

- `world.csv`, public CSV extract (1,000 rows)
- `world.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/world-oneword-domains/main/world.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain       | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                               |
| ------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ------------------------------------------------------- |
| ixc.world    | available | $2.98     | $52.98        | low            | low    | 3      | namecheap                                               |
| bee.world    | resell    | —         | —             | high           | medium | 3      | Alibaba Cloud Computing Ltd. d/b/a HiChina (www.net.cn) |
| due.world    | premium   | $82.50    | —             | high           | low    | 3      | name.com                                                |
| achy.world   | available | $2.98     | $52.98        | low            | low    | 4      | namecheap                                               |
| clx.world    | resell    | —         | —             | low            | low    | 3      | Sav.com, LLC                                            |
| ill.world    | premium   | $78.54    | $78.54        | medium         | low    | 3      | namesilo                                                |
| ague.world   | available | $2.98     | $52.98        | low            | low    | 4      | namecheap                                               |
| fin.world    | resell    | —         | —             | medium         | low    | 3      | GoDaddy.com, LLC                                        |
| MMR.world    | premium   | $38.94    | $38.94        | high           | low    | 3      | namesilo                                                |
| awry.world   | available | $2.98     | $52.98        | low            | low    | 4      | namecheap                                               |
| fix.world    | resell    | —         | —             | medium         | low    | 3      | Spaceship, Inc.                                         |
| fine.world   | premium   | $500      | $500          | high           | low    | 4      | name.com                                                |
| fell.world   | available | $2.98     | $52.98        | low            | low    | 4      | namecheap                                               |
| Fla.world    | resell    | —         | —             | medium         | low    | 3      | Sav.com, LLC - 40                                       |
| canoe.world  | premium   | $242      | $242          | high           | low    | 5      | namesilo                                                |
| heck.world   | available | $4.49     | $41.49        | medium         | low    | 4      | namesilo                                                |
| gun.world    | resell    | —         | —             | medium         | low    | 3      | Spaceship, Inc.                                         |
| boxing.world | premium   | $250      | —             | high           | low    | 6      | name.com                                                |
| ilxx.world   | available | $2.98     | $52.98        | low            | low    | 4      | namecheap                                               |
| its.world    | resell    | —         | —             | high           | medium | 3      | Spaceship, Inc.                                         |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 16,074 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/world?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/world?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=related_pricing)

## 🧱 Field summary

- `domain`, Fully qualified domain name.
- `status`, Current acquisition state for the domain in the public extract.
- `purchase_price`, Visible purchase price when available.
- `renewal_price`, Visible renewal price when available.
- `attractiveness`, Public composite naming band used as a decision-support signal.
- `demand`, Public buyer-pressure band when available.
- `length`, Character count without the TLD.
- `registrar`, Registrar name when known.
- `created_at`, Creation timestamp when known.
- `expires_at`, Expiry timestamp when known.

See [DATA_DICTIONARY.md](./DATA_DICTIONARY.md) for full definitions and types.

## ⚠️ Methodology and caveats

This list covers one-word domain names on the .world extension, currently totaling 9,444 entries with a median ask around $9.86. The mix ranges from short, brandable single words like succeed.world and project.world to compound-style names such as dogwalking.world and makehistory.world, plus a few names that closely echo established brands. Because .world is a broad, low-cost namespace, pricing tends to stay accessible, but brand-adjacent strings carry added trademark exposure worth checking before you commit.

- Median ask near $9.86 across this .world selection
- 9,444 one-word .world domains tracked, updated daily
- Mix of brandable names and compound one-word terms
- Some names echo existing brands — check trademark risk

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .WORLD One-Word Domains*. Version 2026-09-04. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .WORLD page](https://unique.domains/domains/tld/world?utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_world_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
