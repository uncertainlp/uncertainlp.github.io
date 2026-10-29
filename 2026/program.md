---
layout: 2026
permalink: /2026/program
---

The workshop will take place on **Thursday, October 29, 2026**, in Budapest, Hungary. All times below are in **Budapest local time (CET, UTC+1)**.

See the complete list of [accepted papers](/2026/accepted-papers).

### Workshop Schedule

Each keynote has a 40-minute slot: approximately 30 minutes for the talk and 10 minutes for questions.

| Time | Session |
|---|---|
| 09:00–09:10 | Opening Remarks ([slides](https://drive.google.com/file/d/1U4AlzcMSg9aPigWUA0wIC8Kagj4TlWI6/view?usp=sharing)) |
| 09:10–09:50 | Keynote Talk 1: [**André Martins**](#keynote-martins) |
| 09:50–10:30 | Keynote Talk 2: **Dan Roth** |
| 10:30–10:55 | Coffee Break |
| 10:55–11:25 | Poster lightning round 1 |
| 11:25–12:30 | In-Person Poster Session 1 |
| 12:30–13:40 | Lunch Break |
| 13:40–13:55 | SHROOM |
| 13:55–14:25 | Poster lightning round 2 |
| 14:25–15:30 | In-Person Poster Session 2 |
| 15:30–16:00 | Coffee Break |
| 16:00–16:40 | Keynote Talk 3: [**Yingzhen Li**](#keynote-li) |
| 16:40–17:20 | Keynote Talk 4: [**Gintare Karolina Dziugaite**](#keynote-dziugaite) |
| 17:20–17:30 | Closing Remarks |
| 17:30 | End |

### Keynote: André Martins {#keynote-martins}

**Sparsity Meets Uncertainty: Applications to Conformal Prediction and Generalized Variational Bayes**

**Time:** 09:10–09:50 Budapest local time (CET, UTC+1).

**Abstract:** In the first part of the talk, I will present a framework for conformal prediction based on temperature scaling of sparse activations. Conformal prediction is a distribution-free framework for uncertainty quantification that replaces point predictions with sets, offering marginal coverage guarantees. We uncover a novel connection between conformal prediction and sparse softmax-like transformations, such as sparsemax and γ-entmax (with γ > 1), which may assign nonzero probability only to a subset of labels. We introduce new non-conformity scores for classification that make the calibration process correspond to the widely used temperature scaling method. At test time, applying these sparse transformations with the calibrated temperature leads to a support set (i.e., the set of labels with nonzero probability) that automatically inherits the coverage guarantees of conformal prediction.

In the second part, I will present a generalized variational Bayes method based on Fenchel-Young (FY) regularization. Our proposed formulation – FY variational learning – includes as key ingredients new notions of FY free energy, FY evidence, FY evidence lower bound, and FY posterior. We derive alternating minimization and gradient backpropagation algorithms to compute (or lower bound) the FY evidence, which enables learning a wider class of models than previous variational formulations. For a suitable choice of Fenchel-Young regularizer we can obtain sparse and varying support posteriors.

Joint work with Margarida Campos, Sophia Sklaviadis, Mário A.T. Figueiredo, Thomas Moellenhoff, Emtiyaz Khan

### Keynote: Yingzhen Li {#keynote-li}

**Quantifying uncertainty in-context via probing questions**

**Time:** 16:00–16:40 Budapest local time (CET, UTC+1).

**Abstract:** As large language models (LLMs) gain popularity in conducting prediction tasks in-context, understanding and estimating uncertainty in in-context learning becomes essential to ensuring reliability of prediction and decision-making. The recent hypothesis of in-context learning performing predictive Bayesian inference opens the avenue for Bayesian uncertainty estimation and decision making algorithms. This talk will discuss our recent efforts in decomposing uncertainty and decision making under uncertainty in-context. We first introduce a variational uncertainty decomposition framework for in-context learning without explicitly sampling from the latent parameter posterior, by optimising auxiliary question as probes to obtain an upper bound to the aleatoric uncertainty of an LLM’s in-context learning procedure. We then show the classical Thompson Sampling algorithm can be adapted in this auxiliary question probing framework, where different aggregation strategies for the probes result in different exploration-exploitation trade-off behaviours.

### Keynote: Gintare Karolina Dziugaite {#keynote-dziugaite}

**Remembering and Forgetting: The Antithetical Roles of Linear Mode Connectivity**

**Time:** 16:40–17:20 Budapest local time (CET, UTC+1).

**Abstract:** Continual learning, model merging, and information unlearning address critical challenges in managing foundation models. In this talk I will present evidence that linear mode connectivity (LMC)—the lack of loss barriers on the linear path connecting two models—is a decisive factor in the success and failure of methods in these three areas. We demonstrate how LMC enables efficient, training-free model merging and continual learning through weight interpolation. Conversely, in unlearning, we show that model editing fails when the edited model is linearly connected to the original model. Attempts to “unlearn” information are often superficial, as the original knowledge remains easily recoverable along the same low-loss path, compromising the model’s robustness and leaving it susceptible to relearning attacks. This work highlights a core trade-off in modern AI: the very properties that make models continually learn also make them difficult to truly and safely edit.
