---
layout: page
title: 고급 디지털 제조 및 실습
description: >-
    Course policies and information.
---

# 고급 디지털 제조 및 실습
Advanced Digital Fabrication and Practice

M2866.004200
> This course aims to turn ideas into reality using digital manufacturing equipment. Students will learn to digitize their concepts through 3D modeling tools and materialize them using digital manufacturing devices such as 3D printers, computer-controlled milling machines, and industrial robotic arms. Beyond creating the physical appearance and moving parts, students will also design and program microcontrollers using electronic components. The course culminates in a final project where students apply the digital manufacturing skills they have acquired to design and produce a prototype. Through this process, students will gain an understanding of nano-level precision mass production techniques and the principles of living organisms as manufacturing systems. Additionally, the course includes theoretical lectures and hands-on practice on design methodologies leveraging generative AI and the use of physical simulators.

- __Location__: Bld 38-429
- __Lecture__: Monday 9:30 - 10:45
- __Practice__: Monday 11:00 - 12:15
  

## Teaching Assistants
{% assign teaching_assistants = site.staffers | where: 'role', 'ta_digital_fabrication' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}


---

## References
- Neil Gershenfeld, et al. &quot;Designing reality,&quot; Basic Books, 2017.
- Tom Wujec, “The Future of Making,&quot; Melcher Media, 2017.
- [Genesis AI](https://genesis-embodied-ai.github.io/)
- [Generating Mesh via Prompting in Blender](https://github.com/huggingface/meshgen)
- [Converting Image to 3D Model](https://huggingface.co/spaces/JeffreyXiang/TRELLIS)

## Grading
- Attendance: 5%
- Assignment: 65%
- Final exam: 20%
- Quiz: 5%
- Attitude: 5%

## Lecture Schedule

|       Week        | Lecture                                                                      | Practice |
|:-------------------:|-----------------------------------------------------------------------------|----------|
| Week 1<br /> (3/10)     | Course Introduction<br /> -Introduction to Digital Fabrication<br />	- Additive manufacturing|     | 
| Week 2<br /> (3/17)     | Digital world: Point to 3D world<br /> - Fundamentals of Euclidean geometry<br /> - Programming practice, Computer-Aided Design 					              | - Python programming for 3D geometry<br /> - 3D Printing practice<br /> - Assignment #1    | 
| Week 3<br /> (3/24)     | Bio-making: Digital to Life - 1<br /> -Atom to Bio-information 					              |  - CAD practice<br /> - Assignment #2       | 
| Week 4<br /> (3/31)     | Bio-making: Digital to Life - 2<br /> -CAD for atomic-level structure 					              |  - Assignment #3: One page project proposal       | 
| Week 5<br /> (4/7)     | CAM: Computer Aided Manufacturing<br /> - Subtractive manufacturing					              |- CAM & CNC cutting practice<br /> - Assignment #4      | 
| Week 6<br /> (4/14)     | From CAD to Physics-based digital twin<br /> - Physics in virtual world<br /> - Environmental and safety education 					              |  - Digital Twin practice<br /> - Assignment #5      | 
| Week 7<br /> (4/21)     | The Art of Electronics 1 – Turing to Blink 					              |  - Making a Breaduino practice<br /> - Assignment #6     | 
| Week 8<br /> (4/28)     | The Art of Electronics 2 – Programming<br /> -Project review - 1 					              |  - Breaduino programming practice<br /> - Assignment #7      | 
| Week 9<br /> (5/12)     | The Art of Electronics 3 – PCB making					              |  - PCB design practice<br /> - Assignment #8<br /> - Assignment #9: Detailed design for final project      | 
| Week 10<br />  (5/19)     | Physical world to Digital world: 3D scanning<br /> - How to mold and cast a product 					              |  - Mold making and casting practice<br /> - Order electronic/mechanical components<br /> - Project review – 2       | 
| Week 11<br />  (5/26)     | - 3D Modeling via Large Language Model (Text)			              |        | 
| Week 12<br />  (6/2)     | - 3D Modeling via Large Multimodal Model (PointCloud, Image, etc)				              |        | 
| Week 13<br />  (6/9)     | - Making an artifact and meeting with mentors					              |        | 
| Week 14<br />  (6/16)     | - Final presentation and exhibition			              |        | 
| Week 15<br />  (6/23)     | - Final report, evaluation, grading, and feedback 					              |        | 




