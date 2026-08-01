---
layout: page
title: Software
permalink: /software/
---

We build **Vivarium** — an open-source ecosystem for integrative, multi-scale biological modeling, built on the **process bigraph** formalism: a typed schema system and composition engine that make models easy to define, validate, compose, run, and explore. Everything below is developed openly under the [Vivarium Collective](https://github.com/vivarium-collective).

#### Start here

The two main entry points into the ecosystem — a browser workbench and an AI-agent toolkit.

- [**vivarium-workbench**](https://github.com/vivarium-collective/vivarium-workbench) — the browser-based workbench for Vivarium workspaces: build, run, and explore composites, simulations, studies, and investigations, and discover the ecosystem through a built-in Marketplace.
- [**viva-superpowers**](https://github.com/vivarium-collective/viva-superpowers) — a Claude Code plugin of skills and workflows for building and driving Vivarium research projects with AI agents.

#### Framework

The core of Vivarium 2.0 — the engine and schema system everything else builds on.

- [**process-bigraph**](https://github.com/vivarium-collective/process-bigraph) — the composition engine that runs Processes, Steps, and Composites with transparent, typed data flow.
- [**bigraph-schema**](https://github.com/vivarium-collective/bigraph-schema) — the typed schema system for defining models, state, and interfaces ([docs](https://vivarium-collective.github.io/bigraph-schema/)).

For the formal foundation, see [*Foundations of a Compositional Systems Biology*](https://arxiv.org/abs/2408.00942), [*Process Bigraphs and the Architecture of Compositional Systems Biology*](https://arxiv.org/abs/2512.23754), and the [Process Bigraph Supplemental Materials](https://raw.githubusercontent.com/eagmon/eagmon.github.io/master/files/ProcessBigraphSupplement2025.pdf).

#### Tools

Shared tooling for building, sharing, and running composite models.

- [**viva-template**](https://github.com/vivarium-collective/viva-template) — scaffold for starting a new process-bigraph research workspace.
- [**viva-marketplace**](https://github.com/vivarium-collective/viva-marketplace) — the ecosystem registry (`modules.json`) and aggregated artifact index — composites, processes, studies, and investigations across every repo — that powers the workbench Marketplace.
- [**viva-emitters**](https://github.com/vivarium-collective/viva-emitters) — interchangeable data emitters (XArray / Zarr / Parquet).
- [**viva-basic-processes**](https://github.com/vivarium-collective/viva-basic-processes) — reusable building blocks such as clocks, interventions, and math expressions.

#### Models &amp; Applications

Biological models built on the framework.

- [**v2ecoli**](https://github.com/vivarium-collective/v2ecoli) — a whole-cell model of *E. coli* integrating gene regulation, metabolism, and physiology across molecular, cellular, and population scales ([live dashboard](https://vivarium-collective.github.io/v2ecoli/dashboard)).
- [**3d-ecoli**](https://github.com/vivarium-collective/3d-ecoli) — a spatial, 3D whole-cell model of *E. coli* ([live 3D viewer](https://pub-eb913fbbdc584bd7add047c823570b13.r2.dev/viewer/index.html?models=https://pub-eb913fbbdc584bd7add047c823570b13.r2.dev/ecoli-3d/viz/3d/models.json)).
- [**spatio-flux**](https://github.com/vivarium-collective/spatio-flux) — spatial flux-balance and reaction–diffusion composites for cells in their environments ([demo](https://vivarium-collective.github.io/spatio-flux/)).
- [**vivarium-tyssue**](https://github.com/vivarium-collective/vivarium-tyssue) — process-bigraph integration of [tyssue](https://github.com/DamCB/tyssue) for epithelial tissue mechanics.
- [**viva-munk**](https://github.com/vivarium-collective/Viva-munk) — multi-cell simulations with 2D physics, growing and dividing cells in shared chemical environments ([demos](https://vivarium-collective.github.io/Viva-munk/)).
- [**viva-biomodels**](https://github.com/vivarium-collective/viva-biomodels) — cross-engine comparison of ~900 curated BioModels across multiple simulators ([live site](https://vivarium-collective.github.io/biomodels-comparison/)).

Browse everything at the [Vivarium Collective on GitHub](https://github.com/vivarium-collective).
