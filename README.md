# Available .ICU One-Word Domains (10,968)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-10%2C968%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .icu one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **10,968 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 10,968 domains · **Median ask:** $46.04 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-27  
**Canonical page:** `https://unique.domains/domains/tld/icu`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/icu?utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./icu.csv">CSV</a> / <a href="./icu.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .ICU search](https://unique.domains/domains/tld/icu?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .ICU search](https://unique.domains/domains/tld/icu?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .ICU one-word domain catalog.

### Files

- `icu.csv` — public CSV extract (1,000 rows)
- `icu.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/icu-oneword-domains/main/icu.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain          | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                     |
| --------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------------------- |
| rewards.icu     | available | $1.99     | —             | 62             | 30     | 7      | name.com                      |
| hotels.icu      | resell    | —         | —             | 64             | 82     | 6      | Dynadot LLC                   |
| winners.icu     | premium   | $34.22    | $69.02        | 60             | 81     | 7      | namesilo                      |
| perspective.icu | available | $1.99     | —             | 78             | 27     | 11     | name.com                      |
| Tools.icu       | resell    | —         | —             | 56             | 40     | 5      | united-domains GmbH           |
| Chanel.icu      | premium   | $402.50   | $805          | 80             | 77     | 6      | namecheap                     |
| trades.icu      | available | $1.99     | —             | 71             | 26     | 6      | name.com                      |
| storyteller.icu | resell    | —         | —             | 82             | 25     | 11     | Dynadot LLC                   |
| farmers.icu     | premium   | $402.50   | $805          | 54             | 59     | 7      | namecheap                     |
| CapeCod.icu     | available | $20.98    | —             | 78             | 22     | 8      | namecheap                     |
| webshop.icu     | resell    | —         | —             | 76             | 21     | 8      | Dynadot LLC                   |
| events.icu      | premium   | $402.50   | $805          | 68             | 37     | 6      | namecheap                     |
| communities.icu | available | $1.99     | —             | 68             | 19     | 11     | name.com                      |
| hosts.icu       | resell    | —         | —             | 52             | 18     | 5      | NameSilo, LLC                 |
| tokens.icu      | premium   | $3,552.32 | —             | 51             | 36     | 6      | West263 International Limited |
| perks.icu       | available | $1.99     | —             | 62             | 19     | 5      | name.com                      |
| could.icu       | resell    | —         | —             | 78             | 8      | 5      | Go Daddy, LLC                 |
| homes.icu       | premium   | $124.60   | $249.20       | 86             | 34     | 5      | namecheap                     |
| outofoffice.icu | available | $1.99     | —             | 61             | 19     | 13     | name.com                      |
| clipart.icu     | resell    | —         | —             | 74             | 8      | 8      | IONOS SE                      |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 10,968 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/icu?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/icu?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .icu domains. The names range from broad dictionary words such as similar.icu, thing.icu, meaning.icu, and facts.icu to more functional terms like spreadsheet.icu and transfer.icu. For founders, the main question is whether the word is memorable, easy to say, and strong enough to carry a brand on a non-mainstream extension. For investors, the focus is usually buy-in discipline and realistic resale expectations. With a median ask of $46.04, price is accessible, so the harder part is choosing words with clear use cases, clean spelling, and low trademark risk.

- One-word .icu domains only
- 10,958 domains in this selection
- Median ask: $46.04
- Favor clear words with broad commercial use

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ICU One-Word Domains*. Version 2026-05-27. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ICU page](https://unique.domains/domains/tld/icu?utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
