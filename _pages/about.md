---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

M.S. student in Chemistry at Sichuan University, working on computational electrolyte design and AI‑driven screening for rechargeable batteries.

My research interests include computational electrolyte design, electrode–electrolyte interface mechanisms, high‑throughput and machine‑learning screening, and AI4Materials / physics‑informed AI.


# 🔥 News
- *2025.11*: &nbsp;🎉 Joined the **AI4PhysSci Lab @ HKUST** as a Research Assistant (supervised by Prof. Lixue Cheng), working on AI‑assisted materials discovery.
- *2025.12*: &nbsp;🎉 Our work *“Multipaths Li⁺ Migration and In Situ Interfacial Alloying of Composite Solid‑State Electrolyte Enables High‑Performance All‑Solid‑State Lithium Metal Batteries”*, in which I contributed theoretical calculations, was accepted by *Small*.


# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Small</div><img src='images/small.png' alt="Small paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multipaths Li⁺ Migration and In Situ Interfacial Alloying of Composite Solid‑State Electrolyte Enables High‑Performance All‑Solid‑State Lithium Metal Batteries](https://onlinelibrary.wiley.com/doi/full/10.1002/smll.202509107)

Ying‑Ying Zhang, Xin‑Rui Xiao, **Hao‑Xiang Yin**, Qing‑Song Liu, Xiu‑Li Wang, Guo‑Rui Zhu, Gang Wu, Yu‑Zhong Wang

- Performed DFT (Gaussian) and MD (GROMACS) simulations to analyze Li⁺ migration pathways and interfacial alloying behavior in BiF₃‑containing composite solid‑state electrolytes, supporting the experimental design and mechanistic understanding.
</div>
</div>


# 🔬 Research Experience

### Machine Learning–Assisted High‑Throughput Screening of Fluorinated Electrolytes for Batteries  (Lead Researcher) · 2025–Now
- Built an LLM‑RAG mining pipeline (`Electrolyte_ML_Project/LLM_RAG_V3`) to automatically discover DOIs, download full texts and extract fluorinated liquid electrolyte molecules and properties from large‑scale literature.
- Developed an automated DFT screening workflow (`AutoDFT‑Fluoro`) that performs conformer search (GFN2‑xTB/CREST), B3LYP‑D3(BJ)/6‑311+G(d,p) optimization, Def2‑TZVP single‑point calculations and ESP analysis for mined molecules.
- Trained machine‑learning models on computed and reported properties to identify key electronic and solvation descriptors governing viscosity, ion transport and electrochemical stability, deriving design rules for fluorinated solvents/additives.
- Used the learned models to generate and rank new fluorinated electrolyte candidates that satisfy predefined stability and transport criteria, and down‑selected promising molecules for experimental validation.
- Collaborated with experimental colleagues to synthesize selected candidates and evaluate ionic conductivity and cycling performance in Li/Na batteries, confirming the predicted structure–property relationships.

### Weakly Solvated Functional Additive Design for Sodium Battery Electrolytes  (Master’s Research Project, Lead Researcher) · 2023–2025
- Designed a bi‑functional fluorinated additive to optimize solvation structure and stabilize interfacial chemistry in sodium metal batteries, guided by DFT and MD simulations.
- Performed Gaussian and GROMACS simulations to pre‑screen candidate molecules, analyze solvation structure and elucidate SEI formation mechanisms.
- Investigated ion‑transport kinetics via electrochemical measurements and spectroscopic analyses, linking microscopic solvation descriptors to macroscopic rate capability.
- Achieved >80% capacity retention after long‑term cycling at practical current densities; manuscript submitted to the *Journal of Energy Chemistry* (under review).


# 🎖 Honors and Awards
- Awarded the **Second Prize Academic Scholarship** for three consecutive years during undergraduate study.
- Recognized as **Class President** and **Outstanding Student Leader** at Sichuan University.
- Served as **Laboratory Instrument Manager (Micro FI‑TR)** and **Leader of Theoretical Calculations** group, supporting long‑term computational chemistry projects.
- Honored as **Outstanding Graduate Student** and **Excellent Master’s Graduate of Sichuan University** for academic and research performance.


# 📖 Educations
- *Sep. 2023 – Jun. 2026 (expected)*, M.S. in Chemistry, Sichuan University, State Key Laboratory of Advanced Polymer Materials. GPA: 3.64/4.0 (Centesimal average: 86.6).
- *Sep. 2019 – Jun. 2023*, B.S. in Applied Chemistry, Sichuan University. GPA: 3.48/4.0 (Centesimal average: 84.3).


# 💬 Talks
- *2025.11*, Oral presentation at **NCEC 2025 (National Chemical Engineering Conference)**, Shanghai, China – *Weakly Solvated Functional Additive Design for Sodium Battery Electrolytes*. [Photo](images/NCEC2025.png)


# 💻 Technical Expertise

**Theoretical & Computational Chemistry**
- Density functional theory calculations with Gaussian (geometry optimization, frequency and single‑point energy), solvation models and wavefunction analysis using Multiwfn.
- Molecular dynamics simulations of electrolyte systems using GROMACS and analysis of ion transport and interfacial structure.

**Programming & Automation**
- Proficient in Python for data processing, scientific computing and workflow automation; comfortable with LaTeX, MATLAB and basic shell scripting.
- Developed automated pipelines such as `AutoDFT‑Fluoro` for high‑throughput DFT screening and Gaussian job scheduling on HPC clusters.

**Machine Learning & AI‑Assisted Research**
- Experience with PyTorch, scikit‑learn, Pandas and NumPy for building and evaluating machine‑learning models for materials property prediction.
- Developed an LLM‑RAG pipeline to mine fluorinated electrolyte molecules and properties from the literature, integrating large language models with document parsing and data cleaning.
- Applied graph neural networks (GNNs) and equivariant GNNs (EGNNs) to learn structure–property relationships of electrolyte molecules and extract key electronic/solvation descriptors.
- Experienced in using AI agents for “vibe‑coding” style development, combining conversational agents with scripts to prototype and iterate on research code efficiently.


# 🎯 Hobbies

Beyond research, I enjoy activities that keep me energetic and inspired:

## 🚗 Driving
I am a car enthusiast and enjoy long‑distance road trips. I have completed two solo self‑driving journeys:

- 2023: ~2,000 km **Qinghai–Gansu loop**, exploring the Qinghai–Tibet Plateau and surrounding regions.
- 2022: **Yunnan–Guizhou–Sichuan loop** road trip across southwestern China.

I am also passionate about sim racing. In titles such as **Le Mans Ultimate (LMU)** and **Assetto Corsa Competizione (ACC)**, I maintain solid lap records and once earned **Silver Driver** and **Fair‑Play** badges in LMU.

## 🏅 Sports
I have been a football fan since middle school and often play informal matches with friends or watch games together. I am also an F1 fan; my favourite drivers are **Max Verstappen** and **Charles Leclerc**, whose driving styles and race craft deeply inspire me.

## 🎮 Gaming
I am a casual but competitive **Teamfight Tactics** player. During my spare time, I once reached **Master** rank on the Chinese server and participated in local open‑qualifier tournaments, which taught me to stay calm, adapt strategies and manage variance under pressure.

