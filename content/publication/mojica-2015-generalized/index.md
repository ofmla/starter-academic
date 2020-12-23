---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Generalized cross-validation and Regı́nska's methods for choosing the regularization
  parameter in 3D gravity inversion of basement relief-a hybrid MPI/OpenMP parallel
  algorithm
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
publishDate: '2020-12-23T19:00:19.474369Z'
publication_types:
- '1'
abstract: This paper addresses the problem of gravity inversion to determine the 3D basement relief of sedimentary basins. It is a nonlinear optimization problem where the gravity anomalies attributable to basement interfaces above which the density contrast varies continuosly with the depth are analyzed. We use the Levenberg-Marquardt (LM) algorithm which needs a key input parameter called the regularization parameter λ to deal with the singularity of the normal equation matrix in the linearized problem at each iteration. The generalized cross-validation (GCV) and Regińska’s methods for estimating the optimal regularization parameter are tested through numerical experiments on a synthetic data set. Also, we implemented the LM algorithm with a hybrid message passing interface (MPI) and Open Multi-Processing (OpenMP) approach to avoid the high proccesing time. This lead to a fast and reliable algorithm, which produced satisfactory results in mapping the basement topography.
publication: '*14th International Congress of the Brazilian Geophysical Society &
  EXPOGEF, Rio de Janeiro, Brazil, 3-6 August 2015*'
doi: https://doi.org/10.1190/sbgf2015-135
---
