<h1 align="center">Zheng Wang</h1>

<p align="center">
  M.S. Candidate, Department of Automation, Tsinghua University<br/>
  <a href="https://www.leaplab.ai">LEAP Lab</a> &middot; advised by Prof. <a href="https://www.gaohuang.net">Gao Huang</a><br/>
  <sub>he/him &nbsp;&middot;&nbsp; Beijing, China &nbsp;&middot;&nbsp; <a href="mailto:george.tsinghua@gmail.com">george.tsinghua@gmail.com</a></sub>
</p>


---

## About

I work at the intersection of **large language models, agent systems, and embodied intelligence**.
My recent research is organized around three questions:

1. *How should multiple agents coordinate so that emergent behavior is reliable, not merely plausible?*
2. *What is the right inference substrate for an agent-native workload — one where prefixes, tools, and policies, rather than tokens, dominate the cost surface?*
3. *Can hierarchical, experience-accumulating planners take LLMs out of the simulator and onto real construction sites?*

In parallel, I founded **SeamLess AI**, where the same questions are stress-tested against industrial robotics, judicial agents, and CAx software at scale.

## Research Interests

- **Agent Systems** — multi-agent coordination, agent memory, prompt-free workflows, A2A / MCP protocols
- **Agent-Native Inference** — KV-cache governance, stable-prefix protocols, parallel scheduling on Ascend (MindIE / CANN)
- **Embodied Intelligence** — hierarchical planning (TSP &times; LLM &times; RL &times; PDDL), sim-to-real for industrial robots
- **Retrieval and Long-Form Reasoning** — score-gated termination, access-driven materialization for RAG

## Selected Publications

- **CostRAG**: *Free Signals Are Enough — Pareto-Improving Long-Form RAG via Score-Gated Termination and Access-Driven Materialization.* &nbsp; **Under review, CIKM 2026.** *First author.*
- **HEAT**: *Hierarchical Thinking with Long-Term Experience Accumulation and Test-Time Evolvement in Real-World Robotic Environments.* *First author.*
- Z. Wang et al. *A Frequency-Domain Scheme for High-Speed Telemetry Downhole Wireline Communication.* **IMCCC 2015** (EI). *First author.*
- *Vertical Magnetic Field and Its Analytic-Signal Applicability in Oil-Field Underground Pipeline Detection.* **Journal of Geophysics and Engineering**, 2015 (SCI).

## Patents (sole inventor)

- *Anomaly Monitoring Method, Device, and Electronic Equipment* — **CN111309539A**
- *Resource Scheduling Method, Device, Electronic Equipment, and Storage Medium* — **CN112667398A**

## Projects

**Cooragent**— an open-source multi-agent collaboration framework from LEAP Lab. Designed and shipped end-to-end; covered as a SOTA framework by *Synced (机器之心)* and roughly ten other outlets.

**Telos** — an *agent-native* inference engine targeting Ascend hardware. Combines fleet parallelism, a stable-prefix protocol (PIN &rarr; FOLD &rarr; DROP), and token-efficient tool interfaces; integrated with MindIE / CANN.

**HEAT (Robotic Plastering)** — joint work with Country Garden / Bright Dream Robotics: the first LLM-driven plastering robot deployed on real construction sites. A three-level planner — layout-TSP &times; cross-room LLM &times; in-room LLM + RL + CV + PDDL — yields **+34.7%** over LLM+P and **+11.5%** over Lamma-P on VirtualHome, with a **90%** task-completion rate in field deployment.

**Autonomous Cardiac-Ultrasound Robot** — with Lingshi Tech: a full perception &ndash; decision &ndash; control loop. Featured as a *Nature Biomedical Engineering* Research Highlight by Editor-in-Chief Rita Strack.

## Education

- **M.S., Automation**, Tsinghua University, *2022 &ndash; 2026*. LEAP Lab, advised by Prof. Gao Huang (DenseNet; CVPR 2017 Best Paper).
- **M.S., Information &amp; Communication Engineering**, China University of Petroleum (Beijing), *2013 &ndash; 2016*. Ranked **1st** in cohort; Outstanding Graduate Student of Beijing Municipality.

## Selected Honors

- *Dream-Launch / Kunpeng-Ascend Seed Program*, Tsinghua University &times; Huawei
- *Global Runner-up*, Tsinghua Sanchuang Entrepreneurship Competition (Seed Group)
- *Champion*, Tsinghua Guoqiang Institute Dual-Innovation Competition (Seed Group)
- *Bronze Award*, Huawei Ascend AI Innovation Competition
- *Outstanding Graduate Student*, Beijing Municipal Commission of Education

## Industry Track (condensed)

Before returning to research I spent close to a decade building large-scale systems:
kernel-level network virtualization at **H3C** &rarr; a 100k+ VM cloud platform at **iQiyi** &rarr; online-serving and ranking infrastructure at **Xiaohongshu** (billion-plus daily requests) &rarr; heterogeneous edge &ndash; cloud computing at the **CASC Ninth Academy**. That trajectory — *systems &rarr; platform &rarr; algorithms &rarr; agents* — is what I now bring to academic work on agent infrastructure.

---

<sub>This page is intentionally terse. Full CV available on request. Last updated: May 2026.</sub>
