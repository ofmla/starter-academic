---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Using SVD Filters for Velocity Analysis and Ground-roll Attenuation
subtitle: ''
summary: ''
authors:
- Oscar Mojica
- Milton Porsani
- Michelangelo Silva
tags:
- '"CMP stacking; seismic processing; SVD filtering; ground-roll attenuation; velocity
  analysis"'
categories: []
date: '2013-01-01'
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
publishDate: '2020-12-23T19:00:19.737985Z'
publication_types:
- '2'
abstract: 'This study investigates the adaptive filtering approach based on the Singular
  Value Decomposition (SVD) method to improve velocity analysis and ground-roll attenuation.
  The SVD filtering is an adaptive multichannel filtering method where each filtered
  seismic trace keeps a degree of coherence with the immediate neighboring traces.
  Before applying the adaptive filtering, in order to flatten the primary reflections
  the seismogram is corrected using the Normal Move Out (NMO) method. The SVD filtering
  helps to strengthen the spatial coherence of reflectors. It works as multichannel
  and can be applied by selecting a set of seismic traces taken from around the target
  trace. Thus traces from different shots can be represented by a five-point areal
  operator, which we call five-point cross operator. In this paper we run this operator
  along the coverage map of the seismic survey. At each operator position, the filtered
  trace (center of the operator) is obtained by taking the firstor adding the first
  eigenimages. Thereby we enhance the coherence corresponding to the primary reflections
  in detriment of the remaining events (ground-roll, multiples, and other non-correlated
  events) remained in the other eigenimages. The method was tested on a seismic line
  of the Tacutu, Brazil. The obtained results show the velocity spectra with better
  definition, as well as better post-stacked section exhibiting better continuity
  of seismic reflections and lower noise, compared with the raw processing results
  (without SVD filtering).RESUMO. No presente trabalho aplicamos o método de filtragem
  adaptativa baseada no método SVD (Singular Value Decomposition) para a melhoria
  da análise de velocidades e atenuação do ruído coerente associado à fonte sísmica
  (ground-roll). A filtragem SVD pode ser vista como um método de filtragem adaptativa
  multicanal onde cada traço filtrado guarda certo grau de coerência com os traços
  imediatamente vizinhos. Antes da aplicação do método é feita a correção de decalagem
  normal (normal move out - NMO) dos sismogramas, tendo como finalidade deixar as
  reflexões de interesse aproximadamente horizontais. A filtragem SVD permite reforçar
  a coerência espacial dos refletores. Ela trabalha na forma multicanal e pode ser
  aplicada seguindo um procedimento padrão que consiste na seleção de um conjunto
  de traços tomados ao redor do traço-alvo da filtragem. Desta forma traços de diferentes
  tiros podem ser utilizados na filtragem SVD. A coleta de traços pertencentes a diferentes
  tiros, no mapa de cobertura, pode ser representada por um operador espacial de cinco
  pontos que denominamos de operador em cruz. No presente trabalho utilizamos um operador
  de cinco pontos que opera sobre todos os traços do mapa de cobertura do levantamento
  sísmico. A cada posição do operador, o traço filtrado (centro do operador) é obtido
  tomando-se a primeira ou somando-se a(s) primeira(s) autoimagem(ns) do painel de
  5 traços selecionados. Desta forma, reforçamos a coerência correspondente às reflexões
  primárias, em detrimento dos eventos restantes (ground-roll, múltiplas e demais
  eventos não correlacionados), localizado nas demais autoimagens. O método foi testado
  sobre uma linha sísmica terrestre da Bacia do Tacutu, Brasil. Os resultados obtidos
  mostram espectros de velocidades com melhor definição, como também seções empilhadas
  exibindo melhor continuidade das reflexões e menor ruído ground-roll, comparado
  com os resultados do processamento bruto (sem a filtragem SVD).Palavras-chave: empilhamento
  CMP; processamento sísmico; filtragem SVD, atenuação do ground-roll; análise de
  velocidade'
publication: '*Brazilian Journal of Geophysics*'
url_pdf: https://www.sbgf.org.br/revista/index.php/rbgf/article/view/247
doi: 10.22564/rbgf.v31i1.247
---
