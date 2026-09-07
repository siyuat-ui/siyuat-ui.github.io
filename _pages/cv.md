---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- You can replace this Markdown CV with a PDF: drop your file in /files/ and link it here, e.g. [Download my CV (PDF)](/files/cv.pdf) -->

Education
======
* Ph.D. in Statistics, University of Michigan, Ann Arbor, 2026 - present (expected [year])
* B.S. in Statistics, University of Science and Technology of China (USTC), GPA 4.00/4.30

Research interests
======
* Statistical network analysis
* Synthetic data generation for time series (reverse Markov learning, engression, LSTM encoder-decoder architectures, variational autoencoders)
* BIC-based model selection for latent class models (Monte Carlo simulation studies)

Research experience
======
* 2026 - present: Ph.D. Research, Department of Statistics
  * University of Michigan, Ann Arbor
  * Working on BIC-based model selection for latent class models and synthetic data generation methods for time series

Teaching experience
======
* Teaching Assistant, undergraduate statistics courses
  * University of Michigan, Ann Arbor
  * Designed lesson materials on correlation and causation, including interactive classroom activities, LaTeX Beamer presentations, and lesson plans
  * See the [Teaching](/teaching/) page for details

Skills
======
* Probability theory and statistical inference
* Theoretical statistics: exponential families, Gaussian processes, bootstrap methods
* Applied statistics: EHR data generation, logistic regression, correlation analysis
* Statistical computing and programming

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
