---
layout: page
title: 머신러닝을 위한 기초 수학 및 프로그래밍 실습
description: >-
    Course policies and information.
---

# 머신러닝을 위한 기초 수학 및 프로그래밍 실습
Basic Mathematics and Programming Practice for Machine Learning

M2177.005800
> This course aims to understand the fundamental principles of complex systems and apply them through mathematics and programming. Mathematical understanding serves as a tool to clearly explain complex phenomena, while programming involves implementing these principles in a logical sequence. Students will learn how to bring their ideas to life through computer programming, providing an opportunity to explore and understand the essence of complex systems. The course will cover real-world data from fields such as nature, industry, and healthcare, with hands-on practice using interactive generative AI to derive meaningful results. Ultimately, the learning experience will extend to understanding the mechanisms of the human mind. This course is open to students of all majors, encouraging collaboration in multidisciplinary teams to tackle challenging problems that may be difficult to solve individually. Through this course, students will develop the ability to logically analyze and solve complex problems, learning how to creatively address various real-world challenges by utilizing programming and mathematics.

- __Location__: Bld 43-101
- __Lecture__: Monday 9:00 - 12:00
  
## Teaching Assistants
{% assign teaching_assistants = site.staffers | where: 'role', 'ta_basic_machine_learning' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

---

## References
- 아라키 마사히로, 만화로 쉽게 배우는 머신러닝, 성안당

## Grading
- Attendance: 5%
- Assignment: 40%
- Final exam: 30%
- Final project: 15%
- Final report: 5%
- Attitude: 5%

## Assignments
- homework1: Motion of Stars
- homework2: Classification of chest X-ray images
  - [ChestX-ray paper](https://openaccess.thecvf.com/content_cvpr_2017/papers/Wang_ChestX-ray8_Hospital-Scale_Chest_CVPR_2017_paper.pdf)
  - [ChestX-ray dataset](https://nihcc.app.box.com/v/ChestXray-NIHCC/folder/36938765345)    
- homework3: TBD
- homework4: TBD
    

## Lecture Schedule

| Week | Date | Lecture | 
|:-------------------:|:-------------------:|-------------------------------------------------------------|
| 1 | 3/7 | Course introduction and Axiomatic system Axiomatic system <br /> from the structure of the Universe to the structure of thought. <br /> _Programming practice: Installation and first programming._ |
| 2 | 3/14 | Retrogradation <br /> Retrograde motion in the sky, Function, Derivative, Chain-rule, Retrograde signal in a cell <br /> _Programming practice: Basic python programming practice_ |
| 3 | 3/21 | Optimization and Regression <br /> Optimization frameworks, Gradient descent method and Convexity, Non-linear optimization, Monte Carlo Method, Linear regression <br /> _Programming practice: Random number generation, Gradient descent method, Monte Carlo method._ |
| 4 | 3/28 | Analytical geometry <br /> Mathematical modeling of neurons, From Euclidean geometry to analytical geometry, Occam's razor <br /> _Programming practice: Training binary operations_ |
| 5 | 4/4 | Linear Algebra and Associative memory <br /> Fundamentals on Vector, Fundamentals on Matrix, Associate memory <br /> _Programming practice: Vector class, vector calculation, matrix operation_ |
| 6 | 4/11 | Dimensionality reduction – 1/ Team meeting #1 <br /> Dimensionality reduction in linear transformation, Dimensional reduction in Perceptron <br />_Programming practice:  MNIST classification_ |
| 7 | 4/18 | Dimensionality reduction – 2 <br /> Eigen vector/value, Principal Component Analysis, Singular Vector Decomposition <br /> _Programming practice: Eigen vector/value, PCA with MNIST_ |
| 8 | 4/25 | Distance / One-page idea proposal <br /> Euclidean distance, Minkowski distance, Distance in general space, Autoencoder, Event Horizon Telescope <br /> _Programming practice: Autoencoder_ |
| 9 | 5/2 | Randomness in Machine Learning <br /> Randomness, Gaussian distribution, Randomness in Encoder|
| 10 | 5/9 | Distance in probability / Project planning <br /> Kullback-Leibler Divergence, Decision Tree, Ensemble, Bagging, Boosting, and Random forest. |
| 11 | 5/16 | Distance in time <br /> Prediction in time, Distance in time, Map of meanings | 
| 12 | 5/23 | Final Exam / Team meeting #2 | 
| 13 | 5/30 | Symmetry in Machine Learning <br /> Recommendation, Measure of Intelligence, Incompleteness theorems, Symmetry in Universe and Intelligence |
| 14 | 6/13 | Peer-to-peer review | 
| 15 | 6/20 | Final project presentation and exhibition | 

## Final PT
- XAICON 2025 [TBA]
- [XAICON 2023](https://sites.google.com/view/xaicon2023)
- [XAICON 2022](https://sites.google.com/view/xaicon2022)
- [XAICON 2021](https://sites.google.com/view/xaicon2021)
- [XAICON 2020](https://sites.google.com/view/xaicon2020)
- [XAICON 2019](https://sites.google.com/view/xaicon2019)
