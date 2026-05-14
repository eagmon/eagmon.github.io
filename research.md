---
layout: page
title: Research Areas
permalink: /research/
---

#### Compositional Systems Biology
<div style="display: flex; flex-direction: column; align-items: flex-start;">
  <!-- Text Section -->
  <div style="padding: 10px; width: 100%;">
    <p>Compositional Systems Biology is our approach to building infrastructure for integrative biological modeling: a generalizable architecture for composing multiscale simulations from modular models with transparent data flow.</p>
    <p>Our infrastructure development focuses on:</p>
    <ul>
      <li><strong>Composition Framework</strong>: a standard for connecting heterogeneous processes through modular interfaces and orchestration patterns.</li>
      <li><strong>Composition Schema</strong>: a unified format for defining models, data structures, and process interactions, supporting reproducibility and automated composition.</li>
      <li><strong>Compositional Software</strong>: open-source tools for simulation runtime, schema validation, model annotation, and API-based deployment.</li>
      <li><strong>Biological Interface Definitions</strong>: standard schemas for cells, molecules, and environments, keeping simulations consistent and extensible.</li>
      <li><strong>Collaborative Modeling Infrastructure</strong>: shared registries that let research groups reuse modular components across domains.</li>
    </ul>
    <p>The goal is to reduce the friction of building and sharing complex biological models, creating an open ecosystem where multiscale simulations evolve through contributions from many research groups.</p>
    <p>This infrastructure is being built as <strong>Vivarium 2.0</strong>, a redesign of the Vivarium framework around the process bigraph formalism. It introduces a typed schema system and composition engine that make models easier to define, validate, compose, and visualize. The core software is developed openly across <a href="https://github.com/vivarium-collective/process-bigraph">process-bigraph</a> (the composition engine), <a href="https://github.com/vivarium-collective/bigraph-schema">bigraph-schema</a> (the type and schema system), and <a href="https://github.com/vivarium-collective/bigraph-viz">bigraph-viz</a> (visualization of composite models).</p>
    <p>The approach rests on a formal foundation: process bigraphs give a rigorous mathematical account of how heterogeneous processes share state and compose, keeping combined models well-defined. See the <a href="https://raw.githubusercontent.com/eagmon/eagmon.github.io/master/files/ProcessBigraphSupplement2025.pdf">Process Bigraph Supplemental Materials</a> for the formal treatment.</p>
  </div>
  <!-- Figure Section -->
  <div style="padding: 10px; width: 100%;">
    <img src="/images/metamodeler_overview.png" 
         alt="Metamodeler Overview" style="width: 100%; height: auto;">
  </div>
  <!-- Guiding Principles Posters -->
  <div style="padding: 10px; width: 100%;">
    <p>Two illustrated guides set out the principles behind this work. <em>The Ten Commandments of Computational Cell Biology</em> covers the modeling discipline behind each component; <em>Community-Based Assembly of Whole-Cell Models</em> describes how independently-built models combine into whole-cell understanding through shared interfaces and communal use.</p>
    <div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center;">
      <figure style="flex: 1 1 45%; min-width: 280px; margin: 0; text-align: center;">
        <img src="/images/ten_commandments_cell_biology.png"
             alt="The Ten Commandments of Computational Cell Biology" style="width: 100%; height: auto;">
        <figcaption style="font-size: 0.9em; padding-top: 6px;">The Ten Commandments of Computational Cell Biology — <a href="/images/ten_commandments_cell_biology.png" download>Download</a></figcaption>
      </figure>
      <figure style="flex: 1 1 45%; min-width: 280px; margin: 0; text-align: center;">
        <img src="/images/constitutional_modeling.png"
             alt="Community-Based Assembly of Whole-Cell Models" style="width: 100%; height: auto;">
        <figcaption style="font-size: 0.9em; padding-top: 6px;">Community-Based Assembly of Whole-Cell Models — <a href="/images/constitutional_modeling.png" download>Download</a></figcaption>
      </figure>
    </div>
  </div>
</div>


#### <i>E. coli</i> Whole-cell Model
<div style="display: flex; flex-direction: column; align-items: flex-start;"> 
  <div style="width: 100%; padding: 10px;"> 
    <p>
        We are developing a mechanistic model of <i>E. coli</i> that integrates gene regulation, metabolism, and cellular physiology across molecular, cellular, and population scales. With over 19,000 parameters, it predicts gene expression, metabolite levels, protein interactions, and whole-cell properties such as biomass and growth rate.
    </p>
    <p>
        We use the model as a discovery tool to:
    </p>
    <ul>
      <li><strong>Complete functional annotations</strong> by predicting the roles of uncharacterized genes from simulation–data comparisons.</li>
      <li><strong>Capture population heterogeneity</strong> by simulating variation in growth and physiology across thousands of cells.</li>
      <li><strong>Model environmental context</strong> by testing how nutrients and stressors shape adaptation and behavior.</li>
      <li><strong>Enable simulation-based inference</strong> using probabilistic and ML methods for parameter estimation and experimental design.</li>
    </ul>
    <p>By unifying diverse data in an extensible simulation, the model supports systems-level reasoning and discovery in microbial physiology.</p>
  </div> 
  <div style="width: 100%; padding: 10px;"> 
      <video autoplay loop muted playsinline style="width: 100%; height: auto;" controls>
        <source src="https://raw.githubusercontent.com/eagmon/eagmon.github.io/master/images/morowitz.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
  </div>
</div>




#### Ocean Microbiome
<div style="display: flex; flex-wrap: wrap; align-items: flex-start;">
  <div style="flex: 1 1 60%; padding: 10px;">
    <p>We connect genome-scale metabolic models of ocean bacteria and plankton to biogeochemical models of the water column, quantifying how microbial activity affects climate. This work includes:</p>
    <ul>
      <li><strong>Metabolic Modeling</strong>: detailed models of microbial metabolism in ocean bacteria and plankton.</li>
      <li><strong>Biogeochemical Integration</strong>: linking these models to water-column cycles to assess nutrient and carbon fluxes.</li>
      <li><strong>Climate Impact</strong>: quantifying how microbial carbon sequestration and nutrient cycling influence climate.</li>
    </ul>
    <p>This work is conducted in collaboration with the Center for Chemical Currencies of a Microbial Planet at the Woods Hole Oceanographic Institution.</p>
  </div>
</div>

#### Gut Microbiome
<div style="display: flex; flex-wrap: wrap; align-items: flex-start;">
  <div style="flex: 1 1 60%; padding: 10px;">
    <p>Our gut microbiome research, led by PhD students and undergraduates in the lab, builds a spatial dynamical model of the human intestines. Areas include:</p>
    <ul>
      <li><strong>Ecological Niches</strong>: mapping intestinal niches, their microbial communities, and the spatially structured environment shaped by peristaltic flow.</li>
      <li><strong>Microbial Community Interactions</strong>: how microbes interact and coexist, from molecular networks to whole-gut physiology, including microbe–host interactions such as mucus production by goblet cells.</li>
      <li><strong>Layered Complexity</strong>: addressing the hierarchical structure and diverse interactions of the gut microbiome.</li>
      <li><strong>Dynamic Modeling</strong>: starting from stoichiometric models, then adding multi-species interactions and processes like digestion, absorption, and peristalsis.</li>
      <li><strong>Multi-Omics Data Integration</strong>: incorporating multi-omics data into spatial models of the gut environment.</li>
    </ul>
    <p>The goal is to integrate these datasets and uncover the microbial interactions that drive gut health and disease.</p>
  </div>
</div>
