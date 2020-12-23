---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'Regularization parameter selection in the 3D gravity inversion of the basement
  relief using GCV: A parallel approach'
subtitle: ''
summary: ''
authors:
- admin
- A. Bassrei
tags:
- '"Generalized cross-validation"'
- '"Gravity modeling and inversion"'
- '"Linearized inversion"'
- '"Regularization"'
- '"Parallel processing"'
categories: []
date: '2015-01-01'
lastmod: 2020-12-23T16:22:03-03:00
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
publishDate: '2020-12-23T19:22:03.724511Z'
publication_types:
- '2'
abstract: In this study, we present a computationally efficient automatic method for
  the optimal selection of the regularization parameter in the 3D inversion of gravity
  data. We use a linearized inversion method to estimate the depth of a 3D sedimentary
  basin in which the density contrast varies parabolically with the depth. The sedimentary
  basin is discretized into rectangular juxtaposed prisms with thicknesses that represent
  the depths from the surface to the interface and are the parameters to be estimated
  in the inversion process from the gravity anomaly. To deal with the singularity
  of the normal equation matrix in the linearized least squares method, standard-form
  Tikhonov regularization is incorporated in each step. The Generalized cross-validation
  (GCV) technique, which is capable of finding the optimal regularization parameter
  in an automatic manner, is adopted in this study. We present the simulation results
  with a synthetic model of a complex sedimentary basin, taking advantage of a parallel
  inversion algorithm implemented by adopting the message passing interface (MPI)
  standard on a multi-core cluster. This makes it possible to reduce the computer
  time by more than one order of magnitude. The applicability and efficacy of the
  GCV technique for the selection of the optimum regularization parameter are demonstrated.
publication: '*Computers & Geosciences*'
url_pdf: http://www.sciencedirect.com/science/article/pii/S0098300415001442
doi: https://doi.org/10.1016/j.cageo.2015.06.013
---
