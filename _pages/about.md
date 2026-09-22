---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a machine learning engineer in Brighton, UK.

I build and own production prediction platforms end to end: model architecture through
to the infrastructure that serves them, and the evaluation that decides whether a model
is allowed near production at all. Recently that has meant forecasting for consumer
sports products: constrained optimisation over predicted outcomes, fed by noisy
third-party data against fixed deadlines, where prediction quality *is* the product.

The part I find most interesting is the part that isn't modelling. Deciding what a model
has to satisfy before it ships: time-based evaluation splits and domain validation
metrics, enforced through backtesting. And once it's live, watching for it degrading
quietly rather than failing loudly: mode collapse, shifts in the input data
distribution. That tends to matter more than the architecture, and gets written about
less.

## Research

My PhD, at the University of Sussex under [Prof. Novi
Quadrianto](https://scholar.google.com/citations?user=n9nXAPcAAAAJ), was on **fair
representation learning that stays in the data domain** rather than an uninterpretable
latent space, so per-sample information can be inspected and explained to the people who
have to act on it. You can [read the thesis here](https://olliethomas.github.io/thesis/).

That thread (making machine learning legible and operable by people who aren't the
person who built it) runs through most of what I do, research or otherwise.

- *Discovering Fair Representations in the Data Domain*, **CVPR 2019**
- *Null-Sampling for Interpretable and Fair Representations*, **ECCV 2020**
- *An Algorithmic Framework for Positive Action*, **ACM EAAMO 2021**

## Open source

I wrote and maintain [**EthicML**](https://github.com/wearepal/EthicML), an open-source
benchmarking framework for fair machine learning: common loaders for the standard
fairness datasets, a built-in train/validation/test protocol, pluggable models and
metrics, and automatic utility–fairness trade-off plots. It started because the lab was
sharing code by emailing snippets, and it ended up being used in teaching and behind the
experiments in published papers.

## Elsewhere

📫 Reach me at [oliverthomas@outlook.com](mailto:oliverthomas@outlook.com).

😄 Pronouns: he/him.

⚡ Fun fact: the dress was gold and white. There was no blue and black dress.
