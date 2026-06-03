# Se-Cd-Fe Iron Plaque Research Radar

A Codex skill for tracking, screening, and synthesizing research frontiers around rice selenium-cadmium co-occurrence, root iron plaque, rhizosphere microbiomes, SynCom construction, DGT/DCB/BCR methods, and safe utilization of Se-rich Cd-risk paddy soils.

This skill was designed for the doctoral research direction:

> Microbe- and iron plaque-mediated selenium biofortification and cadmium mitigation in rice grown in Se-Cd co-occurring red soils of southern Jiangxi, with mechanisms and synthetic community construction for safe utilization.

## What It Can Do

- Build daily or weekly research radar reports for recent Se-Cd-Fe, rice iron plaque, SynCom, and safe-utilization papers.
- Deep dive into papers and translate them into experiment design ideas.
- Create related-work outlines grouped by mechanism chain.
- Design hydroponic, pot, field, or literature-derived data studies.
- Build variable extraction frameworks for DGT, DCB, BCR, Se speciation, pH/Eh, grain Se/Cd/As, yield, and safety-window modelling.
- Generate publishable thesis or paper ideas with hypotheses, indicators, risks, and target article types.

## Install

Copy this folder into your Codex skills directory:

```text
~/.codex/skills/se-cd-iron-plaque-research-radar
```

Then invoke it in Codex with:

```text
$se-cd-iron-plaque-research-radar 帮我做一份最近两周水稻 Se-Cd-Fe 铁膜方向的研究雷达周报。
```

## Structure

```text
se-cd-iron-plaque-research-radar/
├── SKILL.md
├── agents/
│   └── openai.yaml
├── evals/
│   └── evals.json
└── references/
    └── frontier-radar.md
```

## Example Prompts

```text
$se-cd-iron-plaque-research-radar 帮我查最近两周 Se-Cd-iron plaque 水稻方向的新论文，给我周报。
```

```text
$se-cd-iron-plaque-research-radar 深挖一篇 SynCom 降镉促生水稻论文，转成我的实验设计启发。
```

```text
$se-cd-iron-plaque-research-radar 围绕 DGT/DCB/Se 形态帮我设计一篇数据文章的变量提取框架。
```

## Notes

For latest or recent literature requests, the assistant should verify publication dates and cite links. For adjacent topics, it should explicitly explain the transfer path to the rice Se-Cd-Fe iron-plaque system.
