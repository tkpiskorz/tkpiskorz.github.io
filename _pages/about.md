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

I am a post-doc at prof. [Fernanda Duarte group](fduargegroup.org), where I work on understaning self-assembly of coordination complexes. 


Before starting this position, I worked on my Ph.D. in the [Advance Soft Matter group](https://www.linkedin.com/company/advanced-soft-matter-tu-delft/) at TU Delft under the supervision of prof. Jan van Esch (Advance Soft Matter (ASM) group) and dr. Alex de Vries ([molecular dynamics (MD) group](https://www.rug.nl/research/molecular-dynamics/) at the University of Groningen). My Ph.D. thesis is entitled "[Molecular modeling of supramolecular structures](https://doi.org/10.4233/uuid:2c876b61-a850-4ae1-b47d-38a60a576006)."

Research Intrest
------
The main focus of my research is understanding the self-assembly process, i.e., processes which rely on spontaneous organization of small molecular block into complex structures. For me, the most fascinating fact about these systems is that the whole complex structure is encoded in a single molecular block. Although this would imply that we can obtain a desirable structure by careful design of the molecular block, this is hard to achieve due we know little about these processes.

In my work, I use computational methods to give insights into these processes since experimental methods face limitations. I am the most interested in combining different approaches, such as quantum mechanics, empirical simulations (i.g., MD), and data science (cheminformatics), to create reliable models for chemical systems, which could guide work in the lab towards better products.

During my Ph.D., I have been using different flavors of molecular dynamics (all-atomistic, coarse-grained, and rare-event sampling methods), and I have been using these techniques to study supramolecular and polymer systems. Besides working in ASM and MD groups, I had the opportunity to go to Glasgow and work in [Tuttle Lab](http://tuttlelab.com/) on peptide-based supramolecular systems and go to Lyon to the [Laboratoire Polymères et Matériaux Avancés of Solvey](https://www.lpma-research.com/en/index.html) to work on multiscale simulations of polymers.  Before starting my Ph.D., I studied at [College of MISMaP](http://mismap.uw.edu.pl/) at Warsaw University, from which I have gained M.Sc. degree in chemistry. As for the thesis itself, I wrote it in [biophysical chemistry group](http://groups.ichf.edu.pl/ochab) at the Polish Academy of Science, where I developed Monte Carlo simulations and a model of fluorescent correlation spectroscope (FCS).

In my spare time, I do outdoor activities (hiking, running and beach volleyball), play games (board or video games), or play on bass guitar in a band.

Other
------
If you have any question about my research, collaboration just drop me <a href="mailto:{{ author.email }}">an e-mail</a>.
