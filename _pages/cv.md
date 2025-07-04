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

- GPU-accelerated large eddy simulations using simplified lattice boltzmann method
  - Dual Degree Thesis, Indian Institute of Technology, 2025
  - Advisor: Prof. Kameshwarrao Anupindi

# Work experience

- Mechanical Dept, IIT Madras, Graduate Research Assistant, May 2024 - June 2025

  - Advisor: [Prof. Kameshwarrao Anupindi](https://home.iitm.ac.in/kanupindi/)
    - Developed GPU-accelerated LES modules for solver using OpenACC, implementing subgrid-scale (SGS) models and synthetic eddy method for realistic inlet turbulence generation.
    - Conducted validation study comparing SGS models (Smagorinsky, Vreman, WALE, Sigma) for wall-bounded (lid-driven cavity) and free-shear (jet flow) cases, identifying optimal approach.
    - Applied validated models and approach to a model room ventilation flow case, achieving good agreement ( 20% mean deviation error) with experimental data from a reference study.
    - Accepted to present these findings at the upcoming [INCOTHERM](https://people.iitism.ac.in/~incotherm2025/home.html) conference, with plans for subsequent first author journal publication.

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

Mentored underprivileged students for JEE (one of Asia's toughest undergraduate entrance exams) as part of pan-India NGO [Avanti Fellows](https://www.avantifellows.org/).

# Honors and Awards

- Co-founded Team Agnirath and successfully represented India in World Solar Challenge, an international solar car competition. (2023)
- MITACS Fellowship : Fellowship to pursure research in summer at a canadian university. (2023)
- Ranked among the top 1% in the IIT-Joint Entrance Examination and 1 in physics at MHT-CET (2020)
- Ranked 2nd at Student Science Meet by Rashtriya Vigyan Sangrahalaya for 'solution on price hike and adulteration in pulses' (2016) 

# Relevant Coursework

- Turbulence modeling
- Parallel scientific computing
- Advanced Computational Fluid Dynamics
- Numerical Linear Algebra
- Meshfree methods for applied to hydrodynamics
- FEM applied to ocean engineering
- Mathematical foundations of Data Science
- Deep Learning Specialisation by Andrew Ng (coursera)

<!-- # Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

For a detailed CV/resume please email me at `na20b053 at smail dot iitm dot ac dot in`
