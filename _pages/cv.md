---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Education

- M.Tech, Computational Engineering, IIT Madras, (Expected 2025)
- B.Tech, Ocean Engineering, IIT Madras, (Expected 2025)

# Thesis

- Particle-laden flow simulations using Simple and Highly Stable Lattice Boltzmann Method
  - Dual Degree Thesis, Indian Institute of Technology, 2025
  - Advisor: Prof. Kameshwarrao Anupindi

# Work experience

- Mechanical Dept, IIT Madras, Graduate Research Assistant - Summer 2024-Present

  - Advisor: [Prof. Kameshwarrao Anupindi](https://home.iitm.ac.in/kanupindi/)
    - Coupled and validated sub-grid scale models to model turbulence (GPU-parallelized using OpenACC), against benchmark 3D lid-driven cavity flow capturing boundary-induced turbulence.
    - Implemented and validated module for particle-laden flow (in FORTRAN), which uses an Eulerian–Lagrangian approach to model the carrier and the dispersed phase respectively, against the benchmark experimental data in circular turbulent jet flows.
    - Implementing a higher-order scheme based on the concepts of virtual streaming nodes and higher-order interpolation, following the work of
    [Zhen Chen and Chang Shu](https://pubs.aip.org/aip/pof/article/30/10/103605/989749).
    - Studying the evolution of poly-disperse particles in jet flow and indoor ventilation cases. This has practical implications in air
    quality control in industrial ventilation systems

- LMFTEUS, Universite de Sherbrooke, Research Intern, Summer 2023

  - Advisor: [Prof. Sebastian Poncet](https://lmfteus.wordpress.com/team/)
    - Motivation was to develop a carbon dioxide and propane mixture that stays subcritical during separation, offering higher energy efficiency than pure carbon dioxide while reducing flammability risks of pure propane.
    - Conducted Ranque-Hilsch vortex tube experiments with pure carbon dioxide and generated validation data.
    - Simulated pure carbon dioxide for operating conditions from experiments and validated CFD model and numerical procedure. Later
    conducted simulations for carbon dioxide and propane mixture.
    - Conducted a model comparison study for RANS models using Fluent, and found that the k-omega SST with perfect gas equation produced closest results to experimental cold-mass fractions values.

- Ocean Engineering Dept, IIT Madras, Undergraduate Research Assistant, Summer 2022

  - Advisor: [Prof. Sriram V](https://home.iitm.ac.in/vsriram/)
    - Familiarized myself with the extensive in-house code base in C and conducted literature review.
    - Developed and tested sub-routines for patching multiple bodies with complex geometries using the immersed boundary method. Also force calculation routine for fluid-structure interaction.
    - Simulated gap resonance problem in moonpools. Validated results for a two fixed barge geometries case for various wave headings against established benchmarks in the literature.
    - I updated the professor on my progress through weekly group meetings, where we presented and discussed the research each member was working on.

- SkyServe.ai, Remote, India, Machine Learning Intern, Spring 2023

  - Advisor: [CPO Mr. Adithya Kothandhapani](https://www.skyserve.ai/)
    - Collaboratively developed a UNet-based building detection solution on Sentinel-2 data, utilizing a pre-trained ResNet50 encoder under
    guidance from a former ISRO group director.
    - Enhanced dataset quality by 5% by refining ROI selection and automating diverse Sentinel-2 image extraction via Google Earth Engine to mitigate model bias.
    - Integrated the optimized model into the company’s website for real-time predictions, aligning with required needs after an extensive literature review and different architectures exploration.


# Skills

- Deep Learning
- Foundational Turbulence modelling
- Large Eddy Simulations
- Lattice Boltzmann modelling
- Parallel Computing
  - OpenMP
  - MPI
  - OpenACC, CUDA
- Python
  - TensorFlow
  - OpenCV
- C, C++
- FORTRAN
- Ansys, Solidworks
- MATLAB, Paraview

<!-- # Talks

- NASA ULI Safe Aviation Autonomy Seminar. "Scalable Multi-Agent Reinforcement Learning through Intelligent Information Aggregation"
- Tata Consultancy Services Research and Innovation Labs. --"-- -->

# Service

<!-- ## Conference Reviewing

- AAAI (2021, 2024)
- CVPR (2024)
- IROS (2024)
- IFAC (2024)
- NeurIPS (2024)
- ICLR (2024)
- ACL (2024) -->

<!-- ## Journal Reviewing

- IEEE Transactions on Circuits and Systems for Video Technology (2023)
- Complex & Intelligent Systems (CIS)
- Information Science (IS)
- IEEE Robotics and Automation Letters (RAL)
- Journal of Guidance, Control, and Dynamics (JDCD) -->

<!-- ## Workshop Reviewing

- [The 4th Workshop on Mathematical Reasoning and AI](https://mathai2024.github.io/) @NeurIPS (2024)
- [NeurIPS 2024 Workshop on Multimodal Algorithmic Reasoning](https://marworkshop.github.io/neurips24/) @NeurIPS (2024)
- [Robotic Tasks and How to Specify Them?](https://sites.google.com/view/rss-taskspec) @RSS (2024) -->

<!-- # Workshop Organisation

- [Coordination and Cooperation in Multi-Agent Reinforcement Learning](https://sites.google.com/view/cocomarl-2024/home) (CoCoMARL) @RLC 2024 -->

# Mentoring

Mentored underprivileged students for JEE (one of Asia's toughest undergraduate entrance exams) as part of pan-India NGO Avanti Fellows.
<!-- A list of budding engineers I have mentored:

- Wenqi Ding (EECS, S.B., MIT) 2022, 2024
- Vittal Thirumalai (EECS, S.B.+ M.Eng.), 2024
- Jackson Zhang (EECS, S.B.+ M.Eng.), 2024
- Adelmo Morrison Orozco (EECS + Math, S.B.) 2024
- Marina Ten Have (EECS + AI, S.B.) 2024
- Darren Chen (EECS, S.B.) 2024
- Daniel Liu (EECS, M.Eng.) 2021-2022
- Kenneth Choi (EECS, S.B.) 2022
- Carson Smith (EECS, M.Eng) 2021
- Laura Peralta (Electrical and Electronics, B.E.; Hampton University) 2021
- Akila Sarvanan (AeroAstro, S.B.; MIT) 2021
- Simran Pabla (AeroAstro, M.Eng.; MIT) 2021 -->

# Honors and Awards

- Co-founded Team Agnirath and successfully represented India in World Solar Challenge, an international solar car competition. (2023)
- MITACS Fellowship : Fellowship to pursure research in summer at a canadian university. (2023)
- Ranked among the top 1% in the IIT-Joint Entrance Examination and 1 in physics at MHT-CET (2020)
- Ranked 2nd at Student Science Meet by Rashtriya Vigyan Sangrahalaya for 'solution on price hike and adulteration in pulses' (2016) 

# Relevant Coursework

- Turbulence modeling
- Parallel scientific computing
- GPU Programming*
- Advanced Computational Fluid Dynamics*
- Numerical Linear Algebra
- Meshfree methods
- Probability, Statistics and Stochastic Process
- Mathematical foundations of Data Science
- Deep Learning Specialisation by Andrew Ng (coursera)

<!-- # Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

For a detailed CV/resume please email me at `mastkartik at smail dot iitm dot ac dot in`
