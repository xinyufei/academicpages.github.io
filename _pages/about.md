---
permalink: /
title: "Xinyu Fei"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## About Me

Xinyu Fei is an Applied Scientist II at Amazon.com, focusing on ML-integrated optimization algorithm design and GenAI reasoning for optimization. Xinyu received her Ph.D. in Operations Research and Scientific Computing from the University of Michigan, advised by [Prof. Siqian Shen](https://websites.umich.edu/~siqian/). 

[**Resume**](https://drive.google.com/file/d/1lxWcwNtXLazkfS8c3HMeEagcUdmsDLbi/view?usp=sharing)

### Research Interests
- **Optimization**: Mixed-integer optimization, stochastic optimization, large-scale optimization
- **Machine Learning**: ML-integrated optimization, GenAI agents, reinforcement learning (ongoing research)
- **Applications**: Quantum computing, traffic optimization, resource planning, labor optimization

### Technical Skills
- **Programming Languages**: Python, Java, Pytorch, C++, SQL, Matlab, R  
- **Solvers & Tools**: Xpress, Gurobi, AWS (S3, SageMaker, Lambda)

## Education {#education}

* *Sept. 2019 - Dec. 2023*  
  **Ph.D. in Operations Research and Scientific Computing**  
  University of Michigan  
  Focus: Mixed-integer & stochastic optimization, reinforcement learning  
  Advisor: [Prof. Siqian Shen](https://websites.umich.edu/~siqian/)

* *Sept. 2015 - Jun. 2019*  
  **B.S. in Computational and Applied Mathematics**    
  School of the Gifted Young (SCGY)  
  University of Science and Technology of China

## Work Experience {#work-experience}

* *Feb 2024 – Present*  
  **Applied Scientist II**  
  *Amazon.com*  
  • Scalable Optimization System for Real-Time Labor Planning  
  • AI Reasoning Model for Explainable Optimization

* *May 2023 – Aug 2023*  
  **Research Scientist Intern**  
  *Amazon.com*  
  • Machine Learning Based Ergonomics Stowing Assistance

* *May 2022 – Aug 2022*  
  **Research Scientist Intern**  
  *Amazon.com*  
  • Decomposition Algorithm for Large-scale Resource Planning Problems

* *May 2021 – Feb 2024*  
  **Research Collaborator**  
  *Argonne National Laboratory*  
  • Binary control for quantum systems under uncertainty

## Publications {#publications}

{% include base_path %}

{% assign sorted_publications = site.publications | sort: 'date' | reverse %}
<ul>
{% for post in sorted_publications %}
  {% include archive-single.html %}
{% endfor %}
</ul>

## Presentations & Talks {#presentations}

* **Data-Driven Automated Labor Staffing by Real-time Optimization in Amazon Fulfillment Centers**  
  <span style="font-size: 0.9em;"><i>INFORMS Annual Meeting</i>, Seattle, <i>October 2024</i></span>
* **Route Recommendation Optimization under Unknown and Uncertain Travelers' Trust**  
  <span style="font-size: 0.9em;"><i>INFORMS Annual Meeting</i>, Phoenix, <i>October 2023</i></span>
* **Binary Control Pulse Optimization for Quantum Systems**  
  <span style="font-size: 0.9em;"><i>INFORMS Annual Meeting</i>, Indianapolis, <i>October 2022</i></span>
* **Quantum Control Pulse Optimization With Uncertain Hamiltonian Controllers**  
  <span style="font-size: 0.9em;"><i>INFORMS Annual Meeting</i>, Indianapolis, <i>October 2022</i></span>
* **Optimization Methods for Discrete Binary Quantum Control**  
  <span style="font-size: 0.9em;"><i>Workshop on Optimization and Machine Learning</i>, Evanston, <i>May 2022</i></span>
* **Optimizing Reopening and Lockdown of Correlated Businesses and Regions under Uncertain Disease Outbreaks**  
  <span style="font-size: 0.9em;"><i>IISE Annual Meeting</i>, Virtual, <i>May 2021</i></span>
* **Distributed Optimization of Traffic Signals in Arterial Networks**  
  <span style="font-size: 0.9em;"><i>INFORMS Annual Meeting</i>, Virtual, <i>November 2020</i></span>
