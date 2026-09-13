# Serafim Tkachenko

**Software Engineering Lead · Independent LLM Interpretability Research**

I lead an engineering team at BNP Paribas CIB and have 10+ years of experience building production systems and applied R&D software. Alongside that work, I study LLM behavior through activation analysis, controlled interventions and empirical evaluation.

My research interests are interpretability and empirical AI alignment: understanding what a model is doing, testing competing explanations, and finding when internal signals add value beyond simpler methods.

## Selected work

### [SAE Feature Atlas](https://github.com/serafim-tkachenko/sae-feature-atlas)

Does the context associated with an SAE feature help explain the effects of intervening on it?

I built and ran a Gemma 3 4B study using pretrained Gemma Scope SAEs across 12,000 documents and two layers, followed by a 96-case development intervention pilot. The work includes activation collection, held-out statistical comparisons and matched intervention controls. It supports contextual associations in selected features; transferable prediction and selective mechanisms remain unresolved.

[Read the research report](https://github.com/serafim-tkachenko/sae-feature-atlas/blob/main/reports/research_report/report.pdf)

### [EGNN with topology features on QM9](https://github.com/serafim-tkachenko/qm9-egnn-tda)

I built molecular-property training and evaluation pipelines around `egnn-pytorch`, adding persistent-homology features through FiLM conditioning.

A subsequent paired evaluation and descriptor-replacement checks exposed a limitation: the tested FiLM branch was saturated and predictions barely depended on individual topology descriptors. The observed checkpoint advantage therefore does not establish a benefit from molecule-specific topology.

[Read the validation report](https://github.com/serafim-tkachenko/qm9-egnn-tda/blob/research/paired-validation/reports/paired_pilot_2026-09-13.md)

## Background

- Engineering leadership and hands-on development in trading analytics, pre-trade risk, data pipelines and distributed systems.
- Two semesters of MIPT Deep Learning School, both completed with honors and maximum available points; second-semester final project: 20/20.
- MSc in Software Engineering, with honors. Earlier industrial computer-vision work led to a co-authored conference paper in 2018.

Research tools: Python, PyTorch, NumPy, pandas, scikit-learn, Transformers and SAE-Lens. Engineering: Java, C++, C#, KDB+, SQL and distributed systems.

[LinkedIn](https://www.linkedin.com/in/serafim-tkachenko/) · [Email](mailto:serafim.tkachenko@gmail.com) · Lisbon, Portugal
