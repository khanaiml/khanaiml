<div align="center">

<p>
  <img
    src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=25&duration=3200&pause=800&color=2F81F7&center=true&vCenter=true&width=900&lines=Abdullah+Khan;SciML+Researcher+%7C+AI%2FML+Engineer;Materials+%E2%80%A2+Energy+%E2%80%A2+Healthcare"
    alt="Abdullah Khan"
  />
</p>

<p style="margin:0;">
  <a href="https://www.linkedin.com/in/mrabdullahkhan">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://www.kaggle.com/abdullahkhan161101">
    <img src="https://img.shields.io/badge/Kaggle-20BEFF?style=flat-square&logo=kaggle&logoColor=white" alt="Kaggle">
  </a>
  <a href="mailto:abdullahkhan.prof@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

<p style="margin:0;">
  <img src="https://img.shields.io/badge/Upper%20Dir%2C%20KP%2C%20Pakistan-36454F?style=flat-square" alt="Location">
  <img src="https://img.shields.io/badge/Open%20to-PhD%20%7C%20Research%20%7C%20AI%2FML%20Role-2F81F7?style=flat-square" alt="Open to PhD | Research | AI/ML Role">
</p>

</div>

---

<p align="center">

<a href="#about"><strong>ABOUT</strong></a>
&nbsp;&nbsp;·&nbsp;&nbsp;
<a href="#research"><strong>PUBLICATION</strong></a>
&nbsp;&nbsp;·&nbsp;&nbsp;
<a href="#projects"><strong>PROJECTS</strong></a>
&nbsp;&nbsp;·&nbsp;&nbsp;
<a href="#data"><strong>DATA</strong></a>
&nbsp;&nbsp;·&nbsp;&nbsp;
<a href="#experience"><strong>EXPERIENCE</strong></a>
&nbsp;&nbsp;·&nbsp;&nbsp;
<a href="#education"><strong>EDUCATION</strong></a>
&nbsp;&nbsp;·&nbsp;&nbsp;
<a href="#skills"><strong>SKILLS</strong></a>

</p>

---

<a id="about"></a>

## About

I am a **Scientific Machine Learning researcher and AI/ML engineer** working at the intersection of **machine learning and the natural sciences**, with applications across **materials science, energy systems, and computational healthcare**.

My work combines scientific reasoning, machine learning, and practical engineering to build systems that are **interpretable, uncertainty-aware, robust under distribution shift, and reproducible**.

> **Does a model merely perform well or can we trust what it predicts?**

**Core domains:**  
`Scientific ML` · `Physics-Informed ML` · `Materials Informatics` · `Energy Intelligence` · `Healthcare AI` · `Reliable AI`

---

<a id="research"></a>

## PUBLICATION
<details open>
<summary><strong>Physics-Informed Materials Discovery</strong></summary>
<br>
  
### Physics-informed machine learning screening and validation of MOF/g-C₃N₄ heterojunction photocatalysts

**Chinese Journal of Physics · Elsevier · 2026** <br>
A physics-informed machine-learning workflow for large-scale screening and validation of MOF candidates for Type-II heterojunction photocatalysis with g-C₃N₄.

**20,152 MOFs → 983 high-confidence candidates** <br>
`ROC-AUC 0.912` · `Top-50 Precision 98%` · `External Recall 100%`
`+27.6 pp` over physics-rule baselines · `~20.5×` estimated screening-cost reduction

**Methods** &nbsp; `Random Forest` · `XGBoost` · `SHAP` · `Physics-Informed Descriptors` · `Butler–Mulliken Band Alignment` · `Physical Constraints`

**Interpretable drivers:** &nbsp; Metal ionic radius · linker π-conjugation · structural stability · pore accessibility

[**Source Code**](https://github.com/khanaiml/mof-gcn-ml-screening) &nbsp;&nbsp; [**Paper**](https://doi.org/10.1016/j.cjph.2026.07.025)

</details>

---

<a id="projects"></a>

## Featured Projects

<details open>
<summary><strong>01 · AI-Assisted Materials Screening</strong></summary>

<br>

A reliability-aware SciML platform for **composition-based thermodynamic stability screening of inorganic crystals**.

**Pipeline** &nbsp; `132 Magpie Descriptors` → `XGBoost` → `Calibration` → `Uncertainty` → `OOD Risk` → `Candidate Ranking`

**Benchmark** &nbsp; `ROC-AUC 0.8521` · `F1 0.7082` · `AUPR 0.7872` · `ECE 0.0246`

**Stack** &nbsp; `Python` · `XGBoost` · `FastAPI` · `Streamlit` · `SQLite`

[**Repository**](https://github.com/khanaiml/ai-materials-screening)

</details>

<details>
<summary><strong>02 · Multimodal Oncology AI</strong></summary>

<br>

Reliability-aware clinical AI combining **digital pathology and genomic transcriptomics** for colorectal cancer prognosis.

`Independent Modality Branches` · `Transparent Late Fusion` · `Uncertainty Estimation` · `Modality Disagreement Detection` · `Missing-Modality Handling`

**Stack:** `Next.js` · `FastAPI` · `SQLAlchemy` · `Docker`

[**Repository**](https://github.com/khanaiml/multimodal-oncology-ai)

</details>

<details>
<summary><strong>03 · Energy Systems Intelligence</strong></summary>

<br>

An integrated AI platform spanning **battery degradation, energy forecasting, photovoltaic modeling, digital twins, and constrained dispatch**.

**Methods** &nbsp; `Physics-Regularized Neural Networks` · `Walk-Forward Validation` · `P10/P50/P90 Forecasting` · `HiGHS Optimization`

[**Repository**](https://github.com/khanaiml/energy-systems-intelligence)

</details>

<details>
<summary><strong>04 · ECSG Reproduction</strong></summary>

<br>

Independent reproduction of a published inorganic-crystal stability benchmark.

**85,014 compounds**

`ROC-AUC 0.8859` vs `0.8860` reported  
`F1 0.7550` vs `0.7520` reported

[**Repository**](https://github.com/khanaiml/ecsg-stability-reproduction)

</details>

<details>
<summary><strong>05 · Applied AI & SciML Benchmark Suite</strong></summary>

<br>

Cross-domain empirical research spanning superconductivity, battery SOH, cancer prognosis, steel-defect segmentation, and ML pipeline leakage analysis.

[**Kaggle Notebooks**](https://www.kaggle.com/work/code)

</details>

---

<a id="data"></a>

## Open Research Data

<!-- Replace each URL with the direct Kaggle dataset link if available -->

<details>
<summary><strong>Global Dengue Surveillance (1924–2023)</strong></summary>

<br>

**383,338 surveillance records across 102 countries and territories**  
Curated for epidemiological modeling, temporal forecasting, and spatiotemporal outbreak analysis.

[**Explore Dataset**](https://www.kaggle.com/datasets/abdullahkhan161101/global-dengue-surveillance-19242023)
</details>

<details>
<summary><strong>Pan-Cancer Gene Discriminability Benchmark</strong></summary>

<br>

**100 stability-ranked genes across 5 cancer cohorts** — BRCA, COAD, KIRC, LUAD, PRAD  
Designed for biomarker discovery, feature-selection stability, and interpretable oncology ML.

[**Explore Dataset**](https://www.kaggle.com/datasets/abdullahkhan161101/pan-cancer-gene-discriminability-benchmark)

</details>

<details>
<summary><strong>Pakistan Solar Resource & Climate Dataset</strong></summary>

<br>

**Ground-measured solar and meteorological data from 9 weather stations**  
Supports GHI/DNI/DHI irradiance forecasting and renewable-resource characterization.

[**Explore Dataset**](https://www.kaggle.com/datasets/abdullahkhan161101/pakistan-solar-resource-and-climate-dataset)

</details>

<details>
<summary><strong>MOF Property Diversity Dataset</strong></summary>

<br>

**900 curated Metal–Organic Frameworks** with electronic, pore, and geometric metadata  
Built for materials informatics, PBE band gap prediction, and small-data representation learning.

[**Explore Dataset**](https://www.kaggle.com/datasets/abdullahkhan161101/mof-property-diversity-dataset)

</details>

---

## Selected Research Findings

<details>
<summary><strong>Validation · Generalization · Reliability</strong></summary>

<br>

**Complexity vs. utility**  
TF-IDF + Linear SVM achieved **99.95%** accuracy vs **99.53%** for DistilBERT.

**Distribution shift**  
Superconductivity: **R² = 0.931** on random splits, with **+55.5% MAE** under chemical-family holdout.

**External validation**  
Multimodal oncology: **0.984 ROC-AUC** in cross-validation  **0.681** on external cohorts.

**Reproducibility**  
ECSG reproduction: **0.8859 ROC-AUC** vs **0.8860** reported.

</details>

---

<a id="experience"></a>

## Experience

<details open>
<summary><strong>AI/ML Engineer & Mentor · TABSAP</strong> · Jan 2024 – Present</summary>

<br>

Built and deployed production ML systems across **predictive lead scoring, computer vision, and LLM-powered automation**.

Conducted R&D in **interpretability, uncertainty quantification, and reliable ML architectures**.

Designed and directed a structured **6-month AI/ML internship program**, Total interns 9, 3 graduated with distinction.

</details>

<details>
<summary><strong>Lecturer in Computer Science & IT · Medicaid College of Nursing & Allied Health Sciences</strong></summary>

<br>

**May 2024 – Apr 2026**

Computer Science and IT instruction, laboratory teaching, assessment, academic guidance, and student supervision.

</details>

<details>
<summary><strong>ML Engineer / Python Developer · MSA Solutions</strong></summary>

<br>

**Oct 2023 – Dec 2023**

Python automation, ML components, data processing, experimentation, integration, and debugging.

</details>

<details>
<summary><strong>Machine Learning Intern · Eziline Software House</strong></summary>

<br>

**Aug 2023 – Oct 2023**

Data preparation, baseline modeling, hyperparameter evaluation, and ML integration.

</details>

---

<a id="education"></a>

## Education

<details open>
<summary><strong>MPhil Computer Science · Machine Learning</strong> · University of Malakand · 2024 – 2026</summary>

<br>

**CGPA:** `3.81 / 4.00`

**Thesis**

*Cancer Biomarkers Identification using Explainable Variational Autoencoders with Ensemble Feature Selection*

**Research evidence**

`20,531  12 genes` · `99.97% accuracy`

`66,660  34 genes` · `99.31% accuracy` on independent RNA-seq validation

</details>

<details>
<summary><strong>BS Computer Science</strong> · University of Malakand · 2019 – 2023</summary>

<br>

**CGPA:** `3.77 / 4.00`

*The Minute-Medical: Multi-Disease Prediction using Machine Learning and Deep Learning*

</details>

---

<a id="skills"></a>

## Technical Expertise

**Scientific ML**  
`SciML` · `Physics-Informed ML` · `PINNs` · `Materials Informatics` · `Computational Biology` · `Energy Intelligence` · `Multimodal AI`

**Reliability & Evaluation**  
`Uncertainty Quantification` · `OOD Detection` · `Calibration` · `ECE` · `SHAP` · `Distribution Shift` · `External Validation`

**Machine Learning**  
`Python` · `PyTorch` · `scikit-learn` · `XGBoost` · `TensorFlow` · `Transformers` · `NumPy` · `Pandas`

**Engineering & MLOps**  
`FastAPI` · `Streamlit` · `Next.js` · `SQLAlchemy` · `SQLite` · `Docker` · `Git` · `GitHub Actions` · `MLflow`

---

<p align="center">
  <i>Curiosity ignites research. Code forges intelligence.</i>
</p>
