# CLAUDE.md — hack-the-plantet

## Project Overview

This is a personal DIY plant biohacking research project focused on understanding and improving **carbon fixation in plants**. The goal is to build deep knowledge of plant biology, quantitative measurement, and computational analysis before attempting gene editing. CRISPR is an optional final phase — the real work is rigorous measurement and original experiments.

This is an independent (non-institutional) research project. Timeline: 12–18 months, ~8–12 hours/week.

## Six-Phase Curriculum

| Phase | Duration | Focus |
|-------|----------|-------|
| 1 | Months 1–2 | Botanical foundations, sterile technique, tissue culture |
| 2 | Months 3–4 | Genetics, molecular biology, PCR, gel electrophoresis |
| 3 | Months 5–7 | Quantitative plant biology, experimental design, statistics |
| 4 | Months 8–10 | Python, bioinformatics, genomics databases, CRISPR target design |
| 5 | Months 11–14 | Original carbon capture research experiments |
| 6 | Months 15–18 | CRISPR/Cas9 gene editing (optional capstone) |

## Key Organisms

- **Arabidopsis thaliana** — primary model organism for genetics and CRISPR work; order from ABRC
- **Lemna minor** (duckweed) — fast-growing, ideal for quantitative carbon capture experiments
- **Brassica rapa** (Wisconsin Fast Plants) — 35-day lifecycle, used for selective breeding experiments

## Key Biology

**Carbon fixation genes of interest:**
- `rbcL` / `rbcS` — RuBisCO large and small subunits; the primary carbon-fixing enzyme
- `SBPase` — sedoheptulose-1,7-bisphosphatase; overexpression shown to boost carbon fixation 30–40%
- `EPFL9` / Stomagen — stomatal density regulator; affects CO₂ uptake vs. water loss tradeoff
- `PLGG1` — photorespiratory glycolate transporter; knockout enables photorespiratory bypass
- Carbonic anhydrase — concentrates CO₂ near RuBisCO

**Core concepts:**
- C3 vs. C4 vs. CAM photosynthesis pathways
- Calvin-Benson cycle and photorespiration
- Stomatal regulation (EPF/EPFL family, SLAC1)
- RGR (relative growth rate), net assimilation rate, specific leaf area
- NHEJ vs. HDR CRISPR repair pathways

## Computational Stack

- **Python** — pandas, matplotlib, scipy (stats), Biopython
- **Jupyter notebooks** — lab data analysis and visualization
- **Databases** — NCBI, TAIR (Arabidopsis), Phytozome, Ensembl Plants, NCBI GEO, KEGG, PMN
- **CRISPR tools** — CRISPOR, Benchling, Cas-OFFinder
- **OS** — CachyOS Linux (Arch-based)

## What to Help With

- Writing Python scripts for lab data analysis (growth curves, RGR calculations, t-tests, ANOVA)
- Bioinformatics tasks: BLAST queries, parsing FASTA/GenBank files, Biopython workflows
- Experimental design review: controls, replication, statistical power
- CRISPR guide RNA design and off-target analysis
- Literature interpretation and protocol troubleshooting
- Pathway analysis and candidate gene identification
- Automating repetitive data processing tasks

## Lab Notebook Standards

Every experiment must have:
- Clear hypothesis
- Positive and negative controls
- Minimum 3 biological replicates
- Statistical analysis (t-test or ANOVA as appropriate)
- Quantitative measurements, not qualitative observations

Document in Jupyter notebooks or CSV/spreadsheet format. Graph all data. Write results as if preparing a preprint.

## Constraints

- Home lab setting — no institutional equipment or reagents beyond what's affordable for hobbyists
- Biosafety: work with BSL-1 organisms only; Arabidopsis and Lemna minor are appropriate
- Prefer open-source tools and freely available data (NCBI GEO, preprints, etc.)

## Commit Style

Never add "Co-Authored-By: Claude" lines to commit messages.
