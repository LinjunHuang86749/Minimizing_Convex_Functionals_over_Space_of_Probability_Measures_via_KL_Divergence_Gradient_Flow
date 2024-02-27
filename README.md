# Minimizing_Convex_Functionals_over_Space_of_Probability_Measures_via_KL_Divergence_Gradient_Flow

This repository contains code of the experiments of AISTATS 2024 paper [Minimizing Convex Functionals over Space of Probability Measures via KL Divergence Gradient Flow](https://arxiv.org/abs/2311.00894), [Rentian Yao](https://sites.google.com/view/rentianyao), [Linjun Huang](https://linjun-site.netlify.app/), and [Yun Yang](https://sites.google.com/site/yunyangstat/). We introduce an implicit scheme, called the implicit KL proximal descent (IKLPD) algorithm, for discretizing a continuous-time gradient flow relative to the Kullback–Leibler (KL) divergence for minimizing a convex target functional. We perform experiments to validate the effectiveness of our approach works in different scenarios.

## Description

* repository `Gaussian_location`
* repository `Gaussian_location_scale`
* repository `Bayesian_sampling`
* repository `Comparisons_with_WGF`
* repository `impact_of_tau_figure_5`
* repository `impact_of_tau_figure_6`
* repository `impact_of_tau_figure_7`
* repository `NF_short_flows`


## Dependencies

* We use the [`normflows` package](https://github.com/VincentStimper/normalizing-flows/tree/master) to implement the IKLPD algorithm.
