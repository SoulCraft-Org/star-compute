# ⭐ Star compute

> Fusion: unlimited energy for it and everything around.

[![ci](https://github.com/SoulCraft-Org/star-compute/actions/workflows/ci.yml/badge.svg)](https://github.com/SoulCraft-Org/star-compute/actions/workflows/ci.yml) [![Quality](https://img.shields.io/badge/Quality-page-8B6CE0)](https://soulcraft-org.github.io/star-compute/) ![License](https://img.shields.io/badge/license-Apache--2.0-E8C25A)

The top level of SoulCraft's compute ladder. AI compute powered by fusion, with energy to spare for everything around it. The data center that makes it is a Star computer. In time, Sage is trained and run here.

| | |
|---|---|
| Status | 💡 Concept |
| Energy | Fusion |
| Where | Beside a fusion plant |
| Largest real thing today | First ARC fusion plant: about 400 MW, early 2030s. This is a forecast by its builder ([Commonwealth Fusion Systems, ARC](https://cfs.energy/technology/arc/), read 2026-11-23). |
| License | Apache-2.0 |
| Publisher | [SoulCraft](https://soulcraft.computer) |

## The compute ladder

```mermaid
flowchart LR
  P["💻 Personal<br/>10² W · today"] --> D["🏢 Data center<br/>10⁸ W · today"] --> S["☀️ Solar<br/>10¹¹ W · 2030s"]
  S --> PL["🌋 Planetar<br/>10¹² W · 2040s"] --> ST["⭐ Star<br/>10¹⁴ W · later"]
  classDef here fill:#E8C25A,stroke:#8B6CE0,color:#0B1026,stroke-width:2px
  class ST here
```

| Level | Power | Energy | Power and water | When |
|---|---|---|---|---|
| 💻 Personal computer | about 10² W | wall socket | takes a little | today |
| 🏢 Data center | about 10⁸ W | the grid | takes both | today |
| ☀️ [Solar computer](https://github.com/SoulCraft-Org/solar-compute) | about 10¹¹ W | sunlight | neutral | 2030s |
| 🌋 [Planetar computer](https://github.com/SoulCraft-Org/planetar-compute) | about 10¹² W | Earth's heat | gives back | 2040s |
| ⭐ [Star computer](https://github.com/SoulCraft-Org/star-compute) | about 10¹⁴ W | fusion | gives plenty | later |

Source: the compute ladder on [soulcraft.computer](https://soulcraft.computer), read 2026-11-22. The last three levels are
vision estimates, scaled from the data center by power.

The bigger compute grows, the more it can give energy and water back instead of taking them.

📍 The world is at level 2 of 5 today (▰▰▱▱▱). This repo plans level 5.

This is the physical ladder: energy, water, chips. It lifts the intelligence ladder, from AI to conscious beings: [soulcraft.computer/vision/](https://soulcraft.computer/vision/)

## The plan

Show how fusion can power AI compute with energy to spare, at the scale Sage needs. The open questions are in [docs/PLAN.md](docs/PLAN.md).

## Build with us

```mermaid
flowchart LR
  I["💬 Idea<br/>Discussions"] --> S["📋 Issue"] --> P["🔀 Pull request"] --> C["✅ ci / ci-ok"] --> M["🟣 Squash merge"]
```

| You want to | Go to |
|---|---|
| Share an idea | [Discussions, Ideas](https://github.com/SoulCraft-Org/star-compute/discussions/categories/ideas) |
| Ask a question | [Discussions, Q&A](https://github.com/SoulCraft-Org/star-compute/discussions/categories/q-a) |
| Change the plan | A pull request on [`docs/PLAN.md`](docs/PLAN.md), signed off (`git commit -s`) |
| Read the rules | [CONTRIBUTING.md](CONTRIBUTING.md) · [GOVERNANCE.md](GOVERNANCE.md) · [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) |
