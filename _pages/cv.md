---
layout: archive
title: "CV"
permalink: /cv/
lang: en
lang_url: /zh/cv/
author_profile: true
redirect_from:
  - /en/resume
---

{% include base_path %}

<!-- Publications below are generated from the _publications/ collection (entries with lang: en). -->

Contact
======
* Email: [mickey1331@sjtu.edu.cn](mailto:mickey1331@sjtu.edu.cn) (university)
* Alternative email: [3197959894@qq.com](mailto:3197959894@qq.com)
* GitHub: [github.com/mickey1331](https://github.com/mickey1331)

Education
======
* Shanghai Jiao Tong University, Computer Science (Yongqiang Class), B.Eng. in progress (2nd year)

Research interests
======
* Natural-language requirements → formal specifications → provably correct program code (NL2Spec)
* Formal specification synthesis, program synthesis, formal verification

Advisors
======
* Yun Lin (Shanghai Jiao Tong University)
* Zhenjiang Hu (Peking University)

Research experience
======
* 2026 – present: SpecBridge — learning natural-language formalization plans for formal specification synthesis (co-author; first author: Wenjie Zhang)
  * Shanghai Jiao Tong University; advisors: Yun Lin, Zhenjiang Hu
  * Outcome: *SpecBridge: Learning Natural-Language Formalization Plans for the Formal Specification Synthesis Task* accepted at NeurIPS 2026
* Ongoing: collaboration project with the Shanghai Synchrotron Radiation Facility (SSRF)

Skills
======
* Programming languages: C++, Python; currently learning Rust
* Formal methods / proof assistant: Lean

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% assign post_lang = post.lang | default: 'en' %}
    {% if post_lang != 'en' %}{% continue %}{% endif %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Awards and honors
======
* NeurIPS 2026 paper acceptance (co-author): *SpecBridge: Learning Natural-Language Formalization Plans for the Formal Specification Synthesis Task*
* 2026 Interdisciplinary Contest in Modeling (ICM) — Honorable Mention
* Agent Hackathon
* L'Oréal Beauty Hackathon
