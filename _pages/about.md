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
- *2026.08.20*: &nbsp;🎉 Our work on a bifunctional supramolecular modulator for lithium metal batteries was published in *Chemical Communications*. I performed the theoretical calculations and molecular dynamics simulations and contributed to the mechanistic analysis.
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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CC</div><img src='images/CC.png' alt="Molecular interactions and lithium solvation structures from the Chemical Communications paper, Figure 1" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A bifunctional supramolecular modulator regulating solvation and interfacial chemistry for stable lithium metal batteries](https://doi.org/10.1039/D6CC04662B)

Zhi Wang, **Hao-Xiang Yin**, Guo-Rui Zhu, Gang Wu

*Chemical Communications* (2026), published online 20 August 2026

- Identified thiophanate-methyl (TM) as a bifunctional additive that regulates Li⁺ solvation through hydrogen bonding with anions and promotes an anion-derived solid electrolyte interphase (SEI).
- Performed all theoretical calculations and MD simulations and contributed to the analysis and mechanistic discussions, linking molecular interactions to improved lithium metal battery stability.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">JEC</div><img src='images/JEC.png' alt="Journal of Energy Chemistry paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Weakly solvated functional additive-mediated rapid intra-phase and cross-interface Na⁺ transport kinetics to enable fast-charging and long-life sodium metal batteries](https://doi.org/10.1016/j.jechem.2026.02.042)

**Hao-Xiang Yin**, Guo-Rui Zhu, Ying-Ying Zhang, Zhi Wang, Xiu-Li Wang, Gang Wu

*Journal of Energy Chemistry* 117 (2026) 622–634

- Proposed a weakly solvated functional additive (DMTFOS) strategy that synchronizes bulk-electrolyte transport, SEI migration, and interfacial desolvation in sodium metal batteries.
- Revealed that DMTFOS weakens Na⁺ solvation and promotes a robust NaF/Na₂O-rich SEI, reducing key kinetic barriers and enabling Na₃V₂(PO₄)₃ full cells paired with Na metal to retain ~100% capacity after 1000 cycles at 1 C and 81.5% capacity after 2000 cycles at 8 C.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Small</div><img src='images/small.png' alt="Small paper" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Multipaths Li⁺ Migration and In Situ Interfacial Alloying of Composite Solid‑State Electrolyte Enables High‑Performance All‑Solid‑State Lithium Metal Batteries](https://onlinelibrary.wiley.com/doi/full/10.1002/smll.202509107)

Ying‑Ying Zhang, Xin‑Rui Xiao, **Hao‑Xiang Yin**, Qing‑Song Liu, Xiu‑Li Wang, Guo‑Rui Zhu, Gang Wu, Yu‑Zhong Wang

*Small* 22 (2026), e09107

- Introduced porous BiF₃ fillers into PEO-based solid electrolytes to facilitate Li⁺ transport and form a protective interphase containing LiF and lithium–bismuth alloys.
- Performed all theoretical calculations and MD simulations to investigate ion binding and Li⁺ diffusion, and contributed to the analysis and mechanistic discussions.
</div>
</div>


# 🔬 Research Experience

### FLEX: LLM-Assisted Discovery of Fluorinated Electrolytes

*Lead Researcher · 2025–present · Manuscript in preparation*

- Developed FLEX to identify fluorinated additives for lithium metal batteries, combining literature mining, molecular-space expansion, quantum-chemical descriptors, and LLM-assisted screening.
- Expanded 822 literature-derived molecules into a 24,327-molecule library through ten stages of generation and PubChem identity checks; assembled a screening pool of 21,131 generated molecules with DFT descriptors.
- Completed screening with five LLMs, incorporating preliminary experimental feedback, commercial availability, and blinded expert review to prioritize candidates for further testing.

### Supramolecular Regulation of Lithium Battery Electrolytes

*Theory and Simulation Lead · [Chemical Communications](https://doi.org/10.1039/D6CC04662B), 2026*

- Performed all theoretical calculations and MD simulations to investigate thiophanate-methyl (TM) as a bifunctional additive in ether-based electrolytes.
- Analyzed molecular binding, frontier orbitals, and Li⁺ coordination to connect TM–anion hydrogen bonding with changes in solvation and interfacial reduction tendencies.
- Contributed to data analysis and mechanistic discussions, integrating computational and experimental evidence to explain the formation of a protective SEI enriched in LiF, Li₂S, and Li₃N.

### Weakly Solvated Functional Additives for Sodium Batteries

*Master’s Research Project, Lead Researcher · 2023–2026 · [Journal of Energy Chemistry](https://doi.org/10.1016/j.jechem.2026.02.042), first author*

- Proposed DMTFOS as a weakly solvated functional additive to improve Na⁺ transport in the bulk electrolyte, through the SEI, and across the electrode–electrolyte interface.
- Combined DFT and MD with spectroscopy, electrochemical kinetics, and distribution of relaxation times (DRT) analysis to relate Na⁺ solvation, NaF/Na₂O-rich SEI chemistry, and interfacial stability.
- Demonstrated long-life Na₃V₂(PO₄)₃ full cells paired with Na metal, retaining ~100% capacity after 1000 cycles at 1 C and 81.5% after 2000 cycles at 8 C.

### Ion Transport and Interfacial Stability in Composite Solid Electrolytes

*Theory and Simulation Lead · [Small](https://doi.org/10.1002/smll.202509107), 2026*

- Performed all theoretical calculations and MD simulations for BiF₃-filled PEO composite solid electrolytes for all-solid-state lithium metal batteries.
- Used DFT to examine Li⁺ and TFSI⁻ binding and MD to quantify Li⁺ diffusion, supporting the role of BiF₃ in promoting salt dissociation and ion transport.
- Contributed to data analysis and mechanistic discussions, connecting enhanced bulk transport with experimental evidence for a protective interphase containing LiF and lithium–bismuth alloys.


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
- Mandarin Chinese; English (IELTS 7.0; Listening: 7.5, Reading: 6.5, Speaking: 6.5, Writing: 6.5).

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
