---
title: "Development and analysis of epidemiological compartmental models for pandemic parameter estimation and forecasting"
collection: supervision
student: "Marco Dell'Oro"
type: "MSc thesis"
permalink: /supervision/marcodelloro
venue: "Politecnico di Milano (Italy)"
date: 2024-04-09
location: "Milano, Italy"
---

## Summary

On March 11, 2020, The World Health Organization (WHO) officially declared the SARS-CoV-2 outbreak a global pandemic. The unparalleled spread quickly reached more than 200 countries all over the world. Infected individuals show a large spectrum of symptoms, from mild flu-like illness to pneumonia and acute respiratory distress syndrome, causing deaths and crippling the health systems of most countries.
As an answer to contrast the pandemic, the scientific community has developed mathematical models of various nature, which have provided a framework to combine epidemiological knowledge, novel assumptions, and data collection, recreating a simplified yet valid representation of reality.\
The majority of these models, fall in the class of compartmental models. Compartmental models describe the movement of a certain variable of interest from one compartment to another. In epidemiology, the population is divided into compartments, labelled on the basis of infection status. Compartment dynamics is generally described by ordinary differential equations (usually deterministic), depending on parameters, which are assumed known and constant.\
Data-driven estimation of (slowly) time-varying parameters can provide a more reliable forecast, but it requires control-related properties such as \textit{observability} and \textit{identifiability}.
In this work we retrospectively evaluate various complex compartmental models, showing that identifiability is rarely considered and met in epidemiological modelling.
Furthermore, we propose and analyse a simpler model, showing how this solution can still provide a realistic and interpretable overview of the pandemic scenario while preserving observability and identifiability.\
Lastly, we propose a novel combination of Moving Horizon Estimation and Time-Series Analysis, in order to provide a forecasting tool for policymakers to predict how the pandemic will unfold, given the current situation.