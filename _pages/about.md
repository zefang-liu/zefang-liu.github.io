---
layout: archive
title: "About Me"
permalink: /
author_profile: true
redirect_from:
  - /about/
---

{% include base_path %}

Hello! I'm a Data Scientist at JPMorgan Chase, specializing in machine learning, natural language processing, and large language models. With a Ph.D. in Nuclear Engineering and a M.S. in Computational Science and Engineering from Georgia Tech, I bring interdisciplinary approaches to solving complex problems. My work focuses on applying advanced machine learning techniques across various domains, including cybersecurity, supply chains, and plasma physics.

## Work Experience

* Applied AI ML Associate Sr, JPMorgan Chase, 2023 - Present
* Quantitative Research Associate, JPMorgan Chase, 2022 - 2023
* Applied AI & Machine Learning Summer Associate, JPMorgan Chase, 2021

## Education

* Ph.D. in Nuclear Engineering, Georgia Institute of Technology, 2022
* M.S. in Computational Science and Engineering, Georgia Institute of Technology, 2021
* M.S. in Aerospace Engineering, Georgia Institute of Technology, 2018
* B.E. in Energy and Power Engineering, Shandong University, 2016

## Publications

<ul>
    {% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
    {% endfor %}
</ul>
