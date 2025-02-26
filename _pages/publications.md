---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
## Numerical Modelling of Material Characteristics of Hybrid BNC Nanocomposites
This study explores the mechanical properties of aluminum nanocomposites reinforced with hybrid boron nitride-carbon (BN-C) nanosheets using molecular dynamics simulations. The findings reveal that interfacial mechanics play a crucial role in load-carrying capacity, with BN-C nanofibers achieving the highest Young’s modulus (76.48 GPa) under realistic loading conditions. Tensile resistance is maximized when nanofibers are aligned with the principal loading axis (0°), and thermal stability improves with higher BN concentration. These insights contribute to the design of stronger, more heat-resistant nanocomposites.

Article: [V. Vijayaraghavan and L. Zhang, JOM 72, 2305–2311 (2020)](https://link.springer.com/article/10.1007/s11837-020-04031-9).

## Design of ANN Search Models for Predicting the Efficiency of Floatation Process
This study develops a computational model using the Automated Neural Network Search (ANNS) approach to predict the efficiency of oil-sand separation via floatation. The model accurately captures the impact of input parameters, with global sensitivity analysis identifying sand particle size as the most influential factor. This approach offers a non-conventional, time-efficient alternative for optimizing the floatation process without extensive experimentation.

Article: [V. Vijayaraghavan et al., Measurement 137, 122–129 (2019)](https://www.sciencedirect.com/science/article/abs/pii/S0263224119300867).

## Integrated Machine Learning Models for Surface Characterization of Aerospace Components
This study presents a novel data analytics model integrating Gene Expression Programming and Adaptive Neuro-Fuzzy Inference System to accurately predict mass finishing process behavior. The model outperforms conventional approaches in capturing complex interactions between process variables. Tribological analysis highlights process time and media type as key factors for optimal surface finish. This approach enables parameter optimization without extensive experimentation, saving time and materials.

Article: [V. Vijayaraghavan and S. Castagne, Measurement 115, 279-287, (2018)](https://www.sciencedirect.com/science/article/abs/pii/S0263224117306899).

## Optimization of Inconel 718 Turning Process using FEA based Genetic Programming
This study introduces a combined finite element and genetic programming model to optimize the turning process of Inconel 718, a challenging material due to its poor machinability. Finite element modeling predicts cutting forces, while genetic programming establishes mathematical relationships between process variables. Analysis reveals that depth of cut and cutting angle significantly influence cutting force, with tool angle optimization offering potential power savings. These findings contribute to more sustainable machining of hard-to-machine materials.

Article: [V. Vijayaraghavan et al., Journal of Cleaner Production 137, 1619–1627, (2016)](https://www.sciencedirect.com/science/article/abs/pii/S0959652616302694).




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
