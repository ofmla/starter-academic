---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Towards automatically building starting models for full-waveform inversion
  using global optimization methods: A PSO approach via DEAP+ Devito'
subtitle: ''
summary: ''
authors:
- admin
- Navjot Kukreja
tags: []
categories: []
date: '2019-01-01'
lastmod: 2020-12-23T16:00:18-03:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-12-23T19:00:11.430809Z'
publication_types:
- '6'
abstract: In this work, we illustrate an example in estimating the macromodel of velocities in the subsurface through the use of global optimization methods (GOMs). The optimization problem is solved using DEAP (Distributed Evolutionary Algorithms in Python) and Devito, Python frameworks for evolutionary and automated finite difference computations, respectively. We implement a Particle swarm optimization (PSO) with an “elitism strategy” on top of DEAP, leveraging its transparent, simple and coherent environment for implementing of evolutionary algorithms (EAs). The high computational effort, due to the huge number of cost function evaluations (each one demanding a foward modeling step) required by PSO, is alleviated through the use of Devito. The combined use of both frameworks yields not only an efficient way of providing acoustic macro models of the P-wave velocity field (Vp), but also significantly reduces the amount of geophysicist effort in fulfilling this task.
publication: '*SEG Technical Program Expanded Abstracts 2019*'
doi: https://doi.org/10.1190/segam2019-3216316.1
---
