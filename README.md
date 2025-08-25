# Structure-based Molecule Generation (SBMG)

**Structure-based molecule generation (SBMG)** involves using three-dimensional structural information of biological targets, such as protein binding pockets, to **generate, optimize or link small molecules** for drug development. Unlike traditional ligand-based approaches, SBMG methods are **target-aware**, integrating the spatial and chemical characteristics of binding sites into the generation process. This approach enables the de novo creation of novel compounds, the optimization of known lead compounds, and the design of linkers for complex molecules, such as PROTACs. Advancements in **deep generative models, molecular simulation, and structural biology** have made SBMG a pivotal component of modern **structure-based drug discovery (SBDD)**.

---

## 📚 Contents

1.  [Structure-based de novo Molecule Generation](#structure-based-de-novo-molecule-generation)
2.  [Structure-based Molecule Optimization](#structure-based-molecule-optimization)
3.  [Structure-based Linker Design](#structure-based-linker-design)

---

### Structure-based de novo Molecule Generation
*Generating molecules from scratch within the 3D binding pocket of a target protein.*

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>


| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2025 OpenReview** | **PoseCheck: Generative Models for 3D Structure-based Drug Design Produce Unrealistic Poses.** | [Paper](https://openreview.net/pdf?id=xoUUCS9IGl)  | |
| **2025 OpenReview** | **Decomposed Direct Preference Optimization for Structure-Based Drug Design.** | [Paper](https://openreview.net/pdf?id=blSYKTWurU)  | |
| **2025 ICML Workshop** | **3D-SBDD meets LLM: Towards FDA-Level Drug Design.** | [Paper](https://openreview.net/attachment?id=J5AkfIKTmE&name=pdf)  |
| **2025 ICML** | **CombiMOTS: Combinatorial Multi-Objective Tree Search for Dual-Target Molecule Generation.** | [Paper](https://openreview.net/pdf?id=FSlTEObdLl)  [Code](https://github.com/Tibogoss/CombiMOTS) | Dual-Target |
| **2025 ICML** | **Enhancing Ligand Validity and Affinity in Structure-Based Drug Design with Multi-Reward Optimization.** | [Paper](https://openreview.net/pdf?id=gmFeso9sXJ) |
| **2025 ICLR** | **Complex Binding Graph Benchmark is a benchmark for generative target-aware molecule design.** | [Paper](https://arxiv.org/pdf/2406.10840)  [Code](https://github.com/EDAPINENUT/CBGBench) | Benchmark |
| **2024 Nat. Mach. Intell.** | **Generation of 3D molecules in pockets via a language model.** | [Paper](https://www.nature.com/articles/s42256-023-00775-6)  [Code](https://github.com/stonewiseAIDrugDesign/Lingo3DMol) |
| **2024 CoRR** | **SIU: A Million-Scale Structural Small Molecule-Protein Interaction Dataset for Unbiased Bioactivity Prediction.** | [Paper](https://arxiv.org/pdf/2406.08961v1)  [Code](https://github.com/bowen-gao/SIU) | Dataset |
| **2024 Nat. Mach. Intell.** | **PocketFlow is A data-and-knowledge-driven structure-based molecular generative model.** | [Paper](https://www.nature.com/articles/s42256-024-00808-8)  [Code](https://github.com/Saoge123/PocketFlow) |
| **2024 Nat. Commun.** | **A 3D molecular generative framework for interaction-guided drug design.** | [Paper](https://www.nature.com/articles/s41467-024-47011-2)  [Code](https://github.com/ACE-KAIST/DeepICL) |
| **2024 Nat. Commun.** | **A dual diffusion model enables 3D molecule generation and lead optimization based on target pockets.** | [Paper](https://www.nature.com/articles/s41467-024-46569-1)  [Code](https://github.com/Layne-Huang/PMDM/tree/main) |
| **2024 Nat. Comput. Sci.** | **Structure-based drug design with equivariant diffusion models.** | [Paper](https://www.nature.com/articles/s43588-024-00737-x.pdf)  [Code](https://github.com/arneschneuing/DiffSBDD) |  |
| **2024 NeurIPS** | **De novo Drug Design using Reinforcement Learning with Multiple GPT Agents.** | [Paper](https://arxiv.org/pdf/2401.06155)  [Code](https://github.com/HXYfighter/MolRL-MGPT) |
| **2024 ICLR Workshop** | **Fine-tuning Pocket-conditioned 3D Molecule Generation via Reinforcement Learning.** | [Paper](https://openreview.net/pdf?id=hlzRzr9ksu)  [Code](https://github.com/deargen/Pocket2Mol_RL_public) |
| **2023 Nat. Mach. Intell.** | **ResGen is A pocket-aware 3D molecular generation model based on parallel multiscale modelling.** | [Paper](https://www.nature.com/articles/s42256-023-00712-7)  [Code](https://github.com/OdinZhang/ResGen) |
| **2023 NeurIPS** | **Functional-Group-Based Diffusion for Pocket-Specific Molecule Generation and Elaboration.** | [Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/6cdd4ce9330025967dd1ed0bed3010f5-Paper-Conference.pdf) |
| **2023 ICML** | **DecompDiff: Diffusion Models with Decomposed Priors for Structure-Based Drug Design.** | [Paper](https://arxiv.org/pdf/2403.07902)  [Code](https://github.com/bytedance/DecompDiff) |
| **2023 ICML** | **Learning Subpocket Prototypes for Generalizable Structure-based Drug Design.** | [Paper](https://openreview.net/pdf?id=gfdK6nK8AI)  [Code](https://github.com/zaixizhang/DrugGPS_ICML23) |
| **2023 ICLR** | **3D Equivariant Diffusion for Target-Aware Molecule Generation and Affinity Prediction.** | [Paper](https://arxiv.org/pdf/2303.03543)  [Code](https://github.com/guanjq/targetdiff) |
| **2023 ICLR** | **Molecule generation for target protein binding with structural motifs.** | [Paper](https://openreview.net/pdf?id=Rq13idF0F73)  [Code](https://github.com/zaixizhang/FLAG) |
| **2023 arXiv** | **GraphVF: Controllable Protein-Specific 3D Molecule Generation with Variational Flow.** | [Paper](https://arxiv.org/pdf/2304.12825) |
| **2022 NeurIPS** | **Zero-Shot 3D Drug Design by Sketching and Generating.** | [Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/96ddbf813f042e8ff891b4d6f7149bb6-Paper-Conference.pdf)  [Code](https://github.com/longlongman/DESERT) |
| **2021 NeurIPS** | **A 3D generative model for structure-based drug design.** | [Paper](https://proceedings.neurips.cc/paper_files/paper/2021/file/314450613369e0ee72d0da7f6fee773c-Paper.pdf)  [Code](https://github.com/luost26/3D-Generative-SBDD) |



</details>

---

### Structure-based Molecule Optimization
*Refining existing lead compounds using protein structural insights.*

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2025 Nat. Mach. Intell.** | **Deep lead optimization enveloped in protein pocket and its application in designing potent and selective ligands targeting LTK protein.** | [Paper](https://www.nature.com/articles/s42256-025-00997-w)  [Code](https://github.com/OdinZhang/Delete) |
| **2025 ICML** | **Empower Structure-Based Molecule Optimization with Gradient Guided Bayesian Flow Networks.** | [Paper](https://openreview.net/pdf?id=CIoBEB17FT)  [Code](https://github.com/AlgoMole/MolCRAFT) |
| **2025 arXiv** | **Structure-Based Drug Design via 3D Molecular Generative Pre-training and Sampling.** | [Paper](https://arxiv.org/pdf/2402.14315) |
| **2024 ICLR** | **DecompOpt: Controllable and Decomposed Diffusion Models for Structure-based Molecular Optimization.** | [Paper](https://arxiv.org/pdf/2403.13829)  [Code](https://github.com/bytedance/DecompOpt) |
| **2023 IJCAI** | **GPMO: Gradient Perturbation-Based Contrastive Learning for Molecule Optimization.** | [Paper](https://www.ijcai.org/proceedings/2023/0549.pdf) | |
</details>


---

### Structure-based Linker Design
*Designing linkers between two ligands using structural constraints for bifunctional drug design (e.g., PROTACs).*

<details open>
<summary><b>View Papers (Click to Expand)</b></summary>

| Year & Venue | Title | Links | Description |
| :--- | :--- | :--- | :--- |
| **2025 ICML** | **Domain-Adapted Diffusion Model for PROTAC Linker Design Through the Lens of Density Ratio in Chemical Space.** | [Paper](https://openreview.net/pdf?id=jkyUbkNJyH) |

</details>