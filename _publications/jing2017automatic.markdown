---
layout: publication
title: On The Automatic Generation Of Medical Imaging Reports
authors: Baoyu Jing, Pengtao Xie, Eric Xing
conference: 'Proceedings of the 56th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2018
bibkey: jing2017automatic
citations: 491
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1711.08195'}]
tags: ["Tools"]
short_authors: Baoyu Jing, Pengtao Xie, Eric Xing
---
Medical imaging is widely used in clinical practice for diagnosis and
treatment. Report-writing can be error-prone for unexperienced physicians, and
time- consuming and tedious for experienced physicians. To address these
issues, we study the automatic generation of medical imaging reports. This task
presents several challenges. First, a complete report contains multiple
heterogeneous forms of information, including findings and tags. Second,
abnormal regions in medical images are difficult to identify. Third, the re-
ports are typically long, containing multiple sentences. To cope with these
challenges, we (1) build a multi-task learning framework which jointly performs
the pre- diction of tags and the generation of para- graphs, (2) propose a
co-attention mechanism to localize regions containing abnormalities and
generate narrations for them, (3) develop a hierarchical LSTM model to generate
long paragraphs. We demonstrate the effectiveness of the proposed methods on
two publicly available datasets.