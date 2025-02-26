---
layout: home
title: Home
permalink: /:path/
seo:
  type: Course
  name: Real World Robot Learning 
---

# Real-World Robot Learning 
Spring 2025. ESE 6800/CS7000. Tue / Thu 10:15-11:45. AGH 105.

![Image](/assets/images/front_page.png)

## Announcements 
{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}

## Course Overview 

Decision-making has been a cornerstone of artificial intelligence since the field's inception in the 1960s. While the techniques and algorithms have evolved dramatically over time, the fundamental challenge remains: how to make intelligent decisions in the presence of uncertainty. Over the past six decades, this research has led to the development of highly advanced systems, with some achieving superhuman performance in cognitively demanding tasks like Go, Atari, Gran Turismo, Chess, StarCraft, and SOTA.

However, despite these remarkable successes, most of these systems excel only in controlled, simulated, or game-based environments. Why haven’t the same methods translated seamlessly to real-world decision-making, such as controlling a physical robot to perform household tasks? What makes real-world environments so uniquely challenging? And what recent advances are pushing the boundaries of what’s possible in real-world applications?

This course offers a structured framework to explore these questions. We will study techniques for learning-based decision-making, such as imitation learning and reinforcement learning, focusing on their practical challenges when applied in real-world scenarios. Through a combination of lectures, student presentations, hands-on projects, and guest presentations from leading experts in the field, students will gain a deep understanding of the state-of-the-art decision-making systems and their challenges when applied to robotics.

### Prerequisites

This is a graduate-level course. Students are expected to have prior knowledge in deep learning and robotics, such as the topics covered in Robot Learning (ESE 650), Principles of Deep Learning (ESE 546), Applied Machine Learning (CIS 5190), and Introduction to Robotics (MEAM-520).



## Schedule (Tentative) 

The general idea behind this course is the following. We will start by going off the beaten arxiv track and read oldy but goldy papers. Then, we will use such papers to understand the roots of more recent works. Note that this schedule will evolve during the course.

{% for module in site.modules %}
{{ module }}
{% endfor %}


## Instructors

<figure style="display: inline-flex;">
<figure>
<img src="/real_world_robot_learning_sp25/assets/images/al.jpeg" alt="Avatar" style="width:200px; height:auto; object-fit: cover; border-radius:50%; padding:20px;">
<figcaption style="text-align: center;"><a href="https://antonilo.github.io/"><button type="button" name="button" class="btn">Antonio Loquercio</button>
</a></figcaption>
</figure>

<figure>
<img src="/real_world_robot_learning_sp25/assets/images/dj.jpg" alt="Avatar" style="width:200px; height:auto; object-fit: cover; border-radius:50%; padding:20px;">
<figcaption style="text-align: center;"><a href="https://www.seas.upenn.edu/~dineshj/"><button type="button" name="button" class="btn">Dinesh Jayaraman</button>
</a></figcaption>
</figure>

</figure>


## Teaching Assistants 

<figure style="display: inline-flex;">

<figure>
<img src="/real_world_robot_learning_sp25/assets/images/lmk.jpg" alt="Avatar" style="width:200px; height:auto; object-fit: cover; border-radius:50%; padding:20px;">
<figcaption style="text-align: center;"><a href="https://www.linkedin.com/in/leonmkim/"><button type="button" name="button" class="btn">Leon Kim</button>
</a></figcaption>
</figure>

<figure>
<img src="/real_world_robot_learning_sp25/assets/images/js.jpeg" alt="Avatar" style="width:200px; height:auto; object-fit: cover; border-radius:50%; padding:20px;">
<figcaption style="text-align: center;"><a href="https://junyaoshi.github.io/"><button type="button" name="button" class="btn">Junyao Shi</button>
</a></figcaption>
</figure>

</figure>

## Related Courses


<a href="https://robots-that-learn.github.io/"> Robots that learn</a>, UC Berkeley.

<a href="https://docs.google.com/document/u/1/d/e/2PACX-1vQaioAfwh81lxb3Z3B-Qf83I8DSb6Xu1z7KBbcJBxBrutR6qVEZ12lig5rEgfyq31Ojamf8JeVzSvVg/pub"> Visual Scene Understanding</a>, UC Berkeley.

<a href="https://abajcsy.github.io/embodied-ai-safety/">Embodied AI Safety</a>, CMU. This course is not only very interesting, but also has an awesome webpage.



