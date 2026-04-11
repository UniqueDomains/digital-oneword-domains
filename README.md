# Available .DIGITAL One-Word Domains (7,019)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-7%2C008%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-7%2C019%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .digital one-word domains from Unique Domains.

> **Important:** this repository is a **public 7,008-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **7,019 domains** on the canonical page below.

**Public extract:** 7,008 rows · **Live catalog:** 7,019 domains

**Last updated:** 2026-04-11  
**Canonical page:** `https://unique.domains/domains/tld/digital`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/digital?utm_source=github&utm_medium=referral&utm_campaign=repo_digital_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./digital.csv">CSV</a> / <a href="./digital.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_digital_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_digital_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .DIGITAL search](https://unique.domains/domains/tld/digital?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_digital_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .DIGITAL search](https://unique.domains/domains/tld/digital?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_digital_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_digital_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .DIGITAL one-word domain catalog.

### Files

- `digital.csv` — public CSV extract (7,008 rows)
- `digital.json` — public JSON extract (7,008 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/digital-oneword-domains/main/digital.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain             | status    | ask_price | renewal_price | attractiveness | demand | length | registrar         |
| ------------------ | --------- | --------- | ------------- | -------------- | ------ | ------ | ----------------- |
| cock.digital       | available | $2.99     | —             | 58             | 27     | 4      | name.com          |
| majority.digital   | resell    | $2.99     | —             | 80             | 12     | 8      | Sav.com, LLC      |
| fast.digital       | premium   | $1,000    | $1,000        | 82             | 53     | 4      | name.com          |
| mysterious.digital | available | $2.99     | $54.99        | 68             | 20     | 10     | name.com          |
| behind.digital     | resell    | $2.99     | —             | 78             | 12     | 6      | Sav.com, LLC      |
| electric.digital   | premium   | $42.90    | $42.90        | 86             | 34     | 8      | namecheap         |
| easter.digital     | available | $2.99     | $54.99        | 110            | 19     | 6      | name.com          |
| whizz.digital      | resell    | $2.99     | $54.99        | 98             | 11     | 5      | Sav.com, LLC      |
| second.digital     | premium   | $82.50    | $82.50        | 120            | 28     | 6      | name.com          |
| abide.digital      | available | $53.98    | —             | 94             | 18     | 5      | namecheap         |
| silver.digital     | resell    | —         | —             | 56             | 99     | 6      | Sav.com, LLC - 23 |
| client.digital     | premium   | $42.90    | $85.80        | 70             | 28     | 6      | namecheap         |
| hundred.digital    | available | $2.99     | $54.99        | 88             | 18     | 7      | name.com          |
| automatic.digital  | resell    | —         | —             | 92             | 98     | 9      | Sav.com, LLC - 35 |
| sad.digital        | premium   | $42.90    | $42.90        | 72             | 27     | 3      | namecheap         |
| overnight.digital  | available | $2.99     | $54.99        | 112            | 17     | 9      | name.com          |
| asian.digital      | resell    | —         | —             | 82             | 98     | 5      | Sav.com, LLC      |
| cut.digital        | premium   | $82.50    | $82.50        | 124            | 26     | 3      | name.com          |
| disclosure.digital | available | $2.99     | —             | 71             | 16     | 10     | name.com          |
| commons.digital    | resell    | —         | —             | 63             | 98     | 7      | Sav.com, LLC - 5  |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                                   |
| ----------------------- | ------------------------------------------------ |
| 7,008-row public sample | 7,019 live domains                               |
| Static CSV / JSON       | live search and daily refresh                    |
| Basic exported fields   | deeper price, demand, risk, and workflow context |
| No persistence          | Radar, saved search, and alerts                  |
| No founder workflow     | Project, shortlist, and next-step workflow       |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/digital?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_digital_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/digital?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_digital_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_digital_oneword_domains&utm_content=related_pricing)

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

This repository follows the exact public search represented by the canonical page above.

- This repository is a public extract, not the full live catalog.
- Counts, prices, and statuses can change over time.
- Scores are decision-support signals, not guarantees of resale value.
- Trademark, SEO, and risk signals should be treated as screening inputs, not legal or specialist advice.
- Unique Domains contains deeper filters, monitoring, and decision workflows than this public extract.

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .DIGITAL One-Word Domains*. Version 2026-04-11. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .DIGITAL page](https://unique.domains/domains/tld/digital?utm_source=github&utm_medium=referral&utm_campaign=repo_digital_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_digital_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_digital_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_digital_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
