---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

# Research

Our group develops **theoretical chemistry, computational spectroscopy, and artificial intelligence methods** to understand complex chemical systems across multiple scales—from electronic excitations and molecular interactions to dynamic interfaces and heterogeneous materials.

A central theme of our research is the **structure–dynamics–spectrum relationship**. We develop accurate computational approaches to predict multimodal spectroscopic signals, establish microscopic connections between spectra and molecular structures, and solve challenging inverse problems that extract structural and chemical information from experimental measurements.

Our research spans three interconnected directions:

1. **Theoretical Chemistry and Computational Spectroscopy（理论化学与计算光谱学）**
2. **AI-Driven Multimodal Spectroscopy for Catalysis and Electrochemistry（面向催化与电化学的人工智能多模态谱学）**
3. **Water, Interfaces, and Matter under Confinement and Extreme Conditions（水、界面与限域和极端条件下的物质）**

---

## 1. Theoretical Chemistry and Computational Spectroscopy（理论化学与计算光谱学）

This research is supported by the **National Natural Science Foundation of China (国家自然科学基金)**, including the **Excellent Young Scientists Fund (Overseas) (优秀青年科学基金项目（海外）)** and the **General Program (面上项目)**.

We develop theoretical and computational methods for connecting the electronic and molecular structures of complex chemical systems with their spectroscopic observables. Our goal is to bridge fundamental theoretical chemistry, molecular simulation, and experimentally measurable spectra.

### 1.1 Electronic-Structure Methods for Ground and Excited States（基态与激发态电子结构方法）

We develop and apply advanced electronic-structure methods to describe chemical bonding, electronic excitation, excitons, and charge-transfer processes in molecular and condensed-phase systems.

Our research integrates ideas from **density functional theory and quantum chemistry** for ground-state electronic structures, together with many-body approaches such as **GW and the Bethe–Salpeter equation (BSE)** for quasiparticle and excited-state properties.

A major focus is to understand how electronic excitations interact with complex molecular environments, including hydrogen-bond networks, ionic solvation shells, interfaces, low-dimensional materials, and structurally disordered systems.

### 1.2 First-Principles Multimodal Computational Spectroscopy（第一性原理多模态计算光谱学）

We develop computational methods for predicting and interpreting a broad range of spectroscopic observables, including:

* **Vibrational spectroscopy（振动光谱）**, such as infrared, Raman, and sum-frequency generation spectroscopy;
* **Electronic and excited-state spectroscopy（电子与激发态光谱）**, such as optical absorption and X-ray absorption spectroscopy;
* **Nuclear magnetic resonance spectroscopy（核磁共振谱学）** for molecular and condensed-phase systems.

Rather than treating each spectroscopy technique independently, we aim to establish a unified theoretical framework in which different spectroscopic modalities provide complementary projections of the same underlying molecular and electronic structure.

### 1.3 Molecular Dynamics and Accelerated Simulation of Complex Chemical Environments（复杂化学环境的分子动力学与加速模拟）

Many experimentally relevant spectra arise from dynamic and heterogeneous molecular environments that cannot be represented by a single optimized structure.

We therefore develop and apply **first-principles molecular dynamics and accelerated molecular simulation methods** to sample realistic structural ensembles and dynamic processes. Machine-learning interatomic potentials and active-learning strategies are integrated with electronic-structure and spectroscopy calculations to reach spatial and temporal scales inaccessible to conventional first-principles simulations.

Our long-term goal is to establish an integrated computational workflow:

> **Electronic structure（电子结构） → Molecular dynamics（分子动力学） → Statistical ensembles（统计系综） → Spectroscopy（光谱） → Microscopic mechanism（微观机制）**

### Selected Publications

1. **F. Tang**, D. Y. Qiu, and X. Wu,
   *Optical Absorption Spectroscopy Probes Water Wire and Its Ordering in a Hydrogen-Bond Network*,
   **Physical Review X**, 2025, **15**, 011048.

2. **F. Tang**, Z. Li, C. Zhang, S. G. Louie, R. Car, D. Y. Qiu, and X. Wu,
   *Many-Body Effects in the X-ray Absorption Spectra of Liquid Water*,
   **Proceedings of the National Academy of Sciences of the United States of America**, 2022, **119**, e2201258119.

3. **F. Tang**, K. Shi, and X. Wu,
   *Exploring the Impact of Ions on Oxygen K-Edge X-ray Absorption Spectroscopy in NaCl Solution Using the GW–Bethe–Salpeter-Equation Approach*,
   **The Journal of Chemical Physics**, 2023, **159**, 174501.

4. **F. Tang**, J. Xu, D. Y. Qiu, and X. Wu,
   *Nuclear Quantum Effects on the Quasiparticle Properties of the Chloride Anion Aqueous Solution within the GW Approximation*,
   **Physical Review B**, 2021, **104**, 035117.

---

## 2. AI-Driven Multimodal Spectroscopy for Catalysis and Electrochemistry（面向催化与电化学的人工智能多模态谱学）

This research is supported by the **National Key R&D Program of China (国家重点研发计划)** in **Catalysis Science (催化科学)** and related research programs in computational spectroscopy and artificial intelligence.

Spectroscopy is one of the most important tools for identifying active structures, reaction intermediates, solvation environments, and dynamic transformations in chemistry. However, interpreting spectra from realistic catalytic and electrochemical systems remains challenging because these systems are heterogeneous, dynamic, and often characterized by non-unique structure–spectrum relationships.

We develop **physics-informed and interpretable artificial intelligence methods** to transform spectroscopy from a primarily experience-driven characterization tool into a quantitative approach for structural inference and chemical mechanism discovery.

### 2.1 Machine-Learning-Accelerated Computational Spectroscopy（机器学习加速的计算光谱学）

High-level spectroscopy calculations are often orders of magnitude more expensive than molecular simulations, creating a major bottleneck for studying realistic dynamic systems.

We develop machine-learning models that reproduce first-principles spectroscopic observables across large configurational spaces. These models enable the generation of statistically converged spectra from long molecular trajectories and large structural ensembles.

Our current interests include ML-accelerated modeling of:

* X-ray absorption spectra（X射线吸收谱）;
* NMR chemical shifts（核磁共振化学位移）;
* Infrared and Raman spectra（红外与拉曼光谱）;
* Surface-specific vibrational spectra（表面特异性振动光谱）;
* Optical and excited-state spectra（光学与激发态光谱）.

The ultimate objective is not merely to predict spectra faster, but to enable **spectroscopy calculations at the same statistical scale as molecular dynamics simulations**.

### 2.2 Physics-Informed Forward and Inverse Spectroscopy（物理信息驱动的光谱正问题与反问题）

Conventional computational spectroscopy primarily addresses the forward problem:

> **Structure（结构） → Spectrum（光谱）**

A more challenging problem is the inverse direction:

> **Spectrum（光谱） → Structure（结构）**

The inverse problem is frequently ill-posed because distinct molecular environments can produce similar spectral features. We develop physics-informed deep-learning models that incorporate chemical constraints, local structural representations, spectral physics, uncertainty quantification, and multimodal information.

Our research seeks to answer several fundamental questions:

* **How much structural information is contained in a spectrum?**
  **一张光谱中究竟包含多少结构信息？**

* **Which structural descriptors can be uniquely inferred from a particular spectroscopy?**
  **哪些结构描述符能够由特定光谱唯一确定？**

* **When is one spectroscopy insufficient, and how can multiple spectroscopic modalities be combined?**
  **单一光谱何时信息不足？多种光谱模态应如何协同？**

By addressing these questions quantitatively, we aim to establish the theoretical foundation for intelligent spectral interpretation.

### 2.3 Multimodal Structure–Spectrum–Property Models for Catalysis and Electrochemistry（面向催化与电化学的多模态谱–构–效模型）

Real chemical systems are rarely characterized by a single spectroscopy.

We develop multimodal models that integrate theoretical and experimental information from **XAS, vibrational spectroscopy, NMR, molecular simulation, electronic structure, and physicochemical properties**.

For catalytic systems, our goal is to identify dynamic active sites, adsorbate configurations, reaction intermediates, and structural transformations under working conditions.

For electrochemical systems, we focus on the relationship among ion solvation, aggregation, interfacial organization, molecular dynamics, spectroscopic signatures, and macroscopic properties.

The long-term vision is to establish an interpretable framework:

> **Structure + Dynamics（结构与动力学） → Multimodal Spectra（多模态光谱） → Chemical Mechanism（化学机制） → Materials Design（材料设计）**

### Selected Publications

1. F. Xu, W. Guo, F. Wang, L. Yao, H. Wang, **F. Tang**, Z. Gao, L. Zhang, W. E, Z.-Q. Tian, and J. Cheng,
   *Towards a Unified Benchmark and Framework for Deep Learning-Based Prediction of Nuclear Magnetic Resonance Chemical Shifts*,
   **Nature Computational Science**, 2025, **5**, 292–300.

2. Q. You, Y. Sun, F. Wang, J. Cheng, and **F. Tang**,
   *Decoding the Competing Effects of Dynamic Solvation Structures on NMR Chemical Shifts of Battery Electrolytes via Machine Learning*,
   **Journal of the American Chemical Society**, 2025, **147**, 14667–14676.

3. X. Du, J. Cheng, and **F. Tang**,
   *Machine-Learning Accelerated Computational Spectroscopy Reveals Vibrational Signature of the Oxidation Level of Graphene in Contact with Water*,
   **The Journal of Physical Chemistry Letters**, 2026, **17**, 1471–1478.

4. X. Du, W. Shao, C. Bao, L. Zhang, J. Cheng, and **F. Tang**,
   *Revealing the Molecular Structures of α-Al₂O₃(0001)–Water Interface by Machine Learning-Based Computational Vibrational Spectroscopy*,
   **The Journal of Chemical Physics**, 2024, **161**, 124702.
   *JCP Editor's Pick.*

---

## 3. Water, Interfaces, and Matter under Confinement and Extreme Conditions（水、界面与限域和极端条件下的物质）

This research is supported by the **National Key R&D Program of China (国家重点研发计划)** in **Nanoscience Frontiers (纳米前沿)** and the **Xiamen Natural Science Foundation Young Scientists Program (厦门市自然科学基金青年项目)**.

Water and aqueous interfaces provide a unique platform for understanding how collective molecular interactions give rise to complex structural, dynamical, electronic, and spectroscopic phenomena.

We combine molecular simulation, advanced electronic-structure theory, computational spectroscopy, and machine learning to investigate hydrogen-bond networks across liquid water, ice, aqueous electrolytes, interfaces, and confined environments.

### 3.1 Hydrogen-Bond Networks, Proton Ordering, and Excitonic States（氢键网络、质子有序与激子态）

The hydrogen-bond network of water is dynamic, cooperative, and strongly connected to its electronic excitation properties.

We investigate how local and long-range hydrogen-bond organization controls:

* Water-wire formation（水线形成）;
* Proton ordering and disordering（质子有序与无序）;
* Intermolecular charge transfer（分子间电荷转移）;
* Exciton localization and delocalization（激子局域化与离域化）;
* Oscillator strength（振子强度）;
* Optical and X-ray absorption features（光学与X射线吸收特征）.

By combining molecular simulations with many-body excited-state calculations, we seek to establish direct connections between **hydrogen-bond topology and measurable electronic spectra**.

A central question is whether spectroscopic observables can provide quantitative fingerprints of collective structures that are difficult to identify using conventional structural characterization alone.

### 3.2 Molecular Structure and Dynamics at Complex Interfaces（复杂界面的分子结构与动力学）

Interfaces govern a broad range of chemical processes, including catalysis, electrochemistry, energy storage, membrane transport, and environmental chemistry.

We investigate molecular structures and dynamics at:

* Solid–water interfaces（固–液界面）;
* Electrochemical interfaces（电化学界面）;
* Liquid–vapor interfaces（液–气界面）;
* Graphene and two-dimensional material interfaces（石墨烯与二维材料界面）;
* Oxide–water interfaces（氧化物–水界面）;
* Multicomponent liquid interfaces（多组分液体界面）.

Our research combines molecular dynamics with surface-sensitive and element-specific spectroscopy to determine how hydrogen bonding, surface chemistry, oxidation state, ion adsorption, and molecular orientation collectively shape interfacial behavior.

An important objective is to develop computational spectroscopy as a **quantitative bridge between molecular simulation and operando experiments**.

### 3.3 Water and Aqueous Systems under Nanoconfinement and Extreme Conditions（纳米限域与极端条件下的水及含水体系）

Water behaves differently when confined to molecular dimensions or subjected to extreme thermodynamic conditions.

We study water and aqueous solutions in low-dimensional confinement, disordered nanoporous environments, and unusual thermodynamic regimes. Particular interests include:

* Hydrogen-bond restructuring（氢键网络重构）;
* Ion-induced disruption and reconstruction of water networks（离子诱导的水网络破坏与重构）;
* Anomalous molecular transport（反常分子输运）;
* Phase transitions and proton ordering（相变与质子有序）;
* Nuclear quantum effects（核量子效应）;
* Spectroscopic signatures of confined and extreme water（限域与极端水的光谱特征）.

By linking molecular structure, dynamics, and spectroscopy, we aim to understand how confinement and extreme environments reshape the collective behavior of water and aqueous matter.

### Selected Publications

1. Y. Wang, **F. Tang**, X. Yu, K.-Y. Chiang, C.-C. Yu, T. Ohto, Y. Chen, Y. Nagata, and M. Bonn,
   *Interfaces Govern Structure of Angstrom-Scale Confined Water Solutions*,
   **Nature Communications**, 2025, **16**, 7288.

2. Y. Wang, **F. Tang**, X. Yu, T. Ohto, Y. Nagata, and M. Bonn,
   *Heterodyne-Detected Sum-Frequency Generation Vibrational Spectroscopy Reveals Aqueous Molecular Structure at the Suspended Graphene/Water Interface*,
   **Angewandte Chemie International Edition**, 2024, **63**, e202319503.

3. **F. Tang**, T. Ohto, S. Sun, J. R. Rouxel, S. Imoto, E. H. G. Backus, S. Mukamel, M. Bonn, and Y. Nagata,
   *Molecular Structure and Modeling of Water–Air and Ice–Air Interfaces Monitored by Sum-Frequency Generation*,
   **Chemical Reviews**, 2020, **120**, 3633–3667.

4. S. Sun, **F. Tang**, S. Imoto, D. R. Moberg, T. Ohto, F. Paesani, M. Bonn, and Y. Nagata,
   *Orientational Distribution of Free OH Groups of Interfacial Water Is Exponential*,
   **Physical Review Letters**, 2018, **121**, 246101.
