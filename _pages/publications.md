---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---


Journal Papers
======
- **C. Ozturk**, F. Lind, D. Guo, R. Berry and M. Honig, "Pushing spectrum boundaries: coexistence with passive Sensing," (Working Paper),
- **C. Ozturk**, D. Guo, R. Berry and M. Honig, "Downlink spectral efficiency of low earth orbit satellite mega-constellations," **IEEE Journal on Selected Areas in Communications**, 2023 (Under Review).
- **C. Ozturk**, M. F. Keskin, V. Sciancalepore, H. Wymeersch and S. Gezici, “[RIS-aided localization under pixel failures](https://browse.arxiv.org/pdf/2302.04436.pdf),” **IEEE Transactions on Wireless Communications**, 2023 (Under Review).
- **C. Ozturk**,  M. F. Keskin, H. Wymeersch and S. Gezici, "[RIS-aided near-field localization under phase-dependent amplitude variations](https://ieeexplore.ieee.org/abstract/document/10017173)," in **IEEE Transactions on Wireless Communications**, vol. 22, no. 8, pp. 5550-5566, Aug. 2023.
- E.M. Abadi, C. Goken, **C. Ozturk**, and S. Gezici, "[Optimal power allocation and optimal linear encoding for parameter estimation in the presence of a smart eavesdropper](https://ieeexplore.ieee.org/abstract/document/9855400)," in **IEEE Transactions on Signal Processing**, vol. 70, pp. 4093-4108, 2022, doi: 10.1109/TSP.2022.3198180.
- **C. Ozturk**, C. Goken and S. Gezici, “[Parameter encoding for ECRB minimization in the presence of jamming](https://ieeexplore.ieee.org/abstract/document/9647943),” **IEEE Signal Processing Letters**, vol. 29, pp. 419-423, 2022.
- **C. Ozturk**, and S. Gezici, “[Eavesdropper and jammer selection in wireless source localization networks](https://ieeexplore.ieee.org/abstract/document/9495265),” **IEEE Transactions on Signal Processing**, vol. 69, pp. 4341-4356, 2021.
- **C. Ozturk**, H. M. Ozaktas, S. Gezici, and A. Koc “[Optimal fractional Fourier filtering for graph signals](https://ieeexplore.ieee.org/abstract/document/9435933),” **IEEE Transactions on Signal Processing**, vol. 69, pp. 2902-2912, May 2021.
- B. Dulek, **C. Ozturk**, and S. Gezici, “[Optimal decision rules for simple hypothesis testing under general criterion involving error probabilities](https://ieeexplore.ieee.org/abstract/document/8957537),” **IEEE Signal Processing Letters**, vol. 27, pp. 261-265, Jan. 2020.
- M. F. Keskin, **C. Ozturk**, S. Bayram, and S. Gezici, “[Jamming strategies in wireless source localization systems](https://ieeexplore.ieee.org/abstract/document/8680666),” **IEEE Wireless Communication Letters**, vol. 8, no. 4, pp. 1141-1145, Aug. 2019.
- **C. Ozturk**, B. Dulek and S. Gezici, “[Convexity properties of detection probability for noncoherent detection of a modulated sinusoidal carrier](https://ieeexplore.ieee.org/abstract/document/8494789),” **IEEE Transactions On Vehicular Technology**, vol.67, no. 12, pp. 12410-12415, Dec. 2018.

Conference Papers and Workshops
=====
- **C. Ozturk**, D. Guo, R. Berry and M. Honig, “Downlink Spectral Efficiency of Low Earth OrbitSatellite Mega-Constellations,” **Information Theory and Applications Workshop (ITA)**, San Diego, CA, USA, Feb 12-17, 2023, (Poster Presentation).
- **C. Ozturk**, M. F. Keskin, H. Wymeersch and S. Gezici, “[On the impact of hardware impairments on RIS-aided localization](https://ieeexplore.ieee.org/abstract/document/9838889),” **IEEE International Conference on Communications (ICC)**, Seoul, South Korea, May 16-20, 2022.
- **C. Ozturk**, and S. Gezici, “[Anchor placement in TOA based wireless localization networks via convex relaxation](https://ieeexplore.ieee.org/abstract/document/9527822),” IEEE International Black Sea Conference on Communications and Networking (BlackSeaCom), Bucharest, Romania, May 24-28, 2021.
- **C. Ozturk** and S. Gezici, “[Eavesdropper selection strategies in wireless source localization networks](https://ieeexplore.ieee.org/abstract/document/9148683)”, **IEEE International Conference on Communications (ICC)**, Dublin, Ireland, June 7-11, 2020.




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
