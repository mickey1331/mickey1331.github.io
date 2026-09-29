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
* 上海交通大学，计算机专业，本科在读（大二）
  <!-- TODO: 补上入学年份，例如：2024 年入学，预计 2028 年毕业 -->

Research interests
======
* 自然语言需求描述 → 形式化规约 → 可证明正确的程序代码生成（NL2Spec）
  <!-- TODO: 可继续补充更细的方向，例如程序合成、形式化验证、代码大模型等 -->

Research experience
======
  <!-- TODO: 有科研/项目经历就按下面格式补上，没有可以先删掉这一节
* 2025 年 X 月至今：NL2Spec 相关研究
  * 上海交通大学某实验室 / 课题组
  * 负责内容：……
  * 指导老师：……
  -->

Projects
======
  <!-- TODO: 课程项目、开源项目、竞赛作品等
* 项目名称（附 GitHub 链接）
  * 技术栈：……
  * 说明：……
  -->

Skills
======
  <!-- TODO: 例如
* 编程语言：Python、C++、OCaml、Coq / Lean ……
* 工具：Git、Linux、LaTeX、PyTorch ……
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
  <!-- TODO: 奖学金、竞赛奖项等；没有可整段删除 -->

Service and leadership
======
  <!-- TODO: 学生工作、志愿服务等；没有可整段删除 -->
