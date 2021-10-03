---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Using of Fluidfft for the Optimal Choice of HPC FFT Library: A 3D Seismic
  Modeling Example'
subtitle: ''
summary: ''
authors:
- admin
- R. Pestana
- D.E. Revelo
tags: []
categories: []
date: '2020-01-01'
lastmod: 2021-10-03T12:16:13-03:00
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
publishDate: '2021-10-03T15:16:07.083991Z'
publication_types:
- '6'
abstract: In this work, we illustrate a practical application of the use of Fluidfft, a newly developed common API (C++ and Python) for performing Fast Fourier Transforms (FFT) with different FFT libraries. Fluidfft is an open-source software aimed at filling the absence of a package with the ability to support multiple FFT libraries. It allows end-users (i.e., engineers/geophysicist) to create applications where any one of these libraries can be used while enabling to compare their performance. We developed and evaluated an implementation of the one-step wave extrapolation matrix (OSEM) method on a HPC cluster using the C++ programming language. The computational cost of this method lies in the application of a finite number of FFTs at each time step in order to compute a pseudodifferential operator and, therefore the selection of a suitable FFT library is crucial for optimal performance. We analyzed the impact of the different FFT libraries (fluidfft classes) on the runtime and show how the use of fluidfft facilitates the selection of the optimal one.
publication: '*Conference Proceedings, EAGE 2020 Annual Conference & Exhibition Online, Dec 2020, Volume 2020, p.1 - 5*'
url_pdf: https://www.earthdoc.org/content/papers/10.3997/2214-4609.202011816
doi: https://doi.org/10.3997/2214-4609.202011816
---
