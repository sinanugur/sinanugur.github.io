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


Sinan Uğur Umu, Hilde Langseth,Verena Zuber, Åslaug Helland, Robert Lyle and Trine B. Rounge, Serum RNAs can predict lung cancer up to 10 years prior to diagnosis (2022), eLife

Sinan Uğur Umu, Hilde Langseth, Andreas Keller, Eckart Meese, Åslaug Helland, Robert Lyle  and Trine B. Rounge (2019), A 10 year prediagnostic followup study shows that serum RNA signals are highly dynamic in lung carcinogenesis, Molecular Oncology

Umu, S. U., Langseth, H., Bucher-Johannessen, C., Fromm, B., Keller, A., Meese, E. and  Rounge, T. B. (2018). A comprehensive profile of circulating RNAs in human serum. RNA Biology, 15(2). https://doi.org/10.1080/15476286.2017.1403003

Umu, Sinan Ugur and Gardner, P. P. (2017). A comprehensive benchmark of RNA-RNA interaction prediction tools for all domains of life. Bioinformatics, btw728. doi.org/10.1093/bioinformatics/btw728

Umu, Sinan Ugur, Poole, A. M., Dobson, R. C., & Gardner, P. P. (2016). Avoidance of stochastic RNA interactions can be harnessed to control protein expression levels in bacteria and archaea. eLife, 5. doi.org/10.7554/eLife.13479


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
