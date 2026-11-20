---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download full CV (PDF)](/files/Iman_Alizadeh_Fakouri_CV.pdf)

Education
======
* **B.S. in Electrical Engineering**, Sharif University of Technology, Tehran, Iran *(Sep. 2022 – Aug. 2026)*
  * GPA: 18.76/20 (Department Average: 16.42/20) — Rank: 16/191 (Top 10%)
  * **Selected Coursework:** Digital Signal Processing Lab, Estimation Theory, Software-Defined Cloud Mobile Networks, Data Communications Networks, Digital Communications, Deep Learning, Reinforcement Learning, Deep Generative Models, Convex Optimization

Research Experience
======
* **RL-Based Routing and Sub-Band Selection for THz Aerial Networks** *(Oct. 2026 – Present)*
  * Remote research collaboration with Prof. Özgür Gürbüz (Sabancı University)
  * Modeling 3D aerial routing as a finite-horizon MDP under probabilistic rain cells, frequency-dependent pointing jitter, and relay queue contention; designing a PPO agent and analytical routing heuristic for multi-hop relay selection and sub-band allocation.

* **ML-Based Broadband Path Loss Modeling for THz Aerial Networks** *(Aug. 2026 – Present)*
  * Remote research collaboration with Prof. Özgür Gürbüz (Sabancı University)
  * Proposed the Physics-Anchored Residual Network (PARN) and Physics-Anchored Mixture-of-Experts (PA-MoE) architectures to generalize broadband THz atmospheric absorption across frequencies, atmospheric profiles, and aerial geometries.

* **PURE Summer Research Intern** *(Summer 2026)* — [Certificate](/files/PURE_Internship_Certificate.pdf)
  * Sabancı University, Istanbul, Turkey
  * Reviewed THz path-loss modeling literature for aerial communications and benchmarked regression-based and neural-network approaches.

* **LLMs for 5G Network Fault Diagnosis (B.S. Thesis)** *(Aug. 2025 – June 2026)* — [Thesis PDF](/files/BS_Thesis_5G_LLM.pdf)
  * Supervisor: Prof. Babak Khalaj, Sharif University of Technology
  * Deployed OpenAirInterface and UERANSIM on Kubernetes with a Chaos Mesh fault-injection pipeline; proposed SHEPR, an iterative prompt-optimization method guided by extracted protocol knowledge for 5G fault detection.

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Teaching
======
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>

Technical Skills & Languages
======
* **Languages:** Python, MATLAB, C/C++
* **Frameworks:** PyTorch, TensorFlow, Scikit-learn, NumPy, Pandas, Matplotlib
* **Tools & Systems:** OpenAirInterface, UERANSIM, Docker, Kubernetes, Linux, Mininet, OMNeT++, Wireshark, Git
* **Spoken Languages:** English (C1 — IELTS: 7.5), Turkish (Fluent), Persian (Native), Azerbaijani (Native)