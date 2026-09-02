# NetLogo agent-based model

This folder contains the final agent-based simulation model developed in NetLogo for the study:

**Agent-Based Simulation and Data Mining for Mapping Structural Inequities in Breast Cancer Care Pathways in Colombia: A Computational Proof-of-Concept Study**

## Purpose

The model generates synthetic patient populations and simulates simplified breast cancer care pathways using data-informed distributions and selected empirical dependencies derived from publicly available Colombian datasets.

## Main simulated stages

Each synthetic patient progresses through:

1. Admission
2. Diagnosis
3. Treatment
4. Final evaluation

One NetLogo tick represents one simulated day.

## Main agent attributes

The model includes variables related to:

- age;
- insurance scheme;
- history-related characteristics;
- offspring;
- breastfeeding status;
- left-breast mass;
- right-breast mass;
- diagnostic duration;
- treatment duration.

## Important modelling assumptions

The model is intended for exploratory and hypothesis-generating purposes.

Selected empirical associations were incorporated as population-level parameterisation targets through a calibrated latent dependency structure.

Internal calibration parameters should not be interpreted as:

- causal coefficients;
- clinical effect sizes;
- epidemiological risk estimates;
- patient-level predictors.

The cumulative care-burden indicator and residual-energy representation are synthetic computational constructs and have not been clinically validated.

## Simulation scenarios

The final experiment included three synthetic population sizes:

- 1,000 agents
- 5,000 agents
- 10,000 agents

Three independent runs were performed for each population size, resulting in nine simulation runs.

## Model file

The final NetLogo model used in the manuscript will be stored in this folder.

## Software

NetLogo version information will be included in the final reproducibility release.

## Licence

Code developed for this repository is distributed under the MIT License unless otherwise stated.
