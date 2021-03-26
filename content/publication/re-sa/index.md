---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Fine-Grained, Multi-Domain Network Resource Abstraction as a Fundamental Primitive
  to Enable High-Performance, Collaborative Data Sciences
subtitle: ''
summary: ''
authors:
- Qiao Xiang
- Jingxuan Zhang
- Xin Wang
- Yang Liu
- Chin Guok
- Franck Le
- John MacAuley
- Harvey Newman
- Y. Richard Yang
tags:
- Bandwidth
- Servers
- Routing protocols
- Privacy
- Scalability
- Network topology
categories: []
date: '2018-11-01'
lastmod: 2020-08-25T19:26:17-04:00
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
publishDate: '2020-08-25T23:26:17.764965Z'
publication_types:
- 1
abstract: Multi-domain network resource reservation systems are being deployed, driven
  by the demand and substantial benefits of providing predictable network resources.
  However, a major lack of existing systems is their coarse granularity, due to the
  participating networks' concern of revealing sensitive information, which can result
  in substantial inefficiencies. This paper presents Mercator, a novel multi-domain
  network resource discovery system to provide fine-grained, global network resource
  information, for collaborative sciences. The foundation of Mercator is a resource
  abstraction through algebraic-expression enumeration (i.e., linear inequalities/equations),
  as a compact representation of the available bandwidth in multi-domain networks.
  In addition, we develop an obfuscating protocol, to address the privacy concerns
  by ensuring that no participant can associate the algebraic expressions with the
  corresponding member networks. We also introduce a super-set projection technique
  to increase Mercator's scalability. Finally, we implement Mercator and demonstrate
  both its efficiency and efficacy through extensive experiments using real topologies
  and traces.
publication: '*SC18: International Conference for High Performance Computing, Networking,
  Storage and Analysis*'
url_pdf: https://ieeexplore.ieee.org/document/8665783/
doi: 10.1109/SC.2018.00008
---
