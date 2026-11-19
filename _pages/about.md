---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a senior software engineer and tech lead at NotCo AI. I lead the technical direction of Elevate, part of the company's suite of AI tools for food development, which helps food developers find better formulations faster with Bayesian optimization. I own its architecture end to end, from a Vue frontend and a Python backend to optimization workers on Kubernetes, and I lead the engineers who build it.

I work with AI agents every day, and I spend my own time where they can't help: deciding what to build and what to cut, setting the bar for proof, and keeping systems simple enough to own. Before industry, I did research in deep learning on vision-language navigation; my publications are below.

## What I work on

- **Elevate.** I've been its tech lead since 2024. Recently I designed and shipped a feasibility check that tells food developers, before they run an experiment, whether their constraints allow any valid formula and why an ingredient can never be used.
- **Enterprise environments.** I built the first dedicated customer environment and its shared foundations (per-tenant authentication, a data-access proxy and external-group permissions), which became the template for later ones, and I validated the optimization engine on Azure.
- **Foundations across products.** I lead the company's design system, which went from a product need to a released package in 10 days, and I co-led the design of a formula-tracker product, from the build-vs-reuse analysis to its permissions and data model.
- **Agentic engineering.** I work with an implement-and-review loop: one agent implements, a read-only agent reviews, and people decide the scope, the simplicity bar and the proof required.
- **People.** I mentor engineers as they grow into new areas, and I run the engineering office hours.

## Talks

I've given talks at NotCo's engineering office hours and internal sessions on:

- Workload Identity Federation versus service-account keys
- Docker layers: caching, multi-stage builds and image inspection
- CPU counting in containers
- Kubernetes resource starvation
- asyncio and the event loop

## Background

- Master of Science in Engineering (Magíster en Ciencias de la Ingeniería) with a research focus on deep learning, and a six-year Computer Science engineering degree (Ingeniería Civil), both from Pontificia Universidad Católica de Chile.
- Course assistant for six university courses and private tutor before I moved to industry.
- Outside work, I enjoy board games (I organize board-game nights at work) and music.

See my [CV](/cv/) for the full details.

## Publications

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
