---
layout: publication
title: Deep Relevance Ranking Using Enhanced Document-query Interactions
authors: Ryan Mcdonald, Georgios-ioannis Brokos, Ion Androutsopoulos
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: mcdonald2018deep
citations: 114
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.01682'}]
tags: ["EMNLP"]
short_authors: Ryan Mcdonald, Georgios-ioannis Brokos, Ion Androutsopoulos
---
We explore several new models for document relevance ranking, building upon
the Deep Relevance Matching Model (DRMM) of Guo et al. (2016). Unlike DRMM,
which uses context-insensitive encodings of terms and query-document term
interactions, we inject rich context-sensitive encodings throughout our models,
inspired by PACRR's (Hui et al., 2017) convolutional n-gram matching features,
but extended in several ways including multiple views of query and document
inputs. We test our models on datasets from the BIOASQ question answering
challenge (Tsatsaronis et al., 2015) and TREC ROBUST 2004 (Voorhees, 2005),
showing they outperform BM25-based baselines, DRMM, and PACRR.