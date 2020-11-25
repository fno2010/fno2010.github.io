---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Prophet: Toward Fast, Error-Tolerant Model-Based Throughput Prediction for
  Reactive Flows in DC Networks'
subtitle: ''
summary: ''
authors:
- Jingxuan Zhang
- Kai Gao
- Y. Richard Yang
- Jun Bi
tags: []
categories: []
date: '2020-08-26'
lastmod: 2020-11-25T11:03:05+08:00
featured: true
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
publishDate: '2020-11-25T03:03:05.408611Z'
publication_types:
- 2
abstract: As modern network applications (e.g., large data analytics) become more
  distributed and can conduct application-layer traffic adaptation, they demand better
  network visibility to better orchestrate their data flows. As a result, the ability
  to predict the available bandwidth for a set of flows has become a fundamental requirement
  of today's networking systems. While there are previous studies addressing the case
  of non-reactive flows, the prediction for reactive flows, e.g., flows managed by
  TCP congestion control algorithms, still remains an open problem. In this paper,
  we take the first step to solving this problem in a data center network. To address
  both theoretical and practical challenges, we introduce a novel learning-based prediction
  system based on the NUM model, with two key techniques named fast factor learning
  (FFL) and efficient flow sampling. We adopt novel techniques to overcome practical
  concerns such as scalability, convergence and unknown system parameters. A system,
  Prophet, is proposed leveraging the emerging technologies of Software Defined Networking
  (SDN) to realize the model. Evaluations demonstrate that our solution achieves significant
  accuracy in a wide range of settings.
publication: '*IEEE/ACM Transactions on Networking*'
doi: 10.1109/TNET.2020.3016838

# Resources
url_code: https://github.com/fno2010/arsa-analyze
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9178502
---
