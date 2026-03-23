# BIODRONES  
**Biomimetic and Innovative Optimized hydrodynamic concepts of high-efficiency underwater gliding DRONES for ocean research**

---

## 🌊 Overview

**BIODRONES** is a research project focused on the simulation-based design and optimization of bio-inspired autonomous underwater gliders (AUGs).

This repository acts as the **central entry point and coordination hub** of the project.

The project integrates:

- Physics-based and reduced-order hydrodynamic modeling (RANS / potential flow)
- Multi-fidelity surrogate modeling
- Design-space dimensionality reduction (PME, PD-PME, PI-PME)
- Adaptive sampling and optimization strategies
- High-performance computing workflows

The primary application case is the development and optimization of **bio-inspired underwater glider configurations**.

---

## 🌐 Project Links

- 🌍 **Project Website**  
  https://sites.google.com/inm.cnr.it/biodrones

- 📚 **Zenodo Community (data, datasets, and releases)**  
  https://zenodo.org/communities/biodrones/

---

## 🧩 Project Structure

All project components are organized as dedicated repositories within the  
**cnr-inm-mao** organization.

### Core Repositories

- 🔧 **Software**  
  `pme-toolkit`  
  Design-space dimensionality reduction framework (PME, PI-PME, PD-PME)

---

### 🚧 Planned Repositories

- 🐋 **Manta Parametrization Tools**  
  `sgm`  
  Shape generation and geometric modeling tools (CAD, STL workflows)

- ⚙️ **Optimization Framework**  
  `samoa`  
  Surrogate-based adaptive multi-fidelity optimization framework

---

## 🔧 Software Developed within BIODRONES

The project contributes to the development of advanced computational tools for simulation-based design optimization:

- **PME-toolkit**  
  Open-source framework for design-space dimensionality reduction  
  🔗 https://github.com/cnr-inm-mao/pme-toolkit  
  - 📦 Available on [PyPI](https://pypi.org/project/pme-toolkit/)  
  - 📄 Submitted to JOSS
    
---

## 📦 Deliverables

Official project deliverables are available through the project website.

Main categories include:

- Design specifications
- CAD model definitions
- CFD configuration and validation reports
- Optimization methodology development
- Preliminary and advanced shape optimization results

---

## 📊 Data Availability

Simulation data, datasets, and processed results are released through the  
**BIODRONES Zenodo community**:

https://zenodo.org/communities/biodrones/

---

## 📖 Scientific Outputs

The project contributes to research in:

- Simulation-Based Design Optimization (SBDO)
- Multi-fidelity modeling
- Reduced-order and surrogate models
- Bio-inspired marine vehicle design
- Explainable optimization methodologies

Publications are collected and curated in the project website and Zenodo community.

---

## 💻 High-Performance Computing

Large-scale CFD simulations are performed on HPC infrastructures, including:

- CINECA (Leonardo)
- Institutional clusters

Automation pipelines integrate OpenFOAM-based solvers with surrogate modeling workflows.

---

## 🏛️ Governance

BIODRONES is developed within the  
**cnr-inm-mao** organization.

    cnr-inm-mao
    ├── biodrones (this repository)
    ├── pme-toolkit
    ├── sgm (planned)
    ├── samoa (planned)

---

## 🤝 Contact

For scientific collaboration or project information:

**Matteo Diez**  
CNR-INM – Institute of Marine Engineering  
Rome, Italy  
📧 matteo.diez@cnr.it  

---

## 📄 License

Unless otherwise specified in sub-repositories, licensing is defined at repository level.

---

## 🙏 Acknowledgments

CNR-INM is grateful to the Italian Ministry of University and Research (MUR) through the PRIN 2022 program, project **BIODRONES** (20227JNM52 – CUP B53D23005560006).

The authors also acknowledge the CINECA award under the ISCRA-B grant **HP10BCZZBF** and ISCRA-C grant **HP10CJM3DH**, for the availability of high-performance computing resources and technical support.

---

## 💰 Funding

<p align="center">
  <img src="funding.png" alt="PRIN 2022" width="750"/>
</p>

<p align="center">
  <b>PRIN 2022 – Project BIODRONES</b><br>
  Project Code: 20227JNM52<br>
  CUP: B53D23005560006
</p>
