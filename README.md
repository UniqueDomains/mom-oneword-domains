# Available .MOM One-Word Domains (11,562)

<p align="left">
  <img alt="status" src="https://img.shields.io/badge/status-active-2ea44f">
  <img alt="updated" src="https://img.shields.io/badge/updated-daily-0969da">
  <img alt="public extract" src="https://img.shields.io/badge/public%20extract-1%2C000%20rows-8250df">
  <img alt="live catalog" src="https://img.shields.io/badge/live%20catalog-11%2C562%20domains-6f42c1">
  <img alt="formats" src="https://img.shields.io/badge/formats-CSV%20%7C%20JSON-f59e0b">
  <img alt="license" src="https://img.shields.io/badge/license-see%20LICENSE-6b7280">
</p>

Daily-updated public extract of available and resale .mom one-word domains from Unique Domains.

> **Important:** this repository is a **public 1,000-row extract**, not the full live catalog.
> The full live catalog for this exact search currently contains **11,562 domains** on the canonical page below.

**Public extract:** 1,000 rows · **Live catalog:** 11,562 domains · **Median ask:** $352.49 · **High-demand under $2,500:** 0

**Last updated:** 2026-05-09  
**Canonical page:** `https://unique.domains/domains/tld/mom`  
**Best for:** founders, investors, studios

---

<p align="center">
  <a href="https://unique.domains/domains/tld/mom?utm_source=github&utm_medium=referral&utm_campaign=repo_mom_oneword_domains&utm_content=top_open_search"><b>🗂️ Open live database</b></a> ·
  <b>⬇️ Download sample</b>: <a href="./mom.csv">CSV</a> / <a href="./mom.json">JSON</a>
  · <a href="https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_mom_oneword_domains&utm_content=top_methodology"><b>🧪 Methodology</b></a>
  · <a href="https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_mom_oneword_domains&utm_content=top_api_docs"><b>🧰 API docs</b></a>
</p>

---

➡️ **Investors:** [Create a Radar from this .MOM search](https://unique.domains/domains/tld/mom?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_mom_oneword_domains&utm_content=top_create_radar)  
➡️ **Founders:** [Start a Project from this .MOM search](https://unique.domains/domains/tld/mom?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_mom_oneword_domains&utm_content=top_start_project)  
➡️ **Builders:** [Connect to our API](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_mom_oneword_domains&utm_content=top_api_docs)

---

## 📦 What this repository contains

This repository is the public extract for Unique Domains' .MOM one-word domain catalog.

### Files

- `mom.csv` — public CSV extract (1,000 rows)
- `mom.json` — public JSON extract (1,000 rows)
- `DATA_DICTIONARY.md` — field definitions for the exported files
- `METHODOLOGY.md` — scope, refresh policy, and caveats
- `CHANGELOG.md` — latest snapshot metadata
- `CITATION.cff` — machine-readable dataset citation metadata
- `LICENSE` — terms for the public extract

## 🧭 Quick start

```python
import pandas as pd

df = pd.read_csv("https://raw.githubusercontent.com/UniqueDomains/mom-oneword-domains/main/mom.csv")
print(df.head())
```

## 🗂️ Sample rows

| domain         | status    | ask_price | renewal_price | attractiveness | demand | length | registrar                          |
| -------------- | --------- | --------- | ------------- | -------------- | ------ | ------ | ---------------------------------- |
| barup.mom      | available | $1.99     | —             | 82             | 2      | 6      | name.com                           |
| lyrics.mom     | available | $1.99     | —             | 90             | 21     | 6      | name.com                           |
| dogsit.mom     | available | $1.99     | —             | 96             | 2      | 6      | name.com                           |
| hangon.mom     | available | $1.99     | —             | 82             | 6      | 7      | name.com                           |
| stirup.mom     | available | $1.99     | —             | 82             | 3      | 7      | name.com                           |
| leaveon.mom    | available | $1.99     | —             | 80             | 1      | 8      | name.com                           |
| messages.mom   | available | $1.99     | —             | 80             | 16     | 8      | name.com                           |
| presents.mom   | available | $1.99     | —             | 80             | 9      | 8      | name.com                           |
| rumcake.mom    | available | $1.99     | —             | 81             | 3      | 8      | name.com                           |
| spectra.mom    | available | $1.99     | —             | 62             | 34     | 7      | name.com                           |
| Keys.mom       | resell    | —         | —             | 66             | 46     | 4      | Dynadot LLC                        |
| CocaCola.mom   | premium   | $2,800    | $2,800        | 92             | 82     | 9      | namecheap                          |
| bees.mom       | available | $1.99     | —             | 54             | 27     | 4      | name.com                           |
| shops.mom      | resell    | —         | —             | 64             | 24     | 5      | Global Domains International, Inc. |
| insight.mom    | premium   | $2,500    | —             | 76             | 69     | 8      | name.com                           |
| systems.mom    | available | $1.99     | —             | 46             | 27     | 7      | name.com                           |
| orders.mom     | resell    | —         | —             | 60             | 19     | 6      | Spaceship, Inc.                    |
| donuts.mom     | premium   | $2,500    | —             | 54             | 62     | 6      | name.com                           |
| drops.mom      | available | $1.99     | —             | 52             | 25     | 5      | name.com                           |
| webmasters.mom | resell    | —         | —             | 52             | 12     | 10     | Spaceship, Inc.                    |

These rows are selected to show a more legible mix of visible asks, resale context, and status coverage from the exact live search.

## 🚀 Next move

You are seeing the public sample. Unique Domains keeps the exact search context and adds saved workflows, deeper filters, and alerting.

| GitHub extract          | Unique Domains                             |
| ----------------------- | ------------------------------------------ |
| 1,000-row public sample | 11,562 live domains                        |
| Static CSV / JSON       | live search and daily refresh              |
| Basic exported fields   | 0 high-demand names under $2,500           |
| No persistence          | Radar, saved search, and alerts            |
| No founder workflow     | Project, shortlist, and next-step workflow |

If this sample already feels useful, Unique Domains is where the exact search becomes a workflow.

[Create Radar](https://unique.domains/domains/tld/mom?github_intent=radar&utm_source=github&utm_medium=referral&utm_campaign=repo_mom_oneword_domains&utm_content=top_create_radar) · [Start Project](https://unique.domains/domains/tld/mom?github_intent=project&utm_source=github&utm_medium=referral&utm_campaign=repo_mom_oneword_domains&utm_content=top_start_project) · [See pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_mom_oneword_domains&utm_content=related_pricing)

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

This selection is entirely made up of one-word .mom domains. That makes the main evaluation issue less about raw brevity and more about fit between the word and the .mom ending. Names such as ladies.mom or dogsit.mom communicate a maternal, family, parenting, or women-focused angle more directly than broader terms like forces.mom or finals.mom. For founders, the best picks are the ones that read naturally, are easy to say aloud, and feel ownable now at the asking price. For investors, this set calls for tighter discipline: prioritize words with obvious end-user relevance, realistic resale paths, and pricing near or below the median ask of 352.49.

- Prioritize words that make immediate sense with .mom
- Median ask is 352.49, so price discipline matters
- Clear niche fit beats broad words on this extension
- Check for trademark risk before paying for strong terms

See [METHODOLOGY.md](./METHODOLOGY.md) for the full methodology reference.

## 🔄 Update policy

- This repository is refreshed regularly from the same export pipeline used for public dataset repos.
- The README count targets the live catalog count from the public landing response when available.
- The CSV and JSON files contain the public extract only and may not match the full live catalog size.
- Stable historical references should be published via GitHub Releases outside this repository snapshot.

See [CHANGELOG.md](./CHANGELOG.md) for the latest snapshot metadata.

## 📝 How to cite

Suggested citation:

> Unique Domains. *Available .MOM One-Word Domains*. Version 2026-05-09. Public GitHub extract for the exact Unique Domains search represented by this repository.

GitHub citation metadata is available in [CITATION.cff](./CITATION.cff).


## 🔗 Related links

- [Live .MOM page](https://unique.domains/domains/tld/mom?utm_source=github&utm_medium=referral&utm_campaign=repo_mom_oneword_domains&utm_content=top_open_search)
- [Technology and scoring](https://unique.domains/technology?utm_source=github&utm_medium=referral&utm_campaign=repo_mom_oneword_domains&utm_content=top_methodology)
- [Pricing](https://unique.domains/pricing?utm_source=github&utm_medium=referral&utm_campaign=repo_mom_oneword_domains&utm_content=related_pricing)
- [API docs](https://unique.domains/api?utm_source=github&utm_medium=referral&utm_campaign=repo_mom_oneword_domains&utm_content=top_api_docs)
- [Main catalog repo](https://github.com/UniqueDomains/oneword-domains)

## 📬 Contact

Questions, corrections, or partnership requests: `gaetan@unique.domains`
