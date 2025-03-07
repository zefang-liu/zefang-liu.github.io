---
layout: archive
title: "About Me"
permalink: /
author_profile: true
redirect_from:
  - /about/
---

{% include base_path %}

Hello! I'm a data scientist at JPMorganChase, specializing in machine learning, natural language processing, and large language models. With a Ph.D. in Nuclear Engineering and a M.S. in Computational Science and Engineering from Georgia Tech, I bring interdisciplinary approaches to solving complex problems. My work focuses on applying advanced machine learning techniques across various domains, including cybersecurity, supply chains, and plasma physics.

## Work Experience

* Applied AI ML Associate Sr, JPMorganChase, 2022 - Present
* Applied AI & Machine Learning Summer Associate, JPMorganChase, 2021

## Education

* Ph.D. in Nuclear Engineering, Georgia Institute of Technology, 2018 - 2022
* M.S. in Computational Science and Engineering, Georgia Institute of Technology, 2018 - 2021
* M.S. in Aerospace Engineering, Georgia Institute of Technology, 2016 - 2018
* B.E. in Energy and Power Engineering, Shandong University, 2012 - 2016

## Publications

<ul>
    {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
    {% endfor %}
</ul>

## Academic Service

* Reviewer: NeurIPS'24 Workshop (ML4PS, FM4Science), AAAI'25 Workshop (MARW), ICLR'25 & Workshop, IJCNN'25.
