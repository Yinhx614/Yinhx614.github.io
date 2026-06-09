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
- *2026.05.26*: &nbsp;🎓 Successfully completed my M.S. thesis defense at Sichuan University.
- *2026.02.19*: &nbsp;🎉 Our first-author work *“Weakly solvated functional additive-mediated rapid intra-phase and cross-interface Na⁺ transport kinetics to enable fast-charging and long-life sodium metal batteries”* was accepted by *Journal of Energy Chemistry*.
- *2025.12*: &nbsp;🎉 Our work *“Multipaths Li⁺ Migration and In Situ Interfacial Alloying of Composite Solid‑State Electrolyte Enables High‑Performance All‑Solid‑State Lithium Metal Batteries”*, in which I contributed theoretical calculations, was accepted by *Small*.
- *2025.11*: &nbsp;🎉 Joined the **AI4PhysSci Lab @ HKUST** as a Research Assistant (supervised by Prof. Lixue Cheng), working on AI4S.


# 📝 Publications 

[ResearchClawBench: A Benchmark for End-to-End Autonomous Scientific Research](https://arxiv.org/abs/2606.07591)

Wanghan Xu, Shuo Li, Tianlin Ye, Qinglong Cao, Yixin Chen, Hengjian Gao, Yiheng Wang, Qi Li, Kun Li, Sheng Xu, Shengdu Chai, Fangchen Yu, Xiangyu Zhao, Zhangrui Zhao, Weijie Ma, Zijie Guo, Haoyu Zhou, **Haoxiang Yin**, Lixue Cheng, Chaofan Hu, Haoxuan Li, Lu Mi, et al.

*arXiv:2606.07591* (2026)

- Introduces ResearchClawBench, a benchmark for evaluating end-to-end autonomous scientific research across 40 tasks from 10 scientific domains using paper-grounded tasks, hidden target papers, and expert-curated multimodal rubrics.
- Contributed chemistry-domain support to help align benchmark tasks and evaluation considerations with scientific practice.

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JEC</div><img src='images/JEC.png' alt="Journal of Energy Chemistry paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Weakly solvated functional additive-mediated rapid intra-phase and cross-interface Na⁺ transport kinetics to enable fast-charging and long-life sodium metal batteries](https://doi.org/10.1016/j.jechem.2026.02.042)

**Hao-Xiang Yin**, Guo-Rui Zhu, Ying-Ying Zhang, Zhi Wang, Xiu-Li Wang, Gang Wu

*Journal of Energy Chemistry* 117 (2026) 622–634

- Proposed a weakly solvated functional additive (DMTFOS) strategy that synchronizes bulk-electrolyte transport, SEI migration, and interfacial desolvation in sodium metal batteries.
- Revealed that DMTFOS weakens Na⁺ solvation and promotes a robust NaF/Na₂O-rich SEI, reducing key kinetic barriers and enabling Na₃V₂(PO₄)₃||Na cells to retain ~100% capacity after 1000 cycles at 1 C and 81.5% capacity after 2000 cycles at 8 C.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Small</div><img src='images/small.png' alt="Small paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multipaths Li⁺ Migration and In Situ Interfacial Alloying of Composite Solid‑State Electrolyte Enables High‑Performance All‑Solid‑State Lithium Metal Batteries](https://onlinelibrary.wiley.com/doi/full/10.1002/smll.202509107)

Ying‑Ying Zhang, Xin‑Rui Xiao, **Hao‑Xiang Yin**, Qing‑Song Liu, Xiu‑Li Wang, Guo‑Rui Zhu, Gang Wu, Yu‑Zhong Wang

- Performed DFT (Gaussian) and MD (GROMACS) simulations to analyze Li⁺ migration pathways and interfacial alloying behavior in BiF₃‑containing composite solid‑state electrolytes, supporting the experimental design and mechanistic understanding.
</div>
</div>


# 🔬 Research Experience

### Machine Learning–Assisted High‑Throughput Screening of Fluorinated Electrolytes for Batteries  (Lead Researcher) · 2025–present
- Built an AI4Electrolyte workflow integrating literature mining, molecular-space definition, staged molecular generation, DFT/MD screening, and LLM-assisted candidate ranking for fluorinated liquid-electrolyte discovery.
- Curated a literature-derived seed library of 822 unique fluorinated electrolyte molecules and expanded it through a 10-stage PubChem-validated generation workflow to a 24,327-molecule chemical space.
- Compared ECFP/Morgan, SMILES Transformer, and GROVER representations, using SMILES Transformer as the primary fine-grained molecular space for cluster-guided generation and chemical-space analysis.
- Constructed reusable AutoDFT and AutoMD workflows, including 785 complete opt+SP+ESP DFT records and an authoritative MD result table for downstream descriptor analysis.
- Developed a constrained DFT-informed LLM virtual-screening pipeline in which models rank supplied candidate IDs from structured candidate cards, followed by output validation, aggregation, and blinded expert review. Manuscript in preparation.

### Weakly Solvated Functional Additive Design for Sodium Battery Electrolytes  (Master’s Research Project, Lead Researcher) · 2023–2026
- Proposed a weakly solvated functional additive strategy using DMTFOS to jointly accelerate Na⁺ transport in the bulk electrolyte, through the SEI, and across the electrolyte–electrode interface.
- Combined DFT, MD, spectroscopy, electrochemical kinetics, and DRT analysis to connect loose Na⁺ solvation, NaF/Na₂O-rich SEI chemistry, and stabilized charge-transfer relaxation behavior.
- Demonstrated fast-charging and long-life Na₃V₂(PO₄)₃||Na full cells, including ~100% capacity retention after 1000 cycles at 1 C and 81.5% retention after 2000 cycles at 8 C.
- Published the work as a first-author article in *Journal of Energy Chemistry*.


# 🎖 Honors and Awards
- Awarded the **First Prize of the 2025–2026 AFCONA Social Scholarship**.
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

**Language**
- Mandarin Chinese; English (IELTS 6.5).

**Experimental Chemistry**
- Spectroscopic and materials characterization; full battery-testing workflow from cell assembly to electrochemical evaluation and data analysis.

**Computational Chemistry**
- First-principles calculations with Gaussian and VASP.
- Molecular dynamics simulations with GROMACS, Materials Studio, and LAMMPS.

**Computing & AI**
- Python, Pandas, NumPy, Matplotlib, and LaTeX for scientific computing, visualization, and writing.
- MAS (multi-agent systems), machine learning, and vibecoding with Codex, Claude Code, Hermes, and related agentic coding tools.


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
