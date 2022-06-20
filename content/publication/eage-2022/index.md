---
# Documentation: https://wowchemy.com/docs/managing-content/

title: An Efficient Implementation of Least-Squares Reverse Time Migration Based on Stable Pseudo-Acoustic Tti Wave Equation
subtitle: ''
summary: ''
authors:
- admin
- R. Pestana
- A. Souza
tags: []
categories: []
date: '2022-06-09'
lastmod: 2022-06-09T21:51:20+0000
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
publishDate: '2022-06-09T21:51:20Z'
publication_types:
- '6'
abstract: Conventional tools for seismic imaging normally ignore the anisotropy of the media to produce images
of the subsurface and such omission reduces the quality of the images. Therefore, it is necessary to
develop methods which account for subsurface anisotropic properties in order to produce more accurate
images. In this paper, we present a Least-squares reverse time migration (LSRTM) based on the coupled
pseudo-acoustic equations for tilted transverse isotropic media (TTI). Thus, from the stable pseudo-
acoustic wave equation for TTI media, we derive the linearized modeling (Born modeling) and adjoint
migration operators to implement a TTI LSRTM. Then to improve the efficiency of inversion, we based
our implementation on the domain specific language (DSL) Devito, which, in turn, allowed us to easily
verify the correctness of the developed operators. Synthetic examples demonstrate the validity of our
approach in dealing with TTI media.
publication: '*Conference Proceedings, 83rd EAGE Conference and Exhibition 2022, Jun 2022, Volume 2022, p.1 - 5*'
url_pdf: https://www.earthdoc.org/content/papers/10.3997/2214-4609.202210281
doi: https://doi.org/10.3997/2214-4609.202210281
---
