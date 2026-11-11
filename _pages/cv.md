---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download my CV as a PDF]({{ base_path }}/files/Oliver-Thomas-CV.pdf)

Education
======
* **Ph.D. in Machine Learning**, University of Sussex, 2017 – 2022
  * Thesis: [*Fair Representations in the Data Domain*](https://hdl.handle.net/10779/uos.23491859)
  * Supervisor: Prof. Novi Quadrianto
  * First year part-time, alongside a graduate role at American Express
  * Built adversarial and normalising-flow models that learn fair representations which
    system designers and stakeholders can inspect
* **B.Sc. (Hons) Computer Science**, First Class, University of Sussex, 2013 – 2017
  * Dissertation: *Learning Using Privileged Information: A Unified Approach*
  * Faculty prizes for Outstanding Computer Science Student and Best AI Final Year Project

Work experience
======
* **Oct 2026 – present: Senior Engineer (AI & Optimisation)**
  * Metasonixx Ltd
  * Using AI and advanced optimisation techniques to produce novel acoustic metamaterial
    designs.
  * Turning the team's research into a reusable, reproducible and tested system built in
    Python.

* **Aug 2024 – Sep 2026: Senior Engineer (AI & ML)**
  * Scoreline AI
  * Owned the technical direction of the AI function for Fantasy Football Hub and
    Wickets.ai, Scoreline's fantasy football and fantasy cricket products: the reference
    architecture for a multi-sport prediction platform, the predictions platform's
    backend testing standard, and models across team strength, expected minutes and
    points prediction.
  * Led the rebuild of Fantasy Football Hub's prediction system, using proven, modern
    architecture (normalised data, event-driven services, serverless infrastructure) to
    make it faster, cheaper to run and safer to change.
  * Built neural networks in PyTorch, from simple baselines to temporal attention over a
    player's recent matches.
  * Defined what a model has to satisfy to reach production: time-based evaluation
    splits and domain validation metrics, checked through backtesting.
  * Proved the architecture on Wickets.ai before it was adopted into the main platform.

* **Jan – Sep 2022, Sep 2023 – Aug 2024: Postdoctoral Research Fellow**
  * Predictive Analytics Lab, University of Sussex
  * The second appointment held through the Basque Center for Applied Mathematics (BCAM), Bilbao.
  * Developing other researchers and maintaining the lab's shared engineering practice,
    alongside contributing to projects as a technical generalist.
  * Lead author of the lab's open-source experiment framework.

* **Sep 2022 – Sep 2023: Career break**
  * Travel across Central and South America after submitting my PhD.

* **Feb 2020 – Jan 2021: Consultancy Project Lead**
  * Predictive Analytics Lab, University of Sussex
  * Led five researchers to deliver a documented Python library for a charity client,
    learning causal structure (Bayesian networks, via MCMC) from questionnaire data and
    estimating intervention effects.

* **Sep 2017 – Sep 2018: Technology Graduate**
  * American Express
  * Teams worked: 
    - Data Architecture: data access APIs and database migrations for a move to microservices
    - Enterprise Cloud Platform: advising development teams adopting cloud systems

* **Summer 2016: Technology Intern**
  * American Express
  * Duties included: Database Migration
  
Skills
======
* Python, PyTorch, Lightning, Weights & Biases, scikit-learn, XGBoost, Pandas/NumPy
* Model evaluation, backtesting and monitoring; experiment tooling (Optuna, Hydra)
* Systems architecture, Postgres, Pulumi, Cloud Run, Pub/Sub
* Constrained optimisation (MILP)
  
Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
