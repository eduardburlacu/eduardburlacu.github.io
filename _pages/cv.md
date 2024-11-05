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
* M.S. in Information and Computer Engineering, University of Cambridge, 2025
* B.A. in Information and Computer Engineering, University of Cambridge, 2024
  
Work experience
======
* Summer 2024: ML Research Engineer Intern
  * Autodesk Research, London
  * Topic: Fast-sampling diffusion model for 3D Computer Vision. Generating 3D bodies as CAD b-reps.
  * Held a presentation outlining findings and how this method improves the latency and reduces costs in deployment.
  * Supported the team by submitting and evaluating PRs, reporting issues, and providing support with debugging.
  

* Summer 2023: ML Research Intern
  * CS department, University of Cambridge
  * Topic: Federated Learning. Allowing straggler clients to optimally offload computation to other clients. Dropped the training time by 30% and reduced straggler prevalence by 15X.
  * An agent splits the neural networks for minimizing the training time. It combines heuristic scheduling, PPO and split learning with any FL strategy.
  * The heuristic-based approach matches prior RL methods that suffered of the curse of dimensionality, thus applicable to a few devices(<6). The proposed method can be applied for thousands of clients.
  

* Summer 2022: Hardware Engineer Intern
  * Qualcomm R&D Lab, Cambridge
  * Topic: I worked in 2 projects, one focused on PCB design, and one on software development.
  * In the PCB project, I designed an internal board from scratch and implemented it in ECAD.
  * I developed a GUI application that automates internal processes of circuit testing by serial communication with dedicated instrumentation. The test time was dropped from 1h to 3 minutes.
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Courses
=======
| Course            | Skills   | 
| :---------------- | :------: | 
| Medical Imaging & 3D Computer Graphics| MRI; CT; Splines; OpenGL/ Vulkan core concepts | 
| Inference                           |   Variational Inference, HMMs, EM, Bayesian Inference   | 
| Information Theory and Coding       | Lossless compression; Huffman and Arithmetic Coding; Message Passing| 
| Mathematical Methods                | Linear Algebra, Stochastic Process, Optimization  |
| Statistical Signal Processing       | Core Probability, Markov Chains, Estimation Theory|
| Signals and Systems                 | Z-transform, FFT, CT Random Processes|
| PDEs and Variational Calculus       | Index Notation, Analytical and Computational methods for PDEs; Functional optimization|
| Economics                           | Business Economics; Demand & Supply; Game Theory |
| Computer Vision                     | SIFT descriptor, |
| Deep Learning                       | |
|Computational Statistics and ML      | MCMC, Lebesgue Int., Functional Analysis, Sampling|
| Probabilistic ML                    | Gaussian Processes, Ranking, Document Modelling|
| Algorithms & Data Structures        | |
| Computational Neuroscience          | |
| Statistical Signal & Network Models | |

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
