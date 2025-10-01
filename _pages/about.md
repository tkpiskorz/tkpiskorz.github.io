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

Before starting this position, I worked as a postdoctoral researcher in [Fernanda Duarte's group](https://www.duartegroupchem.org/) at the University of Oxford. I earned my Ph.D. from TU Delft under the supervision of [Prof. Jan van Esch](https://www.tudelft.nl/en/faculty-of-applied-sciences/about-faculty/departments/chemical-engineering/principal-investigators/jan-van-esch/jan-van-esch-lab) and [dr. Alex de Vries](https://research.rug.nl/en/persons/alex-de-vries) (University of Groningen). My Ph.D. thesis is entitled “[Molecular modeling of supramolecular structures](https://doi.org/10.4233/uuid:2c876b61-a850-4ae1-b47d-38a60a576006)."

Research Intrest
------
The primary focus of my research is understanding the self-assembly process, i.e., the spontaneous organization of small molecular blocks into complex structures. For me, the most fascinating fact about these systems is that the whole complex structure is encoded in a single molecular block. Although this implies that we can obtain a desirable structure by carefully designing the molecular block, achieving this is challenging because we have limited knowledge about these processes.

In my work, I utilize computational methods to gain insights into these processes, as experimental methods have limitations. I am most interested in combining different approaches, such as quantum mechanics, molecular simulations (particularly molecular dynamics), and machine learning, to create reliable models for chemical systems that can guide laboratory work towards better products.

If you have any question about my research/collaboration just drop me <a href="mailto:{{ author.email }}">an e-mail</a>.
