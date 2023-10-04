---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

1. C. Chandre, J. Pablo Salas, Nonlinear dynamics of molecular superrotors, Physical Review A 107, 063105 (2023)
1. C. Chandre, A. Horikoshi, Classical Nambu brackets in higher dimensions, Journal of Mathematical Physics 64, 052702 (2023)
1. C.S. Martins, C. Taveneau, G. Castro-Linares, M. Baibakov, N. Buzhinsky, M. Eroles, V. Milanović, S. Omi, J.-D. Pedelacq, F. Iv, L. Bouillard, A. Llewellyn, M. Gomes, M. Belhabib, M. Kuzmić, P. Verdier-Pinard, S. Lee, A. Badache, S. Kumar, C. Chandre, S. Brasselet, F. Rico, O. Rossier, G.H. Koenderink, J. Wenger, S. Cabantous, M. Mavrakis, Human septins organize as octamer-based filaments and mediate actin-membrane anchoring in cells, Journal of Cell Biology 222, e202203016 (2023); (featured in the Mechanobiology 2023 collection of JCB, featured in the Structural Biology 2023 collection of JCB; featured as a Spotlight in the March issue of JCB)
1. A.P. Bustamante, C. Chandre, Numerical computation of critical surfaces for the breakup of invariant tori in Hamiltonian systems, SIAM Journal on Applied Dynamical Systems 22, 483 (2023)
1. C. Chandre, B.A. Shadwick, Four-field Hamiltonian fluid closures of the one-dimensional Vlasov-Poisson equation, Physics of Plasmas 29, 102101 (2022)
1. F. Mauger, A.S. Folorunso, K.A. Hamer, C. Chandre, M.B. Gaarde, K. Lopata, K.J. Schafer, Charge migration manifests and attosecond solitons in conjugated organic molecules, Physical Review Research 4, 013073 (2022)
1. E. Floriani, J. Dubois, C. Chandre, Bogolyubov's averaging theorem applied to the Kramers-Henneberger Hamiltonian, Physica D 431, 133124 (2022)
1. J. Dubois, M. Jorba-Cuscó, À. Jorba, C. Chandre, Dynamical organization of recollisions by a family of invariant tori, SIAM Journal on Applied Dynamical Systems 21, 523 (2022)
1. C. Chandre, B.A. Shadwick, Hamiltonian fluid reduction of the 1.5D Vlasov-Maxwell equations, Physics of Plasmas 28, 092114 (2021) 



{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
