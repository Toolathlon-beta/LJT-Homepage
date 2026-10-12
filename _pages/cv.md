---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computer Science, Hong Kong University of Science and Technology (HKUST), 2024-Present
* B.Eng., Shanghai Jiao Tong University (SJTU), 2020-2024

Work experience
======
* February 2025 - Present: Research Intern at MINIMAX
* June 2024 - September 2024: Research Intern at Tencent WXG
  * Advisor: Zifei Shan
* June 2023 - December 2023: Research Intern at Shanghai AI Lab
  * Advisor: Prof. Yu Cheng

Skills
======
* Natural Language Processing
* Machine Learning
* Large Language Models (LLM Reasoning and Reinforcement Learning, LLM Truthfulness and Interpretability)
* Vision-Language Models (Hallucination)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
