---
# Documentation: https://wowchemy.com/docs/managing-content/

title: A parallel improved PSO algorithm with genetic operators for 2D inversion of resistivity data
subtitle: ''
summary: ''
authors:
- Jorge Abril
- Marcos Vasconcelos
- Francisco Braboza
- Oscar Mojica
tags:
- '"Constrained inversion;
Electrical resistivity imaging;
Particle swarm optimization;
Parallel computing"'
categories: []
date: '2022-04-02'
lastmod: 2022-04-02
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
publishDate: '2022-04-02'
publication_types:
- '2'
abstract: 'In this paper, an improved particle swarm optimization technique known as elitist-mutated particle swarm optimization (EMPSO) was applied in the 2D electrical resistivity imaging, a complex and highly nonlinear optimization problem. The EMPSO enables better exploration of the search space, by replacing particles with a worse performance by the best particle of the swarm mutated in random positions. Nevertheless, this technique, as any other based on a population of models, costs much computation time in solving optimization problems with a large number of unknown parameters. We addressed this problem by developing a parallel version of the EMPSO that supports pure MPI and hybrid MPI-OpenMP modes, and we named as parallel elitist-mutated PSO (PEMPSO). The solution to the inverse problem is based on minimizing an objective function with a regularization term to create a mathematically stable solution. Total variation and global smoothness regularizations were used in the inversion of synthetic data obtained from simple models and a set of real data of a highly complex geological/geotechnical nature. By virtue of the features of the synthetic models and the geology of the local where the data were acquired, the inversions with total variation regularization provided the best outcomes. Additionally, we have improved the execution time significantly with our parallel solution (the pure MPI model turned out to be better than the hybrid model) in comparison with the sequential version. Cumulative frequency distribution of errors between modeled and observed apparent resistivity data for all experiments was used to validate the PEMPSO technique for estimating resistivity.'
publication: '*Acta Geophysica*'
url_pdf: https://doi.org/10.1007/s11600-022-00760-4
doi: 10.1007/s11600-022-00760-4
---
