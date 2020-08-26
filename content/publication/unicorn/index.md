---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'Unicorn: Unified Resource Orchestration for Multi-Domain, Geo-Distributed
  Data Analytics'
subtitle: ''
summary: ''
authors:
- Qiao Xiang
- X. Tony Wang
- J. Jensen Zhang
- Harvey Newman
- Y. Richard Yang
- Y. Jace Liu
tags: []
categories: []
date: '2019-04-01'
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
publishDate: '2020-08-25T23:26:17.575473Z'
publication_types:
- 2
abstract: 'As the data volume increases exponentially over time, data-intensive analytics
  benefits substantially from multi-organizational, geographically-distributed, collaborative
  computing, where different organizations contribute various yet scarce resources,
  e.g., computation, storage and networking resources, to collaboratively collect,
  share and analyze extremely large amounts of data. By analyzing the data analytics
  trace from the Compact Muon Solenoid (CMS) experiment, one of the largest scientific
  experiments in the world, and systematically examining the design of existing resource
  management systems for clusters, we show that the multi-domain, geo-distributed,
  resource-disaggregated nature of this new paradigm calls for a framework to manage
  a large set of distributively-owned, heterogeneous resources, with the objective
  of efficient resource utilization, following the autonomy and privacy of different
  domains, and that the fundamental challenge for designing such a framework is: how
  to accurately discover and represent resource availability of a large set of distributively-owned,
  heterogeneous resources across different domains with minimal information exposure
  from each domain? Existing resource management systems are designed for single-domain
  clusters and cannot address this challenge. In this paper, we design Unicorn, the
  first unified resource orchestration framework for multi-domain, geo-distributed
  data analytics. In Unicorn, we encode the resource availability for each domain
  into resource state abstraction, a variant of the network view abstraction extended
  to accurately represent the availability of multiple resources with minimal information
  exposure using a set of linear inequalities. We then design a novel, efficient cross-domain
  query algorithm and a privacy-preserving resource information integration protocol
  to discover and integrate the accurate, minimal resource availability information
  for a set of data analytics jobs across different domains. In addition, Unicorn
  also contains a global resource orchestrator that computes optimal resource allocation
  decisions for data analytics jobs. We implement a prototype of Unicorn and present
  preliminary evaluation results to demonstrate its efficiency and efficacy. We also
  give a full demonstration of the Unicorn system at SuperComputing 2017.'
publication: '*Future Generation Computer Systems*'
url_pdf: https://linkinghub.elsevier.com/retrieve/pii/S0167739X18302413
doi: 10.1016/j.future.2018.09.048
---
