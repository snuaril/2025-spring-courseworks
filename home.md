---
layout: home
title: 2025 Spring Courseworks
nav_exclude: true
permalink: /:path/
---

# 2025 Spring Courseworks
Courseworks in 2025 spring, Autonomous Robot Intelligence Lab
- [고급 디지털 제조 및 실습](./digital_fabrication.md)(Advanced Digital Fabrication and Practice, M2866.004200)
- [머신러닝을 위한 기초 수학 및 프로그래밍 실습](./basic_machine_learning.md)(Basic Mathematics and Programming Practice for Machine Learning, M2177.005800)
- [제조를 위한 인공지능](./ai_for_manufacturing.md)(Artificial Intelligence for Manufacturing, M2866.004300)
  
## Instructor
{% assign instructors = site.staffers | where: 'role', 'instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
