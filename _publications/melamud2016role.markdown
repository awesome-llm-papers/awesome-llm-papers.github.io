---
layout: publication
title: The Role Of Context Types And Dimensionality In Learning Word Embeddings
authors: Oren Melamud, David Mcclosky, Siddharth Patwardhan, Mohit Bansal
conference: 'Proceedings of the 2016 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2016
bibkey: melamud2016role
citations: 105
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1601.00893'}]
tags: ["NAACL"]
short_authors: Melamud et al.
---
We provide the first extensive evaluation of how using different types of
context to learn skip-gram word embeddings affects performance on a wide range
of intrinsic and extrinsic NLP tasks. Our results suggest that while intrinsic
tasks tend to exhibit a clear preference to particular types of contexts and
higher dimensionality, more careful tuning is required for finding the optimal
settings for most of the extrinsic tasks that we considered. Furthermore, for
these extrinsic tasks, we find that once the benefit from increasing the
embedding dimensionality is mostly exhausted, simple concatenation of word
embeddings, learned with different context types, can yield further performance
gains. As an additional contribution, we propose a new variant of the skip-gram
model that learns word embeddings from weighted contexts of substitute words.