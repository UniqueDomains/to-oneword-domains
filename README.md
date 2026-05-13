# Available .TO One-Word Domains (8,112)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-8%2C112%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .to one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **8,112 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 8,112 domains · **Median ask:** $30.06 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-13  
**Canonical page:** `https://unique.domains/domains/tld/to`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/to?utm_source=github&utm_medium=referral&utm_campaign=repo_to_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./to.csv">CSV</a> / <a href="./to.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_to_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_to_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .TO search](https://unique.domains/domains/tld/to?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_to_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .TO search](https://unique.domains/domains/tld/to?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_to_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_to_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .TO one-word domain catalog.

### Files

- `to.csv` — public CSV extract (1,000 rows)
- `to.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/to-oneword-domains/main/to.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain           | status    | ask_price | renewal_price | attractiveness | demand | length | registrar |
| ---------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | --------- |
| Acup.to          | available | $29.98    | —             | 80             | 5      | 5      | namecheap |
| LGBTQ.to         | available | $29.98    | —             | 86             | 20     | 5      | namecheap |
| finals.to        | available | $29.98    | —             | 80             | 7      | 6      | namecheap |
| dogsit.to        | available | $29.98    | —             | 96             | 2      | 6      | namecheap |
| gearup.to        | available | $29.98    | —             | 80             | 16     | 7      | namecheap |
| pierogi.to       | available | $29.98    | —             | 82             | 7      | 7      | namecheap |
| stirup.to        | available | $29.98    | —             | 82             | 3      | 7      | namecheap |
| getlife.to       | available | $29.98    | —             | 80             | 5      | 8      | namecheap |
| headout.to       | available | $29.98    | —             | 82             | 6      | 8      | namecheap |
| fitin.to         | available | $29.98    | —             | 84             | 2      | 8      | namecheap |
| dogstail.to      | available | $29.98    | —             | 94             | 1      | 8      | namecheap |
| aloevera.to      | available | $29.98    | —             | 80             | 10     | 9      | namecheap |
| bedframe.to      | available | $29.98    | —             | 80             | 3      | 9      | namecheap |
| IsleofMan.to     | available | $29.98    | —             | 62             | 91     | 11     | namecheap |
| nets.to          | resell    | —         | —             | 54             | 81     | 4      | NAMECHEAP |
| keepthechange.to | available | $29.98    | —             | 46             | 59     | 15     | namecheap |
| regions.to       | resell    | —         | —             | 64             | 59     | 7      | NAMECHEAP |
| veterans.to      | available | $29.98    | —             | 56             | 23     | 8      | namecheap |
| shortcuts.to     | resell    | —         | —             | 48             | 41     | 10     | NAMECHEAP |
| justin.to        | resell    | —         | —             | 58             | 38     | 7      | NAMECHEAP |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 8,112 live domains                         |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/to?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_to_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/to?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_to_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_to_oneword_domains&utm_content=related_pricing)

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

These .to domains span a wide range of word styles, from concise brandables like Acup.to to direct dictionary and phrase-like names such as finals.to, forces.to, dogsit.to, and playin.to. For founders, the key question is whether a name is memorable, easy to say, and ownable without confusion. For investors, the focus is whether the ask leaves room versus likely resale demand for this extension. The median ask of 30.06 suggests many names may look inexpensive upfront, but quality still varies sharply. Give extra weight to clean spelling, broad commercial use, and obvious trademark exposure in names like audible.to.

- Prioritize short, clear .to names with clean spelling
- Compare ask price to the strength of the exact word
- Check trademark exposure before valuing brandable upside
- Favor names with broad use over narrow or awkward phrasing

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .TO One-Word Domains*. Version 2026-05-13. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .TO page](https://unique.domains/domains/tld/to?utm_source=github&utm_medium=referral&utm_campaign=repo_to_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_to_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_to_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_to_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
