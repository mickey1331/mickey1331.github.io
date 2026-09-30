---
layout: archive
title: "CV"
permalink: /cv/
lang: zh
lang_url: /en/cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- 说明：Publications 一节由 _publications/ 目录自动生成，不需要手写。 -->

Contact
======
* 邮箱：[mickey1331@sjtu.edu.cn](mailto:mickey1331@sjtu.edu.cn)（学校）
* 备用邮箱：[3197959894@qq.com](mailto:3197959894@qq.com)
* GitHub：[github.com/mickey1331](https://github.com/mickey1331)

Education
======
* 上海交通大学，计算机专业（永强班），本科在读（大二）

Research interests
======
* 自然语言需求描述 → 形式化规约 → 可证明正确的程序代码生成（NL2Spec）
* 形式规约合成（formal specification synthesis）、程序合成与形式化验证

Advisors
======
* 林云（上海交通大学）
* 胡振江（北京大学）

Research experience
======
* 2026 年至今：SpecBridge —— 面向形式规约合成任务的自然语言形式化计划学习（合作作者，第一作者 Wenjie Zhang）
  * 上海交通大学，导师：林云、胡振江
  * 成果：论文 SpecBridge: Learning Natural-Language Formalization Plans for the Formal Specification Synthesis Task 被 NeurIPS 2026 接收
* 进行中：与上海光源（SSRF）的合作项目

Skills
======
* 编程语言：C++、Python；正在学习 Rust
* 形式化方法 / 证明助手：Lean

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% assign post_lang = post.lang | default: 'zh' %}
    {% if post_lang != page.lang %}{% continue %}{% endif %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Awards and honors
======
* NeurIPS 2026 论文接收（合作作者）：SpecBridge: Learning Natural-Language Formalization Plans for the Formal Specification Synthesis Task
* 2026 年美国大学生数学建模竞赛（ICM）Honorable Mention（荣誉提名）
* 智能体黑客松（Agent Hackathon）参赛
* 欧莱雅美妆黑客松大赛参赛
