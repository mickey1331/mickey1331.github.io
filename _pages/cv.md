---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!-- 说明：下面每个 TODO 都是单独的一条注释，填写时把对应注释整行删掉即可；
     暂不需要的小节整段删除。
     Publications / Talks / Teaching 三节会自动从
     _publications、_talks、_teaching 目录生成，不需要手写。 -->

Contact
======
* 邮箱：[mickey1331@sjtu.edu.cn](mailto:mickey1331@sjtu.edu.cn)（学校）
* 备用邮箱：[3197959894@qq.com](mailto:3197959894@qq.com)
* GitHub：[github.com/mickey1331](https://github.com/mickey1331)

Education
======
* 上海交通大学，计算机专业（永强班），本科在读（大二）
  <!-- TODO: 补上入学年份，例如：2024 年入学，预计 2028 年毕业 -->

Research interests
======
* 自然语言需求描述 → 形式化规约 → 可证明正确的程序代码生成（NL2Spec）
* 形式规约合成（formal specification synthesis）、程序合成与形式化验证
  <!-- TODO: 可继续补充更细的方向，例如代码大模型、交互式定理证明等 -->

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
  <!-- TODO: 如熟悉构建与实验工具链可补充，例如 Git、Linux、LaTeX、PyTorch、Coq / Dafny 等 -->

Projects
======
  <!-- TODO: 课程项目、开源项目、竞赛作品等
* 项目名称（附 GitHub 链接）
  * 技术栈：……
  * 说明：……
  -->

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
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Awards and honors
======
* NeurIPS 2026 论文接收（合作作者）：SpecBridge: Learning Natural-Language Formalization Plans for the Formal Specification Synthesis Task
* 美国大学生数学建模竞赛（MCM/ICM）参赛
* 智能体黑客松（Agent Hackathon）参赛
* 欧莱雅美妆黑客松大赛参赛
  <!-- TODO: 可补充各竞赛的年份与奖项名次；没有名次的可以只写参赛 -->

Service and leadership
======
  <!-- TODO: 学生工作、志愿服务等；没有可整段删除 -->
