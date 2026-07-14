# Representative AI Prompt Documentation

## Purpose

This document records representative AI interactions that materially contributed to the development of this project.

Only prompts that significantly influenced the project are documented. Minor syntax corrections and routine debugging requests are intentionally omitted.

---

# NotebookLM Interactions

---

## Prompt ID: N001

### Objective

Understand mentor-provided project documentation.

### AI Tool

NotebookLM

### AI Contribution

- Summarized uploaded documents.
- Explained project terminology.
- Organized research material.
- Highlighted important methodological concepts.

### Human Contribution

The summaries served as study material only.

Final implementation decisions remained independent.

---

## Prompt ID: N002

### Objective

Review research papers on causal inference.

### AI Tool

NotebookLM

### AI Contribution

- Summarized literature.
- Highlighted important findings.
- Connected ideas across multiple papers.
- Identified methodological recommendations.

### Human Contribution

Only scientifically appropriate recommendations were adopted after manual evaluation.

---

# ChatGPT Interactions

---

## Prompt ID: C001

### Objective

Design a synthetic benchmark dataset.

### AI Contribution

Suggested a stochastic SEIR simulation framework with configurable epidemiological parameters.

Suggested variables including:

- transmission rate,
- vaccination rate,
- mobility,
- hospital capacity,
- population density,
- government intervention.

### Human Contribution

The simulation equations, intervention mechanism, treatment assignment, parameter ranges, and causal assumptions were independently implemented and modified.

---

## Prompt ID: C002

### Objective

Develop the causal inference pipeline.

### AI Contribution

Recommended evaluation using:

- Propensity Score Matching,
- Inverse Probability Weighting,
- Augmented IPW,
- Double Machine Learning,
- Causal Forest.

### Human Contribution

Estimator selection, implementation, hyperparameter tuning, interpretation, and validation were performed manually.

---

## Prompt ID: C003

### Objective

Construct the real-world observational dataset.

### AI Contribution

Suggested integrating:

- Our World in Data (OWID),
- Oxford COVID-19 Government Response Tracker (OxCGRT).

Suggested mapping synthetic variables to real-world proxies.

### Human Contribution

Dataset selection, preprocessing, quality assessment, country filtering, weekly aggregation, and treatment construction were independently performed.

---

## Prompt ID: C004

### Objective

Prepare project documentation.

### AI Contribution

Generated draft explanations for:

- methodology,
- dataset construction,
- variable definitions,
- GitHub documentation,
- LaTeX reports.

### Human Contribution

All scientific content was reviewed, edited, and expanded before inclusion.

---

## Prompt ID: C005

### Objective

Organize the GitHub repository.

### AI Contribution

Suggested repository hierarchy, reproducibility practices, documentation structure, and portfolio organization.

### Human Contribution

Repository design, version control, and future development remain under manual control.

---

# Validation Policy

Every AI-generated output was treated as an initial draft or implementation aid.

Before incorporation into this project:

- statistical assumptions were manually verified,
- causal reasoning was independently reviewed,
- generated code was executed and tested,
- documentation was revised,
- final scientific conclusions were prepared independently.

AI assisted the development process but did not replace scientific judgment or independent analysis.