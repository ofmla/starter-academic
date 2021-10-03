---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Solving one-step wave extrapolation matrix method using Krylov methods for
  matrix functions
subtitle: ''
summary: ''
authors:
- Oscar F. Mojica
- Reynam Pestana
tags: []
categories: []
date: '2021-01-01'
lastmod: 2021-10-03T12:18:29-03:00
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
publishDate: '2021-10-03T15:18:29.027211Z'
publication_types:
- '6'
abstract: ' We investigate the use of a restarted Krylov subspace method for computing
  the action of a function of large sparse matrix on a vector to numerically solve
  the one-step wave extrapolation matrix We investigate the use of a restarted Krylov
  subspace method for computing the action of a function of large sparse matrix on
  a vector to numerically solve the one-step wave extrapolation matrix (OSEM) method.
  The OSEM method belongs to a category exempt from stability and dispersion problems
  when extrapolating acoustic wavefields in time. It is based on the solution of a
  first-order differential equation in the time domain for the analytical wavefield.
  Such wavefield is separated into real and imaginary parts, and the resulting first-order
  matrix differential equation is integrated in time using Chebyshev polynomial expansion,
  usually combined with the Fourier method to compute a square-root pseudodifferential
  operator. To by- pass fast fourier transforms (FFT), the aim of the present work
  is to introduce an approach that uses the theory of matrix functions, and therefore
  enables the use of fast Krylov-based methods for their computation. Numerical modeling
  examples are shown to demonstrate the efficacy of the new formulation. '
publication: '*First International Meeting for Applied Geoscience &amp; Energy Expanded
  Abstracts*'
url_pdf: https://library.seg.org/doi/abs/10.1190/segam2021-3595008.1
doi: 10.1190/segam2021-3595008.1
---
