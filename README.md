# Research Platform — Pillar 4

> **Personal OS**: Blog → Automation → Projects → **Research**

Personal academic portfolio and research infrastructure. This is the highest-leverage pillar — it converts the blog, automation, and project work into lasting intellectual capital.

**Strategy**: Preprint-first. Never wait for peer review to share work. Post to preprint servers immediately after completing a draft to establish timestamped intellectual priority.

## Working Papers

| Title | Status | Preprint | Dataset | Date |
|---|---|---|---|---|
| Structural Evolution of India's Passenger Vehicle Market | Drafting | TBD | complexity-lab/vahan-2015-2025 | 2026 |

## Folder Structure

```
research-platform/
├── papers/
│   └── paper-01-vahan-network/
│       ├── README.md           ← Paper metadata (title, abstract, status, DOI)
│       ├── draft.md            ← Working paper draft (Markdown)
│       ├── abstract.md         ← Abstract for preprint submission
│       ├── methodology.md      ← Methodology section
│       ├── references.bib      ← BibTeX references
│       └── figures/            ← Publication-quality figures from Complexity Lab
├── datasets/
│   └── vahan-network-2015-2025/
│       ├── README.md           ← Dataset documentation, citable
│       ├── schema.md           ← Data schema and collection methodology
│       └── CITATION.cff        ← GitHub citation format
├── notes/
│   ├── literature/             ← Reading notes, paper summaries
│   └── ideas/                  ← Early ideas, half-formed thoughts
└── README.md
```

## Paper Template

Each paper folder follows this front-matter schema:

```yaml
---
title: "Paper Title"
author: Kapil Gupta
date: YYYY-MM-DD
status: drafting | preprint | under-review | published
preprint_server: arXiv | SSRN | IndiaRxiv | OSF
doi: ""
dataset: complexity-lab/[dataset-name]
tags: [complexity-science, automotive, network-analysis, India]
---
```

## Preprint Strategy

| Platform | Best For | Submit When |
|---|---|---|
| **arXiv** (cs.SI / physics.soc-ph) | Complexity science, network analysis | First preference for technical papers |
| **SSRN** | Policy, economics, social science | CAFE policy papers, TCO analysis |
| **IndiaRxiv** | India-context research | All India-specific automotive papers |
| **OSF Preprints** | Interdisciplinary + dataset hosting | When sharing raw data |

**SSRN workflow** (fastest to Google Scholar indexing):
1. PDF upload → title + abstract + keywords
2. Select up to 12 subject eJournals
3. Submit for classifier review (under 30 min)
4. Personal author page auto-created → indexed by Google Scholar

## First Paper Roadmap

**"Structural Evolution of India's Passenger Vehicle Market: A Network Science Perspective Using VAHAN Registration Data (2015–2025)"**

- [ ] Complete Complexity Lab dataset (nodes.csv, edges.csv)
- [ ] Build temporal network in NetworkX
- [ ] Run Louvain community detection across all time periods
- [ ] Identify 3-4 key structural shifts (BSVI, COVID, EV)
- [ ] Generate Gephi visualizations for paper figures
- [ ] Write abstract + methodology
- [ ] Complete full draft
- [ ] Post to arXiv (physics.soc-ph)
- [ ] Submit to SSRN (Economics eJournal + India Policy)
- [ ] Add DOI to personal blog `/research` page
- [ ] Write blog post linking to preprint

## Research Identity Infrastructure

This repo powers the `/research` section of your blog:
- Each working paper linked with DOI
- Datasets citable (CITATION.cff)
- Visible from LinkedIn profile
- Builds toward PhD application portfolio

## PhD Alignment

Target programs: Complexity Science, Public Policy, Systems Science
- This research directly supports applications to SFI (Santa Fe Institute) complexity programs
- Establishes independent research track record before formal PhD

## Part of the Four-Pillar System

```
Pillar 1: personal-blog      (distribution engine)
Pillar 2: social-automation  (reach amplifier)
Pillar 3C: complexity-lab    (data + analysis → papers)
Pillar 4: research-platform  (this repo — intellectual capital)
```
