---
title: Research
nav:
  order: 1
  tooltip: Research areas
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research areas

We work on computational materials science at the intersection of artificial intelligence and atomistic modeling, with an emphasis on the predictive design of functional materials. We develop AI-accelerated frameworks that enable efficient and systematic exploration of high-dimensional materials design spaces. Our methodology combines deep reinforcement learning, machine-learned interatomic potentials, and automated simulation workflows to advance atomistic modeling and simulation for materials discovery.
We seek to understand and predict materials formation, structural evolution, and functional behavior, while addressing fundamental questions related to chemical bonding, materials processing, and ion and defect transport.
We apply these computational approaches to a broad range of materials systems, including electronic materials for heterojunctions, ionic conductors for energy storage applications, and heterogeneous (electro)catalysts.

{% include section.html %}

## Agentic computational workflows

{% capture text %}

Leveraging large language models, we develop scientific AI agents for automated computational workflows. Our goal is to facilitate materials screening and discovery by integrating databases, machine learning models, and high-throughput pipelines. These agentic workflows are applied to problems in energy, sustainability, and electronic materials.

{% endcapture %}

{%
  include feature.html
  image="images/research/research_areas1.svg"
  text=text
  fit="cover
%}

{% include section.html %}

## Agentic atomistic simulation

{% capture text %}

We develop agentic atomistic simulation frameworks that overcome the timescale and sampling limitations of conventional atomistic methods. By coupling machine-learned interatomic potentials (MLIPs) with reinforcement learning, we enable efficient exploration of atomic transition pathways. These approaches are applied to diverse materials phenomena, including ion transport in ionic conductors, phase transformations, and materials processing processes such as thermal annealing.

{% endcapture %}

{%
  include feature.html
  image="images/research/research_areas2.svg"
  flip=true
  style="bare"
  text=text
  fit="cover
%}

{% include section.html %}

## Atomic-level mechanism understanding

{% capture text %}

We employ first-principles (ab initio) calculations to uncover atomic-scale mechanisms governing materials behavior. Electronic structure theory, chemical bonding analysis, and ab initio thermodynamics are combined to elucidate reaction mechanisms and establish quantitative structure–property relationships.

{% endcapture %}

{%
  include feature.html
  image="images/research/research_areas3.png"
  style="bare"
  text=text
  fit="cover
%}