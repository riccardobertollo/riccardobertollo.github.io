---
title: "Stability analysis of bipedal walking using a hybrid linear inverted pendulum model"
collection: supervision
student: "Gianni Lunardi"
type: "MSc thesis"
permalink: /supervision/giannilunardi
venue: "University of Trento (Italy)"
date: 2021-09-18
location: "Trento, Italy"
---

## Summary
Hybrid dynamical systems, which integrate both continuous-time and discrete-time dynamics, have gained significant attention over the past decade due to their applicability in modeling systems with abrupt state changes, such as mechanical systems subject to impacts. A canonical example is the bouncing ball, where continuous motion is interrupted by discrete velocity reversals upon impact. This hybrid framework is particularly valuable for analyzing and controlling systems with impact phenomena, as demonstrated in linear control strategies for point-mass tracking and estimation. \
This work focuses on applying hybrid system theory to bipedal locomotion, specifically using the Linear Inverted Pendulum Model (LIPM) to describe the dynamics of walking robots. Traditional approaches simplify the control problem by predefining contact timings, effectively reducing the hybrid system to a time-varying discrete system. While this facilitates control via methods like Model Predictive Control, it limits adaptability and robustness to timing uncertainties. \
In contrast, the proposed approach models foot-ground impacts as state-triggered events, allowing for dynamic contact timing based on the Center of Mass position. A feedback control law, incorporating both system states and a logic variable, enables tracking of a symmetric periodic reference motion. This formulation enhances the analysis of closed-loop stability under timing deviations. The manuscript further introduces a novel hybrid LIPM formulation that decomposes dynamics into convergent and divergent components, supported by simulation results validating the theoretical framework. The study concludes with a discussion on implications and future research directions.