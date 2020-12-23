---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Lanczos Bidiagonalization Method for Parallel 3-D Gravity Inversion-Application
  to Basement Relief Definition
subtitle: ''
summary: ''
authors:
- admin
- Amin Bassrei
tags: []
categories: []
date: '2015-01-01'
lastmod: 2020-12-23T16:00:19-03:00
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
publishDate: '2020-12-23T19:00:19.192425Z'
publication_types:
- '6'
abstract: It is present an efficient parallel algorithm for the inversion of 3-D gravity data, which goal is to estimate the depth of a sedimentary basin in which the density contrast varies parabolically with depth. The efficiency of the gravity inversion methods applied to the interpretation of sedimentary basins depends on the number of data and model parameters to be estimated, making it very poor when the number of parameters is very large. We present the simulation results with a synthetic model of a sedimentary basin inspired in a real situation, taking advantage of a parallel Levenberg-Marquardt algorithm implemented using both MPI and OpenMP. Lanczos bidiagonalization method has been used to obtain the solution for the linearized subproblem at each iteration. The idea of obtaining the solution of a large system of equations using the bidiagonalization procedure is quite useful in practical problems, and allows to implement selection methods for the optimal regularization parameter in an easy way, like the weighted generalized cross validation method, adopted in this work. The hybrid parallel implementation combined with Lanczos bidiagonalization allows us to achieve a significant reduction of the computational cost, which is otherwise very high due to the scale of the problem.
publication: '*SEG Technical Program Expanded Abstracts 2015*'
doi: https://doi.org/10.1190/segam2015-5903779.1
---
