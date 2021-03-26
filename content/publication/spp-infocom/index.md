---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Looking for the Maximum Independent Set: A New Perspective on the Stable Path
  Problem'
subtitle: ''
summary: ''
authors:
- Yichao Chen
- Ning Luo
- Jingxuan Zhang
- Timos Antonopoulos
- Ruzica Piskac
- Qiao Xiang
tags: []
categories: []
date: '2021-04-01'
lastmod: 2021-03-26T10:19:10+08:00
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
publishDate: '2021-03-26T02:19:10.472732Z'
publication_types:
- 1
abstract: 'The stable path problem (SPP) is a unified model for analyzing the convergence
  of distributed routing protocols (e.g., BGP), and a foundation for many network
  verification tools. Although substantial progress has been made on finding solutions
  (i.e., stable path assignments) for particular subclasses of SPP instances and analyzing
  the relation between properties of SPP instances and the convergence of corresponding
  routing policies, the non-trivial challenge of finding stable path assignments to
  generic SPP instances still remains. Tackling this challenge is important because
  it can enable multiple important, novel routing use cases. To fill this gap, in
  this paper we introduce a novel data structure called solvability digraph, which
  encodes key properties about stable path assignments in a compact graph representation.
  Thus SPP is equivalently transformed to the problem of finding in the solvability
  digraph a maximum independent set (MIS) of size equal to the number of autonomous
  systems (ASes) in the given SPP instance. We leverage this key finding to develop
  a heuristic polynomial algorithm GREEDYMIS that solves strictly more SPP instances
  than state-of-the-art heuristics. We apply GREEDYMIS to designing two important,
  novel use cases: (1) a centralized interdomain routing system that uses GREEDYMIS
  to compute paths for ASes and (2) a secure multi-party computation (SMPC) protocol
  that allows ASes to use GREEDYMIS collaboratively to compute paths without exposing
  their routing preferences. We demonstrate the benefits and efficiency of these use
  cases via evaluation using real-world datasets.'
publication: '*IEEE INFOCOM 2021 - IEEE Conference on Computer Communications*'
url_pdf: /file/pub/spp-infocom.pdf
url_code: https://github.com/fno2010/spp-benchmark
---
