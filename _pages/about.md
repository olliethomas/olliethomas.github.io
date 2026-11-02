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

I design and build production machine learning systems end to end: from whiteboarding
the problem, through training models and writing the services that run them, to
automating the monitoring that keeps them improving. Recently that has meant forecasting for consumer
sports products: constrained optimisation over predicted outcomes, fed by noisy
third-party data against fixed deadlines, where prediction quality *is* the product.

The part I find most interesting is the part that isn't modelling: the systems and
processes that let a team ship models with confidence. Before a model ships, that means
time-based evaluation splits and domain validation metrics, checked through backtesting.
Once it's live, it means catching it degrading quietly rather than failing loudly:
accuracy slipping, or predictions collapsing onto a single value. That tends to matter
more than the architecture, and gets written about less.

## Research

My PhD, at the University of Sussex under [Prof. Novi
Quadrianto](https://scholar.google.com/citations?user=n9nXAPcAAAAJ), was on **fair
representations that system designers and stakeholders can inspect**, rather than an
uninterpretable latent space, so the changes made for fairness can be interpreted and
explained to the people who have to act on them. You can [read the thesis here](https://olliethomas.github.io/thesis/).

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
