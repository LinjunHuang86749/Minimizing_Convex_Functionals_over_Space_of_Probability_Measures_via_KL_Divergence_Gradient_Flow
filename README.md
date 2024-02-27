# Minimizing_Convex_Functionals_over_Space_of_Probability_Measures_via_KL_Divergence_Gradient_Flow

This repository contains **code** of the experiments of AISTATS 2024 paper [Minimizing Convex Functionals over Space of Probability Measures via KL Divergence Gradient Flow](https://arxiv.org/abs/2311.00894), [Rentian Yao](https://sites.google.com/view/rentianyao), [Linjun Huang](https://linjun-site.netlify.app/), and [Yun Yang](https://sites.google.com/site/yunyangstat/). We introduce an implicit scheme, called the implicit KL proximal descent (IKLPD) algorithm, for discretizing a continuous-time gradient flow relative to the Kullback–Leibler (KL) divergence for minimizing a convex target functional. We perform experiments to validate the effectiveness of our approach works in different scenarios.

## Description

* Repository `Gaussian_location` contains code used in the experiments for the **Gaussian location mixture model**.
* Repository `Gaussian_location_scale` contains code used in the experiments for the **Gaussian location scale mixture model**.
* Repository `Bayesian_sampling` contains code used in the experiments for the **Bayesian sampling**.
* Repository `Comparisons_with_WGF` contains code used in the experiments for the [**Comparison with Wassersten gradient flows**](https://github.com/PetrMokrov/Large-Scale-Wasserstein-Gradient-Flows).
* Repository `impact_of_tau_figure_5` contains code used in the experiments for **figure 5** of the **Impact of IKLPD Step Size** in Appendix C.4.
* Repository `impact_of_tau_figure_6` contains code used in the experiments for **figure 6** of the **Impact of IKLPD Step Size** in Appendix C.4.
* Repository `impact_of_tau_figure_7` contains code used in the experiments for **figure 7** of the **Impact of IKLPD Step Size** in Appendix C.4.
* Repository `NF_short_flows` contains code used in the experiments for the **Composition of Short Flows and Teacher-Student Architecture** in Appendix C.5.


## Dependencies

* We use the [`normflows` package](https://github.com/VincentStimper/normalizing-flows/tree/master) to implement the IKLPD algorithm.
