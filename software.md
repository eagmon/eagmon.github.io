---
layout: page
title: Software
permalink: /software/
---

We build **Vivarium** — an open-source ecosystem for integrative, multi-scale biological modeling. The current framework is organized around the **process bigraph** formalism: a typed schema system and composition engine that make models easy to define, validate, compose, and visualize. Everything below is developed openly under the [Vivarium Collective](https://github.com/vivarium-collective).

#### Framework

The core of Vivarium 2.0 — the engine and schema system everything else builds on.

- [**process-bigraph**](https://github.com/vivarium-collective/process-bigraph) — the composition engine that runs Processes, Steps, and Composites with transparent, typed data flow.
- [**bigraph-schema**](https://github.com/vivarium-collective/bigraph-schema) — the typed schema system for defining models, state, and interfaces ([docs](https://vivarium-collective.github.io/bigraph-schema/)).
- [**bigraph-viz**](https://github.com/vivarium-collective/bigraph-viz) — visualization of composite models and how their parts are wired together.

For the formal foundation, see [*Foundations of a Compositional Systems Biology*](https://arxiv.org/abs/2408.00942), [*Process Bigraphs and the Architecture of Compositional Systems Biology*](https://arxiv.org/abs/2512.23754), and the [Process Bigraph Supplemental Materials](https://raw.githubusercontent.com/eagmon/eagmon.github.io/master/files/ProcessBigraphSupplement2025.pdf).

#### Tools

Shared tooling for building, running, and exploring composite models.

- [**vivarium-dashboard**](https://github.com/vivarium-collective/vivarium-dashboard) — interactive dashboard for workspaces, composites, simulations, and investigations.
- [**pbg-template**](https://github.com/vivarium-collective/pbg-template) — scaffold for starting a new process-bigraph research workspace.
- [**pbg-superpowers**](https://github.com/vivarium-collective/pbg-superpowers) — skills and workflows for authoring and driving workspaces.
- [**pbg-emitters**](https://github.com/vivarium-collective/pbg-emitters) — interchangeable data emitters (XArray / Zarr / Parquet).
- [**pbg-basic-processes**](https://github.com/vivarium-collective/pbg-basic-processes) — reusable building blocks such as clocks, interventions, and math expressions.
- [**pbg-uq**](https://github.com/vivarium-collective/pbg-uq) — portable forward uncertainty quantification (polynomial chaos + Sobol).

#### Models &amp; Applications

Biological models built on the framework.

- [**v2ecoli**](https://github.com/vivarium-collective/v2ecoli) — a whole-cell model of *E. coli* integrating gene regulation, metabolism, and physiology across molecular, cellular, and population scales ([live dashboard](https://vivarium-collective.github.io/v2ecoli/dashboard)).
- [**3d-ecoli**](https://github.com/vivarium-collective/3d-ecoli) — a spatial, 3D whole-cell model of *E. coli* ([live 3D viewer](https://pub-eb913fbbdc584bd7add047c823570b13.r2.dev/viewer/index.html?models=https://pub-eb913fbbdc584bd7add047c823570b13.r2.dev/ecoli-3d/viz/3d/models.json)).
- [**spatio-flux**](https://github.com/vivarium-collective/spatio-flux) — spatial flux-balance and reaction–diffusion composites for cells in their environments ([demo](https://vivarium-collective.github.io/spatio-flux/)).
- [**parsimony**](https://github.com/vivarium-collective/parsimony) — spatial, mesh-based modeling of cell geometry and molecular crowding.
- [**biomodels-comparison**](https://github.com/vivarium-collective/pbg-biomodels) — cross-engine comparison of ~900 curated BioModels across multiple simulators ([live site](https://vivarium-collective.github.io/biomodels-comparison/)).

Browse everything at the [Vivarium Collective on GitHub](https://github.com/vivarium-collective).
