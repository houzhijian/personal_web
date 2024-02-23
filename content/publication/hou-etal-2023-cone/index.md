---
title: 'CONE: An Efficient COarse-to-fiNE Alignment Framework for Long Video Temporal
  Grounding'
authors:
- Zhijian Hou
- Wanjun Zhong
- Lei Ji
- Difei Gao
- Kun Yan
- W.k. Chan
- Chong-Wah Ngo
- Mike Zheng Shou
- Nan Duan
date: '2023-07-01'
publishDate: '2024-02-22T07:54:55.420764Z'
publication_types:
- paper-conference
publication: '*Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)*'
doi: 10.18653/v1/2023.acl-long.445
abstract: This paper tackles an emerging and challenging problem of long video temporal
  grounding (VTG) that localizes video moments related to a natural language (NL)
  query. Compared with short videos, long videos are also highly demanded but less
  explored, which brings new challenges in higher inference computation cost and weaker
  multi-modal alignment. To address these challenges, we propose CONE, an efficient
  COarse-to-fiNE alignment framework. CONE is a plug-and-play framework on top of
  existing VTG models to handle long videos through a sliding window mechanism. Specifically,
  CONE (1) introduces a query-guided window selection strategy to speed up inference,
  and (2) proposes a coarse-to-fine mechanism via a novel incorporation of contrastive
  learning to enhance multi-modal alignment for long videos. Extensive experiments
  on two large-scale long VTG benchmarks consistently show both substantial performance
  gains (e.g., from 3.13 to 6.87% on MAD) and state-of-the-art results. Analyses also
  reveal higher efficiency as the query-guided window selection mechanism accelerates
  inference time by 2x on Ego4D-NLQ and 15x on MAD while keeping SOTA results. Codes
  have been released at r̆lhttps://github.com/houzhijian/CONE.
links:
- icon_pack: fab
  icon: scroll
  name: URL
  url: https://aclanthology.org/2023.acl-long.445
- icon_pack: fab
  icon: github
  name: code
  url: lhttps://github.com/houzhijian/CONE
---
