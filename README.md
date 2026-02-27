# DIY Plant Biohacker Learning Plan

**Botany · Quantitative Biology · Bioinformatics · Carbon Capture · CRISPR**

*A hybrid curriculum for the home plant experimenter with a focus on understanding carbon fixation in plants.*

**Estimated timeline:** 12–18 months

---

## Overview & Philosophy

This plan is designed for a self-taught hobbyist with an interest in plant carbon capture. Rather than rushing to CRISPR, it takes a hybrid approach: building deep understanding of plant biology, quantitative measurement, and computational analysis before touching gene editing tools. The reasoning is simple — knowing what to edit and how to measure the result matters far more than the editing itself.

CRISPR appears at the end as an optional capstone. By the time you reach it, you'll know exactly which genes are worth targeting and have the infrastructure to evaluate whether an edit actually improved carbon fixation. Many of the most interesting experiments you can do at home don't require gene editing at all.

---

## Plan Structure

- **Phase 1 (Months 1–2):** Botanical Foundations — Plant biology, cell structure, and basic lab skills
- **Phase 2 (Months 3–4):** Genetics & Molecular Biology — DNA, gene expression, PCR
- **Phase 3 (Months 5–7):** Quantitative Plant Biology — Experimental design, measurement, statistics, and carbon fixation biology
- **Phase 4 (Months 8–10):** Computational Skills & Bioinformatics — Python, genomics databases, pathway analysis, target identification
- **Phase 5 (Months 11–14):** Carbon Capture Research — Selective breeding, phenotyping, and original experiments
- **Phase 6 (Months 15–18, Optional):** CRISPR & Plant Transformation — Gene editing with informed target selection

Plan for roughly 8–12 hours per week. Consistency matters more than speed. Some phases can overlap — computational work pairs well with bench time.

---

## Phase 1: Botanical & Biological Foundations

**Duration:** Months 1–2
**Goal:** Understand plant anatomy and cell biology. Develop sterile technique and basic lab habits.

### Study Topics

- **Plant cell structure:** cell walls, chloroplasts, vacuoles, plasmodesmata. What makes plant cells different from animal cells, and why chloroplast biology matters for carbon fixation.
- **Plant anatomy:** roots, stems, leaves, meristems. Where growth happens and why meristematic tissue matters for transformation and regeneration.
- **Photosynthesis overview:** light reactions vs. Calvin cycle, C3 vs. C4 vs. CAM pathways. This is your first exposure to the carbon fixation machinery you'll study deeply later.
- **Basic chemistry:** pH, buffers, molar concentrations. Essential for making media and solutions.
- **Sterile technique:** contamination sources, autoclaving, working in a still-air box, flame sterilization.

### Resources

**Plant biology and cell science:**

- **Botany in a Day** (Thomas Elpel) — Approachable intro to plant families and structure.
- **MIT OpenCourseWare 7.013** — Introductory Biology. Free lectures covering cell biology fundamentals.
- **Khan Academy Biology** — Cell structure, photosynthesis, DNA basics. Excellent visual explanations.
- **Life in the Light** (photosynthesis chapters in any plant physiology textbook) — Taiz & Zeiger's *Plant Physiology* is the gold standard; older editions are cheap used.

**Sterile technique and home lab skills:**

- **The Thought Emporium** (YouTube) — Practical series on home tissue culture covering sterile technique, still-air box use, and media preparation in a non-institutional setting.
- **Plant Tissue Culture: A Home-Based Guide** (DIYbio community wikis) — Freely available walkthroughs of surface sterilization, still-air box construction, pouring plates, and flame technique with photos.
- **PlantCell Technology blog** — Free step-by-step guides on preparing MS media and working aseptically.
- **The ODIN's basic microbiology guides** — Originally designed for their CRISPR kits, these cover aseptic technique, autoclaving with a pressure cooker, and streaking plates. The skills transfer directly to plant work.
- **Biopunk: Kitchen-Counter Scientists Hack the Software of Life** (Marcus Wohlsen) — Not a protocol book, but useful context on how DIY labs are set up and what's realistically achievable outside institutions.

### Hands-On Projects

- **Build a still-air box:** Clear plastic tub with arm holes. Practice flaming tools and pouring agar plates inside it.
- **Prepare MS media:** Buy MS basal salt mix, agar, sucrose. Practice making plates, adjusting pH, and autoclaving with a pressure cooker.
- **Plant tissue culture:** Take stem cuttings from an African violet or pothos, surface-sterilize, and establish sterile cultures on MS media.
- **Leaf disc photosynthesis assay:** Punch leaf discs, submerge in sodium bicarbonate solution, and time how quickly they float (as O₂ from photosynthesis makes them buoyant). Simple, visual, and directly relevant to carbon fixation.

### Milestone

You can maintain contamination-free tissue cultures for 2+ weeks, explain C3 vs. C4 photosynthesis, and have run your first quantitative photosynthesis assay.

---

## Phase 2: Genetics & Molecular Biology

**Duration:** Months 3–4
**Goal:** Understand how genes work, what DNA is, and learn PCR as a core verification technique.

### Study Topics

- **DNA structure & gene anatomy:** double helix, base pairing, promoters, exons, introns, terminators. What a gene physically looks like.
- **Central dogma:** DNA → RNA → Protein. Transcription and translation. What it means to "edit a gene."
- **Mendelian genetics:** dominant/recessive, genotype vs. phenotype. Important for understanding inheritance of any edits or selected traits.
- **PCR:** how it works, primer design, thermal cycling, gel electrophoresis to visualize results.
- **Carbon fixation genes:** Begin learning about RuBisCO (rbcL/rbcS), carbonic anhydrase, SBPase, PEPC, and stomatal regulation genes (EPFL9, MUTE, FAMA). You don't need to memorize them — just start building familiarity.

### Resources

- **Molecular Biology of the Gene** (Watson et al.) — Used older editions are cheap. Focus on DNA, transcription, translation chapters.
- **iBiology YouTube channel** — Short lectures from working scientists on molecular biology topics.
- **RIPE Project resources** (ripe.illinois.edu) — The Realizing Increased Photosynthetic Efficiency project publishes accessible summaries of carbon fixation improvement research. Start reading their publications list.

### Hands-On Projects

- **DNA extraction:** Extract DNA from plant leaf tissue using CTAB buffer. Practice on multiple species.
- **Set up PCR:** Buy a used thermocycler. Run PCR using rbcL primers (the RuBisCO large subunit gene) — directly relevant to carbon fixation and well-characterized with universal primers.
- **Gel electrophoresis:** Build or buy a mini gel rig. Run your PCR products on an agarose gel.
- **Grow model organisms:** Start growing Arabidopsis thaliana (order from ABRC) and duckweed (Lemna minor, available from aquarium suppliers). Both are critical for later phases — Arabidopsis as the model for genetics, duckweed as a fast-growing system ideal for carbon capture experiments.

### Milestone

You can extract plant DNA, amplify rbcL via PCR, visualize it on a gel, and explain what RuBisCO does and why it's central to carbon fixation.

---

## Phase 3: Quantitative Plant Biology & Experimental Design

**Duration:** Months 5–7
**Goal:** Learn to design rigorous experiments, measure plant growth quantitatively, and understand the biology of carbon fixation deeply enough to identify research questions.

This phase is the heart of the hybrid approach. Most hobbyists skip straight to molecular tools, but the ability to measure phenotypes precisely and design controlled experiments is what separates real research from following protocols blindly.

### Study Topics

- **Experimental design:** controls (positive and negative), replication, randomization, blinding where possible. What makes an experiment publishable vs. anecdotal.
- **Statistics fundamentals:** mean, standard deviation, t-tests, ANOVA, confidence intervals. You don't need a statistics degree — you need enough to know whether your results are real or noise.
- **Plant growth metrics:** relative growth rate (RGR), net assimilation rate, specific leaf area, root-to-shoot ratio, chlorophyll content. These are your measurement toolkit.
- **Carbon fixation deep dive:** RuBisCO kinetics and its oxygenase problem (photorespiration), carbon concentrating mechanisms in C4 and CAM plants, the Calvin-Benson cycle in detail, photorespiratory bypass strategies being researched.
- **Stomatal biology:** how stomata regulate CO₂ uptake vs. water loss, the genes controlling stomatal density and aperture (EPF/EPFL family, SLAC1), and how stomatal traits affect water-use efficiency and carbon gain.
- **Soil carbon and root biology:** how root architecture, exudates, and mycorrhizal associations affect carbon sequestration. A different angle on "carbon capture" that's often overlooked.

### Resources

- **Plant Physiology** (Taiz, Zeiger, Møller, Murphy) — Chapters on photosynthesis, respiration, and growth analysis. The definitive reference.
- **Khan Academy Statistics** — Covers the essentials: distributions, hypothesis testing, confidence intervals.
- **Experimental Design for Biologists** (David Glass) — Short, practical book on designing valid experiments.
- **The Photosynthesis chapter from Biochemistry** (Berg/Stryer) — Deep molecular view of the Calvin cycle and RuBisCO mechanism.
- **RIPE Project publications** — Read 3–5 key papers on SBPase overexpression, photorespiratory bypass, and stomatal optimization.

### Hands-On Projects

- **Duckweed growth rate experiment:** Set up a controlled growth experiment with Lemna minor. Vary CO₂ concentration (ambient vs. supplemented with carbonated water or a CO₂ source), light intensity, or nutrient levels. Measure frond count and fresh weight daily. Calculate relative growth rate. This is your first real quantitative experiment.
- **Stomatal density survey:** Use clear nail polish leaf impressions to count stomata per mm² across different species or growth conditions. Correlate with growth rate data. Cheap, informative, and directly relevant to carbon uptake.
- **Chlorophyll extraction and quantification:** Extract chlorophyll in acetone or DMSO, measure absorbance if you have a spectrophotometer (a basic one is ~$100–200), and compare across conditions. Chlorophyll content is a useful proxy for photosynthetic capacity.
- **Selective breeding pilot:** Grow a population of Brassica rapa (Wisconsin Fast Plants, 35-day lifecycle). Measure biomass accumulation under controlled conditions. Select the top 10% fastest growers for the next generation. Run 2–3 generations. This teaches quantitative genetics through direct experience and demonstrates that natural variation in carbon fixation traits exists and is selectable.
- **Build a measurement notebook:** Start a rigorous digital lab notebook (Benchling, Jupyter notebooks, or a simple spreadsheet). Record every measurement, condition, and observation. Graph your data. Practice writing results as you would in a paper.

### Milestone

You have run at least two controlled experiments with proper replication, performed basic statistical analysis on your data, and can articulate specific hypotheses about which carbon fixation genes or traits you'd want to investigate further. You understand the difference between photosynthetic rate, growth rate, and carbon sequestration.

---

## Phase 4: Computational Skills & Bioinformatics

**Duration:** Months 8–10
**Goal:** Build the computational skills to analyze genomes, identify CRISPR targets, and work with publicly available datasets. Your CachyOS setup gives you a natural advantage here.

### Study Topics

| Topic | Details |
|-------|---------|
| Python fundamentals | Variables, loops, file I/O, pandas for data analysis, matplotlib for plotting. Enough to automate your lab data analysis and parse sequence files. |
| Biopython | Parse FASTA/GenBank files, run BLAST searches programmatically, extract gene annotations. Your bridge between biology and code. |
| Genome browsers | NCBI, Ensembl Plants, TAIR (Arabidopsis), Phytozome. Finding gene sequences, expression data, and annotations for carbon fixation genes. |
| RNA-seq data analysis | Using publicly available datasets from NCBI GEO to identify which photosynthesis genes are most variable across species or conditions. This is how you find targets. |
| Pathway analysis | KEGG, Plant Metabolic Network (PMN). Map carbon fixation pathways and identify rate-limiting steps computationally. |
| Guide RNA design | PAM sequences, on-target scoring, off-target analysis. Tools: CRISPOR, Benchling, Cas-OFFinder. Learn this now even if you don't use CRISPR immediately. |
| Comparative genomics | Compare carbon fixation gene variants between C3 and C4 species. Look at natural variation in RuBisCO, SBPase, and stomatal genes across the plant kingdom. |

### Resources

- **Rosalind.info** — Interactive bioinformatics problems. Start with the Bioinformatics Stronghold. Gamified and genuinely educational.
- **Bioinformatics Data Skills** (Vince Buffalo) — Practical guide to command-line bioinformatics, especially good for Linux users.
- **Python for Biologists** (Martin Jones) — Gentle intro that goes from zero to Biopython.
- **CRISPOR.tefor.net** — Free gRNA design tool. Upload your target sequence and get scored guides.
- **Benchling.com** — Free for individuals. Sequence editor, cloning planner, and CRISPR guide designer.
- **NCBI GEO Datasets** — Free RNA-seq data from thousands of plant experiments. Search for photosynthesis, carbon fixation, or stomatal development datasets.

### Hands-On Projects

- **BLAST the rbcL sequence you amplified in Phase 2.** Identify species, compare to C4 plant variants, look at amino acid differences in the active site.
- **Map the Calvin cycle computationally.** Use KEGG to pull the full carbon fixation pathway for Arabidopsis. Identify every enzyme, find their gene IDs, and note which ones have been shown to be rate-limiting in the literature.
- **Analyze a public RNA-seq dataset.** Download a dataset comparing high-light vs. low-light grown Arabidopsis. Identify which carbon fixation genes are differentially expressed. This is original analysis.
- **Design guide RNAs for your top target genes.** Pick 2–3 carbon fixation genes (SBPase, EPFL9, carbonic anhydrase). Use CRISPOR to design guides, score them, check off-targets. Even if you never order them, this exercise teaches the full target-to-guide pipeline.
- **Write an analysis script.** Automate your duckweed growth data analysis from Phase 3. Calculate RGR, plot growth curves, run t-tests — all in Python. Combine your wet lab and computational skills.

### Milestone

You can navigate genomics databases to find any gene of interest, analyze expression data to identify candidate targets, design and score CRISPR guides, and have written scripts that process your own experimental data. You have a ranked list of carbon fixation gene targets with rationale for each.

---

## Phase 5: Carbon Capture Research

**Duration:** Months 11–14
**Goal:** Conduct original experiments on carbon fixation in plants. Test hypotheses identified in Phase 4 using the quantitative and computational tools you've built.

This is where the plan diverges most from a traditional CRISPR curriculum. Instead of editing genes, you're doing real plant biology research — asking questions, designing experiments, and generating data that could genuinely contribute to the field.

### Research Directions (Pick 1–2)

- **Natural variation in carbon fixation efficiency.** Grow multiple accessions (genetic variants) of Arabidopsis or duckweed under identical conditions. Measure growth rate, biomass, stomatal density, and chlorophyll content. Identify the highest performers and use your bioinformatics skills to look for genetic differences in carbon fixation genes between fast and slow growers. This is essentially a genome-wide association study at a hobbyist scale.
- **Stomatal density manipulation.** Grow plants under varying CO₂ concentrations and light intensities. Measure how stomatal density changes in response. Correlate with growth rates. This addresses a live research question: can we predict optimal stomatal density for a given environment?
- **CO₂ enrichment response curves.** Measure duckweed growth across a range of dissolved CO₂ concentrations. At what point does additional CO₂ stop helping? This tells you about the saturation point of carbon fixation machinery — and whether the bottleneck is CO₂ supply or enzyme capacity.
- **Selective breeding for biomass accumulation.** Continue the Brassica rapa or duckweed selection experiment from Phase 3 for 5–10 more generations. Track response to selection. Genotype selected vs. unselected lines using PCR of candidate genes. This is classical quantitative genetics applied to carbon capture.
- **Root and soil carbon exploration.** Compare root mass, architecture, and soil organic carbon content across different plant species or growing conditions. This requires different measurement approaches (root scanning, loss-on-ignition for soil carbon) but addresses a critically important aspect of carbon sequestration.

### Measurement Toolkit

| Measurement | Method | Cost |
|-------------|--------|------|
| Growth rate | Frond count, fresh/dry weight, imaging analysis | ~$0 (scale + camera) |
| Stomatal density | Nail polish impressions + microscope | ~$50–150 (microscope) |
| Chlorophyll content | Acetone extraction + spectrophotometer | ~$100–200 |
| Photosynthetic proxy | Leaf disc float assay (O₂ evolution rate) | ~$5 per experiment |
| Chlorophyll fluorescence | Cheap fluorimeters or DIY with LED + photodiode | ~$50–300 |
| Root architecture | Flatbed scanner + ImageJ analysis | ~$0 (software is free) |
| Soil organic carbon | Loss-on-ignition (muffle furnace or kiln) | ~$50–100 |
| Genotyping | PCR + gel electrophoresis (already built) | ~$10–20 per run |

### Sharing Your Work

- **Preprint servers:** bioRxiv accepts submissions from independent researchers. If your experiments are well-designed and well-documented, you can publish your findings.
- **DIYbio community:** Present at community lab meetings, post on forums, share protocols on Protocols.io.
- **Citizen science platforms:** Contribute to projects tracking plant responses to environmental change.
- **Open notebooks:** Publish your lab notebook online (GitHub, Open Science Framework). Transparency builds credibility.

### Milestone

You have completed at least one original research project with proper experimental design, quantitative measurements, statistical analysis, and documented results. You can articulate a specific gene target for CRISPR editing based on evidence from your own experiments and the literature, not just because a protocol told you to.

---

## Phase 6 (Optional): CRISPR & Plant Transformation

**Duration:** Months 15–18
**Goal:** Apply CRISPR-Cas9 to edit a specific carbon fixation gene, guided by everything you've learned. This phase is optional — you may find that your research from Phase 5 takes you in a different direction entirely, and that's fine.

### Why This Phase Comes Last

By now you can answer the three critical questions that most DIY CRISPR experimenters can't: What gene should I edit and why? What phenotype do I expect? How will I measure whether the edit worked? That context transforms CRISPR from a novelty into a research tool.

### Study Topics

- **CRISPR-Cas9 mechanism:** how Cas9 creates double-strand breaks, NHEJ vs. HDR repair pathways, why most home experiments produce knockouts (loss of function) rather than precise edits.
- **Delivery methods:** Agrobacterium-mediated transformation, floral dip (Arabidopsis-specific), protoplast transfection, biolistics.
- **Selection and screening:** antibiotic/herbicide markers, PCR genotyping, T7 endonuclease assay, Sanger sequencing.
- **Plant regeneration:** callus induction, shoot regeneration, hormone ratios (auxin:cytokinin), hardening off.
- **RNP vs. plasmid approaches:** RNP delivery leaves no foreign DNA. Simpler legally, conceptually cleaner.

### Recommended First Edit

Before targeting carbon fixation genes, validate your technique with a visible marker. Target PDS3 (phytoene desaturase) in Arabidopsis — knockout produces albino sectors that you can see with your eyes. Once you've confirmed you can edit a gene successfully, move to your carbon fixation target.

### Suggested Carbon Fixation Targets

| Gene | Edit Strategy | Expected Effect |
|------|---------------|-----------------|
| EPFL9/Stomagen | Overexpression or knockout to modify stomatal density | Altered CO₂ uptake; measurable via stomatal counts and growth rate |
| SBPase | Promoter swap for overexpression | Potentially 30–40% increase in carbon fixation (shown in published research) |
| Carbonic anhydrase | Overexpression to concentrate CO₂ near RuBisCO | Improved carbon fixation under low CO₂ conditions |
| PLGG1 | Knockout to block photorespiratory glycolate transport | Reduced carbon loss to photorespiration (synthetic bypass) |

### Floral Dip Workflow (Arabidopsis)

1. Clone your gRNA + Cas9 into a binary vector (or order pre-made from Addgene)
2. Transform the vector into Agrobacterium tumefaciens (strain GV3101)
3. Grow Agrobacterium culture to OD600 ~0.8
4. Resuspend in infiltration media (5% sucrose + 0.05% Silwet L-77)
5. Dip Arabidopsis inflorescences for 30 seconds
6. Harvest seeds, select on antibiotic plates (T1 generation)
7. Genotype T1 plants by PCR + sequencing to confirm the edit
8. Phenotype: measure growth rate, stomatal density, or other metrics from your Phase 5 toolkit
9. Grow to T2 to segregate out the transgene, leaving only the edit

### Equipment for This Phase

| Item | Purpose | Approx. Cost |
|------|---------|-------------|
| Micropipettes (P20, P200, P1000) | Precise liquid handling | $150–300 (used set) |
| Microcentrifuge | Pelleting bacteria, DNA prep | $100–200 (used) |
| Incubator/shaker (37°C) | Growing Agrobacterium/E. coli | $100–300 (used) |
| Reagents (plasmid, antibiotics, media) | Per-experiment consumables | $50–150 (after initial stock) |
| Sanger sequencing service | Confirming edits | $5–15 per sample |

Note: pressure cooker, still-air box, PCR thermocycler, and gel rig are already in your lab from earlier phases. The incremental cost for CRISPR is lower than starting from scratch.

### Milestone

You have performed a successful gene edit in Arabidopsis, confirmed by PCR and sequencing, and measured the phenotypic effect using the quantitative methods from your earlier research. You can connect your molecular result to a biological question about carbon fixation.

---

## Community & Continued Learning

### Communities

- **DIYbio.org** — Global directory of community biolabs and mailing lists.
- **r/biohacking and r/labrats** (Reddit) — Active communities for troubleshooting.
- **BioCurious / Genspace** — Community biolabs with equipment and mentorship.
- **iGEM** — Competition wikis are treasure troves of protocols and project ideas.
- **Protocols.io** — Shared, versioned lab protocols from working researchers.
- **Plant carbon capture Twitter/Mastodon** — Follow researchers at RIPE, Salk Institute's Harnessing Plants Initiative, and CRoPS (Cambridge) for the latest publications.

### Long-Term Directions

- **Multiplexed editing:** target multiple carbon fixation genes simultaneously.
- **Base editing and prime editing:** precise single-nucleotide changes without double-strand breaks.
- **Synthetic carbon-concentrating mechanisms:** transplanting cyanobacterial CCM components into plants (active RIPE research area).
- **Crop species:** move beyond Arabidopsis to tomato, tobacco, poplar, or rice.
- **Enhanced root carbon deposition:** engineering deeper roots and more recalcitrant root exudates for long-term soil carbon storage (Salk's Ideal Plants initiative).
- **Collaboration:** your data and skills may be valuable to academic labs. Reach out to researchers whose work you've been reading.

---

## Final Notes

This plan is designed to make you a better researcher, not just a better protocol-follower. The quantitative biology and computational skills in Phases 3–5 are what separate someone who can ask interesting questions from someone who can only follow instructions.

Carbon capture in plants is one of the most important research areas of our time, and it's genuinely open to contributions from non-institutional researchers. The tools are accessible, the data is public, and the questions are far from settled. A well-designed experiment from a home lab that produces clean data on stomatal density, growth rates, or natural variation in photosynthetic efficiency is a real contribution.

Document everything. Be patient with failure. And remember — if this stops being fun, you're doing it wrong. The best science comes from genuine curiosity, and that's something no institution has a monopoly on.
