# Available .ICU One-Word Domains (15,132)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-15%2C132%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .icu one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **15,132 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 15,132 domains · **Median ask:** $37.31 · **High-demand under $2,500:** 51

**Last updated:** 2026-08-18
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

- `icu.csv`, public CSV extract (1,000 rows)
- `icu.json`, public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md`, field definitions for the exported files
- `METHODOLOGY.md`, scope, refresh policy, and caveats
- `CHANGELOG.md`, latest snapshot metadata
- `CITATION.cff`, machine-readable dataset citation metadata
- `LICENSE`, terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/icu-oneword-domains/main/icu.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain    | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                                    |
| --------- | --------- | --------- | ------------- | -------------- | ------ | ------ | -------------------------------------------- |
| aging.icu | available | $1.99     | $24.99        | high           | low    | 5      | name.com                                     |
| car.icu   | resell    | —         | —             | high           | medium | 3      | Xiamen ChinaSource Internet Service Co., Ltd |
| ate.icu   | premium   | $368      | $736          | high           | low    | 3      | namesilo                                     |
| agone.icu | available | $2.79     | $26.98        | low            | low    | 5      | namecheap                                    |
| cut.icu   | resell    | —         | —             | high           | low    | 3      | Dynadot LLC                                  |
| egg.icu   | premium   | $106.80   | $227.84       | high           | low    | 3      | namesilo                                     |
| aloud.icu | available | $1.99     | —             | high           | low    | 5      | name.com                                     |
| fin.icu   | resell    | —         | —             | medium         | low    | 3      | Xiamen ChinaSource Internet Service Co., Ltd |
| fee.icu   | premium   | $368      | $736          | high           | low    | 3      | namesilo                                     |
| apart.icu | available | $1.99     | —             | high           | low    | 5      | name.com                                     |
| xxx.icu   | resell    | —         | —             | low            | medium | 3      | 1API GmbH                                    |
| few.icu   | premium   | $34.22    | $69.02        | high           | low    | 3      | namesilo                                     |
| aroid.icu | available | $2.79     | $26.98        | low            | low    | 5      | namecheap                                    |
| live.icu  | resell    | —         | —             | high           | medium | 4      | Porkbun, LLC                                 |
| fig.icu   | premium   | $34.22    | $69.02        | medium         | low    | 3      | namesilo                                     |
| attic.icu | available | $2.79     | $26.98        | low            | low    | 5      | namecheap                                    |
| guest.icu | resell    | —         | —             | high           | low    | 5      | Dynadot LLC                                  |
| him.icu   | premium   | $106.80   | $227.84       | high           | low    | 3      | namesilo                                     |
| badly.icu | available | $1.99     | —             | medium         | low    | 5      | name.com                                     |
| gusto.icu | resell    | —         | —             | high           | low    | 5      | Dynadot LLC                                  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 15,132 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 51 high-demand names under $2,500          |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/icu?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/icu?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=related_pricing)

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

This list of one-word .ICU domain names covers 10,968 options across short, compound, and phrase-style words such as storyteller, pictures, dogsit, and coffeeglass. With a median asking price near $42, these domains sit in an affordable range for both quick acquisitions and portfolio building. Because .ICU carries less brand history than legacy TLDs, checking renewal cost and memorability matters before committing to any single name.

- 10,968 one-word .ICU domains available for review
- Median asking price near $42 across this selection
- Mix of short, compound, and phrase-style brand names
- Updated daily to reflect current pricing and availability

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .ICU One-Word Domains*. Version 2026-08-18. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .ICU page](https://unique.domains/domains/tld/icu?utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_icu_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
