# Frontier Radar Reference

Use this file when producing radar reports, paper deep dives, related work, experiment designs, variable extraction frameworks, or thesis/paper ideas for the Se-Cd-Fe iron-plaque doctoral line.

## Topic Taxonomy

### Main-Line Topics

- Se-Cd co-occurrence in rice and paddy soils.
- Southern Jiangxi/Gannan, Jiangxi, South China, acidic red soils, Se-rich soils, Cd-contaminated soils, and safe utilization of agricultural land.
- Rice root iron plaque, Fe plaque, iron oxide plaque, DCB extraction, DCB-Fe, DCB-Cd, DCB-Se, DCB-As, Fe/Mn plaque, root oxygen loss, rhizosphere oxidation, Fe(II)/Fe(III), pH/Eh.
- Selenium biofortification, cadmium mitigation, Se-Cd antagonism, selenite, selenate, organic Se, nano-Se, Se nanoparticles, foliar Se, soil Se, slow-release Se, grain Se, grain Cd.
- Rhizosphere microbiome, endophytes, functional strains, Se-transforming bacteria, Cd-immobilizing bacteria, siderophore, EPS, biofilm, IAA, phosphate solubilization, Fe cycling, mineralization, stress tolerance.
- SynCom, synthetic community, bottom-up design, microbial consortium, rice growth promotion, Cd remediation, Se enrichment, colonization, functional complementarity.
- DGT, BCR, sequential extraction, HPLC-ICP-MS, Se speciation, metal bioavailability, soil-rice transfer, safety window, risk assessment.

### Adjacent Topics

- Arsenic risk, Cd-As-Se interaction, water management, alternate wetting and drying, flooding, redox oscillation, pH amendment, lime, biochar, iron amendments, manganese oxides.
- Machine learning, meta-analysis, meta-regression, safety window modelling, interpretable ML, spatial modelling, climate constraints, NASA POWER, ERA5-Land, SoilGrids.
- Se-rich industry, agricultural safe utilization, rice quality, standards, policy, field demonstration, microbial fertilizer, soil conditioner.
- Other crops only when they offer a transferable Se-Cd-microbe, iron plaque, or SynCom mechanism.

### Default Low-Priority Topics

- Plant transporter studies with no soil/rhizosphere/iron-plaque link.
- Food processing or health products without agricultural safety relevance.
- Pure omics pipelines with no experimental design implications.
- Pure mine/industrial remediation unrelated to paddy rice safe production.

## Query Expansion

Combine one or more terms from each relevant group.

### Core English Terms

- selenium cadmium rice
- Se Cd rice paddy soil
- selenium biofortification cadmium mitigation rice
- selenium cadmium iron plaque rice
- rice root iron plaque selenium cadmium
- Fe plaque DCB selenium cadmium rice
- selenite selenate cadmium rice iron plaque
- Se-Cd co-occurring red soil rice
- selenium-rich cadmium-contaminated paddy soil

### Microbe and SynCom Terms

- rhizosphere microbiome selenium cadmium rice
- synthetic microbial community cadmium rice
- SynCom rice cadmium selenium
- Se-transforming bacteria cadmium immobilization
- selenium biofortification rhizosphere microbiome
- siderophore EPS cadmium immobilization rice
- iron cycling bacteria rice rhizosphere cadmium
- functional strains selenium cadmium paddy soil

### Method Terms

- DCB iron plaque rice selenium cadmium
- DGT selenium cadmium paddy soil rice
- BCR sequential extraction selenium cadmium soil
- HPLC ICP-MS selenium speciation rice
- Se speciation selenite selenate rice grain
- SEM EDS iron plaque rice root cadmium
- Feo Fed iron oxides paddy soil cadmium selenium

### Safety Window and Modelling Terms

- selenium biofortification safety window rice
- grain selenium cadmium risk rice meta-analysis
- selenium dose rice cadmium meta regression
- machine learning selenium cadmium rice
- climate constrained selenium biofortification rice
- pH Eh iron plaque selenium cadmium rice
- water management selenium cadmium arsenic rice

### Chinese Terms

- 水稻 硒 镉 铁膜
- 根表铁膜 硒 镉 水稻
- 硒生物强化 镉阻控 水稻
- 赣南 富硒 镉 红壤 水稻
- 硒镉共存 酸性红壤 稻田
- DCB 铁膜 硒 镉
- DGT 硒 镉 稻田
- 硒形态 水稻 HPLC ICP MS
- 根际微生物 硒 镉 水稻
- 合成菌群 SynCom 水稻 镉
- 安全利用 富硒 镉污染 稻田

## Screening Rules

Keep a candidate high priority when it satisfies at least two:

- Directly studies rice, paddy soil, iron plaque, or rhizosphere.
- Measures Se and Cd together, or Se/Cd plus As.
- Reports Fe/iron plaque, DCB, DGT, BCR, pH/Eh, Fe oxides, or Se speciation.
- Includes microbes, functional strains, SynCom, or colonization.
- Produces field, pot, hydroponic, or literature-derived data that can inform treatment design.
- Has a clear route to the user's thesis: mechanism, experiment, data article, or safe utilization.

Mark as adjacent when:

- It uses another crop but has transferable Se-Cd-microbe or SynCom logic.
- It focuses on As or water management but informs rice Se-Cd safety.
- It is a modelling/meta-analysis paper that can support safety-window framing.

Drop or down-rank when:

- It only reports grain Se increase without Cd/As/safety context.
- It is only about food processing after harvest.
- It lacks enough methodological detail to inform experiments.
- It is too far from rice/paddy/red soil/SynCom/iron plaque and has no clear transfer path.

## Scoring Rubric

Score each item from 0-5 on each dimension. Use the total to rank, but explain the decisive reason in words.

| Dimension | 0 | 3 | 5 |
|---|---|---|---|
| Main-line fit | Unrelated | Adjacent to Se/Cd/rice | Direct Se-Cd-Fe/rice/iron-plaque fit |
| Mechanism depth | Descriptive only | Some mechanism indicators | Clear pathway with Fe, Se/Cd, rhizosphere or plaque evidence |
| Method strength | Weak or unclear | Standard pot/field/lab methods | Strong design with DCB/DGT/speciation/omics/field validation |
| Safety value | No grain/risk endpoints | Cd or Se endpoint | Se target + Cd/As safety + yield/quality |
| Microbe/SynCom value | None | Microbiome association | Functional strains/SynCom/colonization/mechanism |
| Reproducibility | No details | Methods enough to repeat | Data/code/materials or highly clear protocol |
| Publishable potential | Low | Useful background | Can inspire a thesis chapter or paper |

Interpretation:

- 28-35: top pick; likely worth deep reading.
- 21-27: strong supporting item.
- 14-20: adjacent or background.
- Below 14: mention only if needed for context.

## Mechanism Chain

Use this chain to organize synthesis and experiment ideas:

```text
Microbes / SynCom
  -> Se transformation and Fe(II)/Fe(III) cycling
  -> rhizosphere pH/Eh, ROL, EPS, siderophore, biofilm
  -> root iron plaque amount, structure, and element loading
  -> Cd retention at root surface and Se allocation to plant/grain
  -> rice Se biofortification, Cd mitigation, yield, and safe utilization
```

## Mandatory Experiment Indicators

When designing experiments for this topic, include these unless clearly impossible:

- Soil: pH, Eh, organic matter, available Cd, available Se, Fe(II)/Fe(III), moisture or water regime.
- Iron plaque: DCB-Fe, DCB-Cd, DCB-Se; DCB-As when As risk matters.
- Plant: root/shoot/grain Cd and Se, biomass or yield, root morphology when relevant.
- Treatment: Se form and dose, Cd background, Fe or plaque induction treatment, microbial inoculation/SynCom, water management.
- Microbial: 16S or targeted community profiling, qPCR/strain tracking for inoculants, functional traits for isolated strains.

Strong additions:

- DGT-Cd/Se/Fe, BCR or Se fractionation, HPLC-ICP-MS Se speciation, SEM-EDS, ROL, Feo/Fed, EPS, siderophore, biofilm, IAA, phosphate solubilization, WGS of top strains, metagenomics/metatranscriptomics, As endpoint, climate or field covariates.

## Output Templates

### Radar Report

```markdown
# Se-Cd-Fe 铁膜研究雷达：[time window/topic]

## Executive Summary
- [frontier movement]
- [frontier movement]
- [frontier movement]

## Ranked Findings
| Rank | Title/Project | Source/Date | Label | System | Key Contribution | Evidence/Method | Code/Data/Materials | Score | Why It Matters |
|---:|---|---|---|---|---|---|---|---:|---|

## Top Picks
### 1. [Title]
- Source fact: [verified facts]
- Method: [design, indicators, data]
- Limitation: [limits]
- My inference: [how it can inspire user's topic]
- Experiment/article extension: [actionable idea]

## Research Ideas
| Idea | Hypothesis | Design | Key Indicators | Baselines | Risk | Target Article |
|---|---|---|---|---|---|---|

## Reading Queue
1. [paper/project + why]
```

### Paper Deep Dive

```markdown
# Paper Deep Dive: [Title]

## Why This Paper Matters
- Main-line/adjacent label:
- Direct connection to Se-Cd-Fe iron plaque:

## What The Paper Did
- System:
- Treatments:
- Measurements:
- Main findings:

## Method Lessons
- What can be copied:
- What needs adaptation:
- What should be avoided:

## Translation To My Topic
- Hypothesis:
- Proposed treatment design:
- Indicators:
- Expected results:
- Risks and fallback:
```

### Experiment Design

```markdown
# Experiment Design: [question]

## Research Question
[one sentence]

## Hypothesis
[mechanism hypothesis]

## Treatments
| Factor | Levels | Reason |
|---|---|---|

## Sampling And Measurements
| Stage | Sample | Mandatory indicators | Optional indicators |
|---|---|---|---|

## Data Analysis
- Primary outcomes:
- Mechanism tests:
- Safety-window endpoints:

## Risk Control
- If SynCom fails:
- If iron plaque signal is weak:
- If advanced instruments are unavailable:
- Minimum publishable dataset:
```

### Variable Extraction Framework

```markdown
# Variable Extraction Framework: [topic]

## Inclusion Criteria
- [criteria]

## Exclusion Criteria
- [criteria]

## Fields
| Group | Field | Unit/Format | Required | Notes |
|---|---|---|---|---|

## Derived Outcomes
- Se biofortification efficiency:
- Cd mitigation effect:
- Safety-window flag:
- Iron-plaque retention index:

## Quality Control
- Unit harmonization:
- Missing data:
- Duplicated experiments:
- Risk of bias:
```

### Thesis/Paper Idea Card

```markdown
## Idea: [title]
- Gap:
- Hypothesis:
- Design:
- Key indicators:
- Expected novelty:
- Minimum publishable version:
- Upgrade version:
- Main risk:
- Target venue/type:
```
