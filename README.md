# Causal Effect of Government Intervention Policies on COVID-19 Transmission

## Overview

This project investigates the causal effect of government intervention policies on COVID-19 transmission using modern causal inference techniques.

Unlike traditional machine learning models that focus on prediction, this project estimates **what would have happened under different intervention policies** by controlling for observed confounding variables.

The study follows a two-stage validation framework:

- Synthetic Benchmark Dataset (known treatment effects)
- Real-World Observational Dataset (public COVID-19 data)

The objective is to demonstrate that the same causal inference pipeline remains applicable when transitioning from controlled simulations to real-world observational data.

---

## Research Question

> **What is the causal effect of stringent government intervention policies on COVID-19 transmission after adjusting for demographic, healthcare, vaccination, and socioeconomic confounders?**

---

## Project Objectives

- Generate a synthetic epidemiological benchmark dataset.
- Validate multiple causal inference methods using known treatment effects.
- Construct a real-world observational panel dataset.
- Estimate causal effects using multiple complementary methods.
- Compare synthetic validation with real-world application.
- Develop an interactive Streamlit dashboard for visualization.

## Project Workflow

```text
Synthetic SEIR Simulation
          │
          ▼
 Benchmark Causal Analysis
 (True Treatment Effects Known)
          │
          ▼
Real-World Data Collection
 (OWID + OxCGRT)
          │
          ▼
Data Cleaning & Weekly Panel Construction
          │
          ▼
Propensity Score Estimation
          │
          ▼
PSM
          │
          ▼
IPW
          │
          ▼
AIPW
          │
          ▼
DoWhy
          │
          ▼
EconML
          │
          ▼
Heterogeneous Treatment Effects
          │
          ▼
Interpretation & Validation
```