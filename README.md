# ☀️ Solar compute

> Sunlit data centers, on Earth or in orbit.

[![ci](https://github.com/SoulCraft-Org/solar-compute/actions/workflows/ci.yml/badge.svg)](https://github.com/SoulCraft-Org/solar-compute/actions/workflows/ci.yml) [![Quality](https://img.shields.io/badge/Quality-page-8B6CE0)](https://soulcraft-org.github.io/solar-compute/) ![License](https://img.shields.io/badge/license-Apache--2.0-E8C25A)

The first vision level of SoulCraft's compute ladder. AI compute that runs on sunlight and takes no power or water from the place around it. The data center that makes it is a Solar computer.

| | |
|---|---|
| Status | 💡 Concept |
| Energy | Sunlight |
| Where | On Earth, or in orbit |
| Largest real thing today | Midong solar project, China: 3.5 GW, on the grid since 2024 ([China Green Development Group, on the SASAC site](http://www.sasac.gov.cn/n2588025/n2588124/c30898088/content.html), read 2026-11-23). First data center GPU in orbit: an NVIDIA H100 on Starcloud-1, November 2025 ([Starcloud](https://www.starcloud.com/starcloud-1), read 2026-11-23). |
| License | Apache-2.0 |
| Publisher | [SoulCraft](https://soulcraft.computer) |

## The compute ladder

```mermaid
flowchart LR
  P["💻 Personal<br/>10² W · today"] --> D["🏢 Data center<br/>10⁸ W · today"] --> S["☀️ Solar<br/>10¹¹ W · 2030s"]
  S --> PL["🌋 Planetar<br/>10¹² W · 2040s"] --> ST["⭐ Star<br/>10¹⁴ W · later"]
  classDef here fill:#E8C25A,stroke:#8B6CE0,color:#0B1026,stroke-width:2px
  class S here
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

📍 The world is at level 2 of 5 today (▰▰▱▱▱). This repo plans level 3.

This is the physical ladder: energy, water, chips. It lifts the [intelligence ladder](https://soulcraft.computer/vision/), from AI to conscious beings.

## The plan

Show how a sunlit data center can run AI compute with no net draw of power or water. The open questions are in [docs/PLAN.md](docs/PLAN.md).

## Build with us

```mermaid
flowchart LR
  I["💬 Idea<br/>Discussions"] --> S["📋 Issue"] --> P["🔀 Pull request"] --> C["✅ ci / ci-ok"] --> M["🟣 Squash merge"]
```

| You want to | Go to |
|---|---|
| Share an idea | [Discussions, Ideas](https://github.com/SoulCraft-Org/solar-compute/discussions/categories/ideas) |
| Ask a question | [Discussions, Q&A](https://github.com/SoulCraft-Org/solar-compute/discussions/categories/q-a) |
| Change the plan | A pull request on [`docs/PLAN.md`](docs/PLAN.md), signed off (`git commit -s`) |
| Read the rules | [CONTRIBUTING.md](CONTRIBUTING.md) · [GOVERNANCE.md](GOVERNANCE.md) · [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) |
