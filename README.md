# Murrough Foley

SEO consultant and researcher building tools at the intersection of search engine optimization, high-performance web data extraction, and applied machine learning.

I've spent 12+ years in SEO — from affiliate sites and local SEO to enterprise product management and large-scale content operations. These days I focus on technical SEO, programmatic data pipelines, and building the tools I wish existed when I was running audits across thousands of pages.

## What I'm Working On

### Web Content Extraction

I build tools for extracting clean, structured content from web pages at scale. The modern web isn't just articles — it's product pages, forums, documentation, landing pages, and category grids. Most extraction tools only handle articles well. I'm working on making extraction work across all of them.

- **[rs-trafilatura](https://github.com/Murrough-Foley/rs-trafilatura)** — A Rust web content extraction library with ML page-type classification. Detects 7 page types, applies type-specific extraction profiles, outputs GitHub Flavored Markdown. F1=0.966 on ScrapingHub (#1), F1=0.859 on a 2,008-page multi-type benchmark. 44ms/page on CPU.

- **[web-content-extraction-benchmark](https://github.com/Murrough-Foley/web-content-extraction-benchmark)** — WCEB: a 2,008-page benchmark across 7 structurally distinct page types from 1,613 domains, with development and held-out test splits. 14 extraction systems benchmarked. Released under CC-BY-4.0. [DOI: 10.5281/zenodo.19316874](https://doi.org/10.5281/zenodo.19316874)

- **[web-page-classifier](https://github.com/Murrough-Foley/web-page-classifier)** — Standalone page type classifier (article, forum, product, collection, listing, documentation, service). Three-stage pipeline: URL heuristics, HTML signal analysis, XGBoost (181 features, 87% accuracy).

- **[html-cleaning](https://github.com/Murrough-Foley/html-cleaning)** — HTML sanitization library for content extraction pipelines. [crates.io](https://crates.io/crates/html-cleaning)

- **[quick_html2md](https://github.com/Murrough-Foley/quick_html2md)** — Fast HTML to Markdown conversion in Rust. [crates.io](https://crates.io/crates/quick_html2md)

### Research

My current research focuses on whether specialized heuristic+ML systems can outperform LLMs for web content extraction — and if so, when and why. Early results suggest that page-type-aware heuristic extraction beats both MinerU-HTML (0.6B) and ReaderLM-v2 (1.5B) on diverse page types while running 36-237x faster.

I'm preparing two papers:
- **WCEB: A Multi-Type Web Content Extraction Benchmark** — dataset paper introducing the benchmark and baseline results
- **Improving Web Content Extraction Through Page Type Classification** — system paper on page-type-aware extraction with ablation study and hybrid pipeline analysis

### SEO & Search

My professional background is in technical SEO — site architecture, crawl optimization, content quality analysis, and programmatic SEO at scale. I'm particularly interested in how content quality signals (structural depth, originality, topical coherence) correlate with rankings, and how to measure them reliably across different page types.

## Tech Stack

**Languages:** Rust, Python, JavaScript/TypeScript, Bash

**SEO & Web:** Technical auditing, site architecture, content extraction, programmatic SEO, crawl infrastructure

**ML/Data:** XGBoost, Random Forest, TF-IDF, content classification, benchmark construction, evaluation methodology

**Infrastructure:** AWS (Solutions Architect certified), Linux, Docker, DuckDB, Tauri

## Professional Background

- 12+ years in SEO across affiliate, local, enterprise, and consultancy
- Former SEO Product Manager at OneTwenty (iGaming)
- Founded Danang Digital (local SEO) and September Road Media (consultancy)
- AWS Solutions Architect, CCNA, Security+, Network+
- Based between London and Plovdiv, Bulgaria

## Links

- **Website:** [murroughfoley.com](https://murroughfoley.com)
- **LinkedIn:** [m-foley-seo](https://www.linkedin.com/in/m-foley-seo/)
- **HuggingFace:** [murrough-foley](https://huggingface.co/murrough-foley)
- **Twitter/X:** [@FoleyMurrough](https://twitter.com/FoleyMurrough)
- **crates.io:** [rs-trafilatura](https://crates.io/crates/rs-trafilatura)
- **ORCID:** [0009-0008-3127-2101](https://orcid.org/0009-0008-3127-2101)
- **Zenodo:** [DOI: 10.5281/zenodo.19316874](https://doi.org/10.5281/zenodo.19316874)

---

*I'm always interested in conversations about content extraction, SEO tooling, and applied ML for web data. Reach out on [LinkedIn](https://www.linkedin.com/in/m-foley-seo/) or [Twitter](https://twitter.com/FoleyMurrough).*
