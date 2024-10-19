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

(Warning: This paper is currently still in draft form, and will be continually revised)

[Download paper here](../files/weightone.pdf)

### Constructing vector-valued automorphic forms on unitary groups
##### joint with Thomas L. Browning, Pavel Coupek, Ellen Eischen, Claire Frechette, Serin Hong and David Marcil

In this paper, we extend ideas of Clery-van der Geer in the Siegel case to construct autormphic forms on unitary Shimura varieties via differential operators.

[Download paper here](../files/AWS.pdf)

### Torsion vanishing for some Shimura varieties
##### joint with Linus Hamann

In this paper, we extend the results of Caraiani-Scholze and show torsion vanishing of l-adic étale cohomology of some PEL type Shimura varieties. 

[Download paper here](../files/torsion.pdf)

### Semisimplicity of étale cohomology for some Shimura varieties

In this paper, I show that some part of the étale cohomology of some abelian type Shimura varieties is semisimple as a Galois representation.

[Download paper here](../files/semi.pdf)

### Eichler-Shimura relations for Shimura varieties of Hodge type

In this paper, I show the Eichler-Shimura congruence relations for a large class of Shimura varieties of Hodge type, confirming a conjecture of Blasius-Rogawski. This is the main result of my PhD thesis.

[Download paper here](../files/es.pdf)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
