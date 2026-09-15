# Serafim Tkachenko

**Software Engineering Lead · ML Research Tooling & Evaluation · Model Behavior & Interpretability**

I lead an engineering team at BNP Paribas CIB and have 10+ years of experience building production systems and applied R&D software. Alongside that work, I study LLM behavior through activation analysis, controlled interventions and empirical evaluation.

I am seeking **Research Engineer** roles combining hands-on software engineering, experimental tooling and model evaluation.

My research interests are model representations, interpretability and empirical alignment. The central question is when internal model signals help predict behavior or intervention effects beyond simpler explanations.

## Selected work

### [Model Behavior Research](https://github.com/serafim-tkachenko/model-behavior-research)

Does the context associated with an SAE feature help explain the effects of intervening on it?

I selected the research question and methodology and designed the [SAE Feature Atlas toolkit](https://github.com/serafim-tkachenko/sae-feature-atlas). The study uses pretrained Gemma 3 4B and Gemma Scope SAEs across 12,000 documents and two layers, followed by a development intervention pilot with 96 feature-prompt cases in 95 duplicate groups.

This is an exploratory study with a negative development result: selected features show contextual associations, but the intervention analyses did not establish additional predictive value beyond principal-component controls or selective effects beyond scalar gain. The result supports narrowing the next experiment around a meaningful behavioral endpoint and strong simple baselines. Proposed experiments are separate from completed evidence.

[Research brief](https://github.com/serafim-tkachenko/model-behavior-research/blob/main/RESEARCH.md) · [Report](https://github.com/serafim-tkachenko/model-behavior-research/blob/main/reports/research_report/report.pdf)

### [SAE Feature Atlas — toolkit](https://github.com/serafim-tkachenko/sae-feature-atlas)

A reusable Python API and CLI for collecting and inspecting SAE activations. It provides explicit token populations, feature statistics, coactivation and decoder-geometry analysis, plus configuration fingerprints and artifact lineage. Model collection uses PyTorch; saved-artifact analysis can run on CPU.

The toolkit supports the research above; study-specific experiments and conclusions live in Model Behavior Research.

### [EGNN with topology features on QM9](https://github.com/serafim-tkachenko/qm9-egnn-tda)

I built a molecular-property prediction pipeline around `egnn-pytorch`, adding persistent-homology features through FiLM conditioning.

The initial audit found saturated conditioning. A subsequent four-condition experiment trained twelve models across three seeds with the same ten-epoch budget. Standardized topology features performed worse than all controls on clean and matched-noise tests in every seed. The project is paused pending a stronger clean baseline; this is a result about the tested pipeline, not a general failure of topology methods.

[Research synthesis and results](https://github.com/serafim-tkachenko/qm9-egnn-tda/blob/master/reports/research_synthesis_2026-09-13.md)

These projects use substantial LLM and coding-agent assistance for implementation, execution and reporting. My research-direction and toolkit-design contributions are recorded in the [contribution statement](https://github.com/serafim-tkachenko/model-behavior-research/blob/main/CONTRIBUTIONS.md).

## Background

- Engineering leadership and hands-on development in trading analytics, pre-trade risk, data pipelines and distributed systems.
- Two semesters of MIPT Deep Learning School, both completed with honors and maximum available points; second-semester final project: 20/20.
- MSc in Software Engineering, with honors. Earlier industrial computer-vision work led to a co-authored conference paper in 2018.

Research tools: Python, PyTorch, NumPy, pandas, scikit-learn, Transformers and SAE-Lens. Engineering: Java, C++, C#, KDB+, SQL and distributed systems.

[LinkedIn](https://www.linkedin.com/in/serafim-tkachenko/) · [Email](mailto:serafim.tkachenko@gmail.com) · Lisbon, Portugal
