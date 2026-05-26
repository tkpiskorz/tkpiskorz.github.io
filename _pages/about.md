---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if page.author and site.data.authors[page.author] %}
  {% assign author = site.data.authors[page.author] %}{% else %}{% assign author = site.author %}
{% endif %}

I am a JSPS postdoctoral fellow in Prof. [Daniel Packwood's group](https://www.packwood.icems.kyoto-u.ac.jp/), where I work on understanding self-assembled structures and their applications in chemical biology.

Before, I worked as a postdoctoral researcher in [Fernanda Duarte's group](https://www.duartegroupchem.org/) at the University of Oxford. I earned my Ph.D. from TU Delft under the supervision of [Prof. Jan van Esch](https://www.tudelft.nl/en/faculty-of-applied-sciences/about-faculty/departments/chemical-engineering/principal-investigators/jan-van-esch/jan-van-esch-lab) and [dr. Alex de Vries](https://research.rug.nl/en/persons/alex-de-vries).

Research Intrest
------
My research explores how complex molecular systems work. In particular, I study how molecular interactions, organization, and reactivity give rise to function in systems relevant to recognition, separation, bioactivity, catalysis, and materials. By connecting molecular-level mechanisms with experimental observations, my work aims to build the understanding needed for prediction and design.

In my work, I use computational methods to understand complex chemical processes at the molecular level. I combine quantum chemical calculations, atomistic and coarse-grained molecular simulations, and machine learning to develop reliable models of chemical systems. I have extensive experience integrating computational modeling with experimental research to interpret observations, test hypotheses, and guide the design of improved chemical systems. 

If you have any question about my research/collaboration just drop me <a href="mailto:{{ author.email }}">an e-mail</a>.
