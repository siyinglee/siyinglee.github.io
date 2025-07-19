---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

### p-isogenies with G-structure
##### joint with Keerthi Madapusi

We construct stacks of p-isogenies with G-structure over Shimura varieties of abelian type at hyperspecial level.

(in preparation)

### Unramifiedness of weight one representations for Hilbert modular varieties 

In this paper, I show that if the residual degree is odd, then the mod p Galois representation attached to a Hecke eigenclass in the higher coherent cohomology of the Hilbert modular variety in weight one is unramified at p.

(Under revision)

### Constructing vector-valued automorphic forms on unitary groups
##### joint with Thomas L. Browning, Pavel Coupek, Ellen Eischen, Claire Frechette, Serin Hong and David Marcil

In this paper, we extend ideas of Clery-van der Geer in the Siegel case to construct autormphic forms on unitary Shimura varieties via differential operators.

[Link](../files/AWS.pdf)
[arXiv](https://arxiv.org/abs/2408.05198)

### Torsion vanishing for some Shimura varieties
##### joint with Linus Hamann

In this paper, we extend the results of Caraiani-Scholze and show torsion vanishing of l-adic étale cohomology of some PEL type Shimura varieties. 

[Link](../files/torsion.pdf)
[arXiv](https://arxiv.org/abs/2309.08705)

### Semisimplicity of étale cohomology for some Shimura varieties

In this paper, I show that some part of the étale cohomology of some abelian type Shimura varieties is semisimple as a Galois representation.

[Link](../files/semi.pdf)
[arXiv](https://arxiv.org/abs/2206.07283)

### Eichler-Shimura relations for Shimura varieties of Hodge type

In this paper, I show the Eichler-Shimura congruence relations for a large class of Shimura varieties of Hodge type, confirming a conjecture of Blasius-Rogawski. This is the main result of my PhD thesis.

[Link](../files/es.pdf)
[arXiv](https://arxiv.org/abs/2006.11745)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
