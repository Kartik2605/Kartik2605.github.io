---
layout: archive
# title: "A few of the projects I worked on!"
permalink: /project/
author_profile: true
redirect_from:
  - /extracurricular-activities
---
## Co-founder and Aerodynamcis Lead at Agnirath (2021 - 2024)
*[Agnirath](https://www.agnirath.in/) - Student team of IIT Madras that designs solar-powered cars and represents India at international competetions like World Solar Challenge*

We started as an interest group under the guidance of [Prof. Sivakumar Srinivasan](https://iitm.irins.org/profile/10107#experience_information_panel), and eventually grew to a team of 30+ passionate individuals. I led and worked on the aerodynamics & cooling subsystem of the car, collaborating closely with our aerodynamics advisor, [Prof. Vishwanathan Babu](https://iitm.irins.org/profile/10330). In this subsystem, we modeled and simulated external turbulent airflow, conducted moving ground simulations, and managed heat and airflow in our active battery thermal management system, as well as ventilation inside the cockpit. We mostly worked with the Generalised k-omega model using Ansys Fluent and MATLAB scripts for specific requirements. To validate our CFD results, we collaborated with scientists from [National Aerospace laboratory](https://www.nal.res.in/), India and conducted wind tunnel (low-speed) tests for a 1:6 scaled model. This involved aerodynamic force calculations, the oil flow method, and Particle Image Velocimetry to visualize flow and separation regions. Also, we conducted a thermal performance test of our variable-height motor controller heat sink in an environmental chamber to validate our CFD results. It led us to file a patent for our novel heat sink design. After our initial efforts, we moved to the manufacturing phase where I worked on the vacuum infusion process for manufacturing the aeroshell out of glass fiber composite panels. I also managed the egress system, virtual validation of all components assembly in CAD. The year 2023 brought a pivotal moment: we secured a huge sole sponsorship for our venture. All the hard work paid off and eventually we represented India at the World Solar Challenge 2023. 

## Simulating gap resonance for moonpools using IITM-RANS3D solver (Summer 2022)
*Advisor : [Prof. Sriram V](https://home.iitm.ac.in/vsriram/)*

I worked as an undergraduate researcher in the Ocean Engineering Department at IIT Madras at Prof. Sriram's lab. My initial focus was on familiarizing myself with the code base of solver written in C and conducting a thorough literature review to understand the underlying methodologies. The solver uses Fully Non-linear Potential Theory (FNPT) to generate waves immitating wave generator from experiments and is coupled with RANS to solve for physical unkowns in the region of interest in the domain. I developed and tested sub-routines for patching multiple bodies with complex geometries using the immersed boundary method, and also implemented a force calculation routine for fluid-structure interaction problems. After this, I worked on simulation of gap resonance phenomena in moonpools, where I validated results for two fixed barge geometries across various wave headings against established benchmarks from the literature. During this time, I regularly updated Prof. Sriram and the research group on my progress during weekly meetings, where we presented and discussed our ongoing work. The IITM-RANS3D solver is open source; to see the detailed documentation, know about it, and download the software, click [here](https://home.iitm.ac.in/vsriram/index.php/research/iitm-rans3d/).

## Course Projects:
****************************************

**2D solitary wave simulations using Moving Particle Semi-implicit (MPS) meshfree method in C++ (2023)**  
*Guide : [Prof. Sriram V](https://home.iitm.ac.in/vsriram/)*

A course project for the OE6020 - Meshfree methods applied to hydrodynamics Fall 2023 course at IIT Madras. In this project, I focused on the Moving Particle Semi-Implicit (MPS) method—a mesh free approach renowned for its versatility in capturing complex fluid behaviours. It employs particles to represent the fluid, enabling the simulation of dynamic free surfaces and fluid flows with greater flexibility than traditional grid-based methods. The report linked at the end gives a detail overiew of the model implementation and using it for simulating different 2D waveforms. It is then validated for a 2D solitary wave form against the standard benchmark case from literature. [[PDF]](https://github.com/Kartik2605/2D-Wave-simulation-using-Moving-Particle-Implicit-method/blob/main/Report.pdf) [[Code]](https://github.com/Kartik2605/2D-Wave-simulation-using-Moving-Particle-Implicit-method)

**Parallelisation of Classical LBM using OpenACC in C++ and evaluation on 2D lid driven cavity test (2024)**  
*Guide : [Prof. Kameshwarrao Anupindi](https://home.iitm.ac.in/kanupindi/)*

A course project for the ID5130 - Parallel Scientific Computing Spring 2024 course at IIT Madras. This project presents the implementation of a classical Lattice Boltzmann Method (LBM) in C++ and its parallelization using OpenACC. The LBM is a technique for simulating fluid flow by modeling the microscopic dynamics of particle distributions on a lattice. The LBM solver exhibits significant potential for parallelization, particularly in the collision and streaming steps. In this project, two main blocks of parallelism are utilized: the first block handles memory allocation for all variables and initialization on the GPU, while the second block operates within a while loop, managing iterations until convergence. It performs streaming and collision step updates on GPU and transfers error values. Upon convergence, the GPU transfers the complete solution to the CPU for further post-processing. [[PDF]](https://github.com/Kartik2605/GPU-Parallelised-Classical-LBM-and-evaluation-on-2D-Lid-Driven-cavity-test./blob/main/Report.pdf) [[Code]](https://github.com/Kartik2605/GPU-Parallelised-Classical-LBM-and-evaluation-on-2D-Lid-Driven-cavity-test.)


## Mini Projects:
****************************************
<!-- ### A list of small projects which required less than a couple of weeks to work on: -->
<!-- * [**Bass Booster**](https://github.com/nsidn98/Bass-Treble-Booster): A pythonic way to overlay another layer of bass in audio files. I was motivated to try out this after hearing this [bass boosted version](https://www.youtube.com/watch?v=VmITSg23CTY) of Attention by Charlie Puth. Can also work as a treble booster. -->

* **Fake News Detection** is a deep leaarning based solution for a hackathon held at [pravega](https://www.pravega.in/?i=1), technical fest held by IISc. The goal is to create a recurrent neural network architecture learning only through heading and article body to identify fake news. It was selected as one of finalist in the competition. [[Code]](https://github.com/Kartik2605/fake-news-detector)

* **Computer vision based game controller**: It is a 3D third player control spaceshooting and a mission game. The moto of the project of making game is to try to get an imersive experience of gameplay. In these the head movements control the 6 degrees of motion of the spaceship and shooting is control by hand gestures.
  - Control with a webcam which detects landmarks on face and calculates the head pose parameters using PnP algorithm. The open source OpenFace software was used.
  - The hand gesture used for shooting is implemented using mediapipe in-built algorithm.
  
Its integrated with unity using its python compatibility and socket programming. Unity is used to develope game. It was showcased at the OpenHoue at IIT Madras. [[Code]](https://github.com/Kartik2605/REBOOT--CVI)

<!-- * **Music with Numbers**: I like to play piano when I am bored or want to cheer myself. I have always been intrigued by Beethoven's music. I came across a video about the math behind some of his musical masterpieces which inspierd me to write this small piece of code to convert the first few digits of ![pi](http://latex.codecogs.com/gif.latex?%5Cpi) and ![e](http://latex.codecogs.com/gif.latex?e) to music on different pentatonic scales. Different scales can be chosen to make the music with numbers. Here are examples of music generated from [pi](https://drive.google.com/file/d/1xqlR9W704Lurq1qHxuNgQ2DjXlNhA3L8/view?usp=sharing) and [e](https://drive.google.com/file/d/1BCA1s1jsqApCm0oZtBV60-okhJHtmDkn/view?usp=sharing). [[Code]](https://github.com/nsidn98/Music-with-numbers) -->

<!-- * **Games**: A few of the games implemented 
  - Conway's Game of Life
  - Car Racer: The video game of traversing a car through a road just like the DeepTraffic Competition.
  - Maze Solver: Solves mazes with input image
  [[Code]](https://github.com/nsidn98/Games) -->



