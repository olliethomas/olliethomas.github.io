---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Machine Learning**, University of Sussex, 2017 – 2022
  * Thesis: [*Fair Representations in the Data Domain*](https://hdl.handle.net/10779/uos.23491859)
  * Supervisor: Prof. Novi Quadrianto
  * First year part-time, alongside a graduate role at American Express
* **B.Sc. (Hons) Computer Science**, First Class, University of Sussex, 2013 – 2017
  * Faculty prizes for Outstanding Computer Science Student and Best AI Final Year Project

Work experience
======
* **Aug 2024 – present: Senior Engineer (AI & ML)**
  * Scoreline (Fantasy Football Hub)
  * Own the technical direction of the AI function: the reference architecture for a
    multi-sport prediction platform, the predictions platform's backend testing
    standard, and model architecture across team strength, expected minutes and points
    prediction.
  * Defined what a model has to satisfy to reach production: time-based evaluation
    splits and domain validation metrics, enforced through backtesting.
  * Proved the architecture on Wickets, a cricket product, before it was adopted into
    the main platform.

* **Jan – Sep 2022, Sep 2023 – Aug 2024: Postdoctoral Research Fellow**
  * Predictive Analytics Lab, University of Sussex
  * The second appointment held through the Basque Center for Applied Mathematics (BCAM), Bilbao.
  * Developing other researchers and maintaining the lab's shared engineering practice,
    alongside contributing to projects as a technical generalist.
  * Authored and maintained EthicML, the lab's fair-ML benchmarking framework.

* **Sep 2022 – Sep 2023: Career break**
  * Travel across Central and South America following completion of the PhD.

* **Feb 2020 – Jan 2021: Consultancy Project Lead**
  * Predictive Analytics Lab, University of Sussex
  * Managed a team of five delivering a standalone application for a charity client,
    built on research into Bayesian Network Structure Learning.

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
* Python, PyTorch, scikit-learn, XGBoost, Pandas/NumPy
* Model evaluation and backtesting; experiment tooling (Optuna, Hydra)
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
