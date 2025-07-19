---
layout: publication
title: Interactive Path Reasoning On Graph For Conversational Recommendation
authors: Lei et al.
conference: Proceedings of the 26th ACM SIGKDD International Conference on Knowledge
  Discovery &amp; Data Mining
year: 2020
bibkey: lei2020interactive
citations: 202
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.00194'}]
tags: [RAG, Tools, Datasets, KDD]
---
Traditional recommendation systems estimate user preference on items from
past interaction history, thus suffering from the limitations of obtaining
fine-grained and dynamic user preference. Conversational recommendation system
(CRS) brings revolutions to those limitations by enabling the system to
directly ask users about their preferred attributes on items. However, existing
CRS methods do not make full use of such advantage -- they only use the
attribute feedback in rather implicit ways such as updating the latent user
representation. In this paper, we propose Conversational Path Reasoning (CPR),
a generic framework that models conversational recommendation as an interactive
path reasoning problem on a graph. It walks through the attribute vertices by
following user feedback, utilizing the user preferred attributes in an explicit
way. By leveraging on the graph structure, CPR is able to prune off many
irrelevant candidate attributes, leading to better chance of hitting user
preferred attributes. To demonstrate how CPR works, we propose a simple yet
effective instantiation named SCPR (Simple CPR). We perform empirical studies
on the multi-round conversational recommendation scenario, the most realistic
CRS setting so far that considers multiple rounds of asking attributes and
recommending items. Through extensive experiments on two datasets Yelp and
LastFM, we validate the effectiveness of our SCPR, which significantly
outperforms the state-of-the-art CRS methods EAR (arXiv:2002.09102) and CRM
(arXiv:1806.03277). In particular, we find that the more attributes there are,
the more advantages our method can achieve.