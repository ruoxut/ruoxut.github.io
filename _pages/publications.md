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

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

(*\* denotes the corresponding author.*)

## Journal Articles

1. Tan, R.\* (2023). Nonparametric regression with nonignorable missing covariates and outcomes using bounded inverse weighting. *Journal of Nonparametric Statistics*, to appear. [[DOI]](https://doi.org/10.1080/10485252.2023.2215341) [[Code]](https://github.com/ruoxut/MissingBothXY)
2. Delaigle, A. and Tan, R.\* (2023). Group testing regression analysis with covariates and specimens subject to missingness. *Statistics in Medicine*, 42, 731-744. [[DOI]](http://doi.org/10.1002/sim.9640) [[Code]](https://github.com/ruoxut/GroupTestingBothMissing)
3. Tan, R.\*, Zang, Y. and Yin, G. (2023+). Nonlinear dimension reduction for functional data with application to clustering. *Statistica Sinica*, to appear. [[PDF]](https://www3.stat.sinica.edu.tw/ss_newpaper/SS-2021-0393_na.pdf) [[Code]](https://github.com/ruoxut/FunctionalManifoldLearning)
4. Delaigle, A. and Tan, R.\* (2023+). Group testing regression analysis with missing data and imperfect tests. *Statistica Sinica*, to appear. [[PDF]](https://www3.stat.sinica.edu.tw/ss_newpaper/SS-2021-0382_na.pdf) [[Code]](https://github.com/ruoxut/GroupTestingMissingD)

## Submitted Papers

1. Tan, R., Huang, W.\*, Zhang, Z. and Yin, G. (2023+). Causal effect of functional treatment. [[arXiv]](https://arxiv.org/abs/2210.00242)
2. Tan, R.\* and Yin, G. (2023+). Model averaging for manifold learning.
3. Gu, J., Tan, R.\* and Yin, G. (2023+). Delaunay weighted two-sample test for high-dimensional data by incorporating geometric information.

## Other Works

1. Tan, R.\* (2021). Nonparametric techniques with missing data. *PhD Thesis*. [[URL]](http://hdl.handle.net/11343/276263)
