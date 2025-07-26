---
layout: publication
title: 'Diverse Beam Search: Decoding Diverse Solutions From Neural Sequence Models'
authors: Ashwin K Vijayakumar, Michael Cogswell, Ramprasath R. Selvaraju, Qing Sun,
  Stefan Lee, David Crandall, Dhruv Batra
conference: Arxiv
year: 2016
bibkey: vijayakumar2016diverse
citations: 380
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1610.02424'}]
tags: ["Evaluation"]
short_authors: Vijayakumar et al.
---
Neural sequence models are widely used to model time-series data. Equally
ubiquitous is the usage of beam search (BS) as an approximate inference
algorithm to decode output sequences from these models. BS explores the search
space in a greedy left-right fashion retaining only the top-B candidates -
resulting in sequences that differ only slightly from each other. Producing
lists of nearly identical sequences is not only computationally wasteful but
also typically fails to capture the inherent ambiguity of complex AI tasks. To
overcome this problem, we propose Diverse Beam Search (DBS), an alternative to
BS that decodes a list of diverse outputs by optimizing for a
diversity-augmented objective. We observe that our method finds better top-1
solutions by controlling for the exploration and exploitation of the search
space - implying that DBS is a better search algorithm. Moreover, these gains
are achieved with minimal computational or memory over- head as compared to
beam search. To demonstrate the broad applicability of our method, we present
results on image captioning, machine translation and visual question generation
using both standard quantitative metrics and qualitative human studies.
Further, we study the role of diversity for image-grounded language generation
tasks as the complexity of the image changes. We observe that our method
consistently outperforms BS and previously proposed techniques for diverse
decoding from neural sequence models.