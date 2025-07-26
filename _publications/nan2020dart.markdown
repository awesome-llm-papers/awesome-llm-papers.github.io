---
layout: publication
title: 'DART: Open-domain Structured Data Record To Text Generation'
authors: Linyong Nan, Dragomir Radev, Rui Zhang, Amrit Rau, Abhinand Sivaprasad, Chiachun
  Hsieh, Xiangru Tang, Aadit Vyas, Neha Verma, Pranav Krishna, Yangxiaokang Liu, Nadia
  Irwanto, Jessica Pan, Faiaz Rahman, Ahmad Zaidi, Mutethia Mutuma, Yasin Tarabar,
  Ankit Gupta, Tao Yu, Yi Chern Tan, Xi Victoria Lin, Caiming Xiong, Richard Socher,
  Nazneen Fatema Rajani
conference: 'Proceedings of the 2021 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2021
bibkey: nan2020dart
citations: 71
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.02871'}]
tags: ["Datasets", "Evaluation", "Has Code", "NAACL", "Tools"]
short_authors: Nan et al.
---
We present DART, an open domain structured DAta Record to Text generation
dataset with over 82k instances (DARTs). Data-to-Text annotations can be a
costly process, especially when dealing with tables which are the major source
of structured data and contain nontrivial structures. To this end, we propose a
procedure of extracting semantic triples from tables that encodes their
structures by exploiting the semantic dependencies among table headers and the
table title. Our dataset construction framework effectively merged
heterogeneous sources from open domain semantic parsing and dialogue-act-based
meaning representation tasks by utilizing techniques such as: tree ontology
annotation, question-answer pair to declarative sentence conversion, and
predicate unification, all with minimum post-editing. We present systematic
evaluation on DART as well as new state-of-the-art results on WebNLG 2017 to
show that DART (1) poses new challenges to existing data-to-text datasets and
(2) facilitates out-of-domain generalization. Our data and code can be found at
https://github.com/Yale-LILY/dart.