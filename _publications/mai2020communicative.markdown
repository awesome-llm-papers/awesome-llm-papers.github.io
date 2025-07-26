---
layout: publication
title: Communicative Message Passing For Inductive Relation Reasoning
authors: Sijie Mai, Shuangjia Zheng, Yuedong Yang, Haifeng Hu
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2021
bibkey: mai2020communicative
citations: 72
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.08911'}]
tags: ["AAAI"]
short_authors: Mai et al.
---
Relation prediction for knowledge graphs aims at predicting missing
relationships between entities. Despite the importance of inductive relation
prediction, most previous works are limited to a transductive setting and
cannot process previously unseen entities. The recent proposed subgraph-based
relation reasoning models provided alternatives to predict links from the
subgraph structure surrounding a candidate triplet inductively. However, we
observe that these methods often neglect the directed nature of the extracted
subgraph and weaken the role of relation information in the subgraph modeling.
As a result, they fail to effectively handle the asymmetric/anti-symmetric
triplets and produce insufficient embeddings for the target triplets. To this
end, we introduce a \textbf\{C\}\textbf\{o\}mmunicative \textbf\{M\}essage
\textbf\{P\}assing neural network for \textbf\{I\}nductive re\textbf\{L\}ation
r\textbf\{E\}asoning, \textbf\{CoMPILE\}, that reasons over local directed subgraph
structures and has a vigorous inductive bias to process entity-independent
semantic relations. In contrast to existing models, CoMPILE strengthens the
message interactions between edges and entitles through a communicative kernel
and enables a sufficient flow of relation information. Moreover, we demonstrate
that CoMPILE can naturally handle asymmetric/anti-symmetric relations without
the need for explosively increasing the number of model parameters by
extracting the directed enclosing subgraphs. Extensive experiments show
substantial performance gains in comparison to state-of-the-art methods on
commonly used benchmark datasets with variant inductive settings.