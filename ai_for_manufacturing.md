---
layout: page
title: 제조를 위한 인공지능
description: >-
    Course policies and information.
---

# 제조를 위한 인공지능
Artificial Intelligence for Manufacturing

M2866.004300
> The development of artificial intelligence technology that reproduces human intelligence with the same structure and principles is expected to bring innovation to the manufacturing sectors that have been outside the field of automation and computerization. This course aims to understand the fundamental principles, possibilities, and limitations of how artificial intelligence can be used to manufacture products. For this purpose, students will learn not only product inspection, forecasting and maintenance, but also theories, practical examples of specific artificial intelligence that can meet the demands in each manufacturing flow, including product design, material discovery and design, and manufacturing machinery.

- __Location__: Bld 38-429
- __Lecture__: Friday 13:00 - 15:50
  


## Co-Lecturer
{% assign teaching_assistants = site.staffers | where: 'role', 'ta_ai_for_manufacturing_co_lecturer' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
## Teaching Assistant
{% assign teaching_assistants = site.staffers | where: 'role', 'ta_ai_for_manufacturing' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

---

## Grading
- Attendance: 5%
- Assignment: 40%
- Final Exam: 25%
- Attitude: 5%
- Project: 25%

## Assignment
- Defective PCB Detection
  - [Reference Paper](https://www.nature.com/articles/s41597-024-03656-8)    
  - [Dataset](https://figshare.com/articles/dataset/DsPCBSD_/24970329?file=44069552)
- Classification of Vibration Signal
  - [Reference Paper](https://ieeexplore.ieee.org/document/9078761)
  - [Dataset](https://engineering.case.edu/bearingdatacenter/download-data-file)
- LLM with Digital Twin
  - [Reference Paper](https://ieeexplore.ieee.org/document/10710900)


## Lecture Schedule

| Week | Date | Lecture | 
|:-------------------:|:-------------------:|-------------------------------------------------------------|
| 1	|3/7	|Course opening<br /> - Manufacturing in the era of AI and Deep Learning: Status quo, potential and limitations<br /> - Historical overview of Human Intelligence, Artificial Intelligence and Deep Learning
| 2|	3/14|	Machine Learning and Optimization<br /> - Fundamental principle of Machine Learning<br /> - Linear/convex/non-linear optimization, Gradient Descent Method, Newton’s Method	
| 3|	3/21|	Neuron and Plasticity<br /> - Accelerated Gradient Method<br /> - Fundamentals on artificial neural networks: Hodgkin and Huxley, Relay/Perceptron<br /> - Understanding learning: Memory/Hippocampus/Plasticity, Long-Term Potentiation
| 4|	3/28|	Learning and Perception<br /> - Learning in neural networks: Function of sleeping/Back-propagation, End-to-End training	
| 5|	4/4	|Visual understanding 1 
| 6|	4/11 |Visual understanding 2 
| 7|	4/18 |	Temporal understanding – Theory<br />- Sequence learning, learning in long-term dependency, Seq-to-sequence learning<br /> - Lab Session 1: Defective PCB Detection
| 8|	4/25 |	Abstraction<br /> - Autoencoder, Defect and Abnormality detection, Word2Vec
| 9|	5/2	|Translation and Language Model<br /> - Attention, Image translation, Natural Language Processing<br /> - Lab session 2: Classification of Vibration Signal 
| 10|	5/9 |Understanding Language and Final exam<br /> - Talk to AI, Pretrained Language Model
| 11|	5/16 |Understanding multi-modal data<br /> - Multi-modality – LLM and LMM
| 12|	5/23 |Structure of idea and simulationy<br /> - Variational Autoencoder, Generative Adversarial Networks<br /> - Lab session 3: LLM with Digital Twin/Simulator
| 13|	5/30 |Diffusion Model<br /> - Image and Video generation, Explainable AI 
| 14|	6/6 |Selection by Consequences, Reinforcement Learning (National holiday, not mandatory)<br /> - ChatGPT, DeepSeek: Language Learning and Reasoning by Reinforcement Learning
| 15|	6/13 |	Final presentation and exhibition
| 16|	6/20 |	Final report, grading, feedback

## References
- Mingu Jeon, In-Ho Choi, Seung-Woo Seo, and Seong-Woo Kim, "Extremely Rare Anomaly Detection Pipeline in Semiconductor Bonding Process with Digital Twin-driven Data Augmentation Method," IEEE Transactions on Components, Packaging and Manufacturing Technology, Vol. 14, No. 10, pp. 1891 - 1902, Oct. 2024
- Gyuho Lee, Seong-Woo Kim, and Mingu Jeon, “Machinery Value Estimation Method based on IIoT System Utilizing 1D-CNN Model for Low Sampling Rate Vibration Signals from MEMS,” IEEE Internet of Things Journal, Vol. 10, No. 14, pp. 12261-12275, July. 2023
- Mingu Jeon, Siyun Yoo, and Seong-Woo Kim, "A Contactless PCBA Defect Detection Method: Convolutional Neural Networks with Thermographic Images," IEEE Transactions on Components, Packaging and Manufacturing Technology, Vol. 12, No. 3, pp 489 - 501, March 2022
