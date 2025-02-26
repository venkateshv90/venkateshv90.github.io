---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Publication

# Analytical Modelling of Mechanical Characteristics of Hybrid BNC Nanocomposites #

This study explores the mechanical properties of aluminum nanocomposites reinforced with hybrid boron nitride-carbon (BN-C) nanosheets using molecular dynamics simulations. The findings reveal that interfacial mechanics play a crucial role in load-carrying capacity, with BN-C nanofibers achieving the highest Young’s modulus (76.48 GPa) under realistic loading conditions. Tensile resistance is maximized when nanofibers are aligned with the principal loading axis (0°), and thermal stability improves with higher BN concentration. These insights contribute to the design of stronger, more heat-resistant nanocomposites.

Article: V. Vijayaraghavan and L. Zhang, JOM 72, 2305–2311 (2020).


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
