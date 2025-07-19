---
layout: publication
title: Multimodal Point-of-interest Recommendation
authors: Kanzawa et al.
conference: Proceedings of the 27th ACM International Conference on Information and
  Knowledge Management
year: 2024
bibkey: kanzawa2024multimodal
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.03265'}]
tags: [Multimodal Models, CIKM, Tools, Datasets]
---
Large Language Models are applied to recommendation tasks such as items to
buy and news articles to read. Point of Interest is quite a new area to
sequential recommendation based on language representations of multimodal
datasets. As a first step to prove our concepts, we focused on restaurant
recommendation based on each user's past visit history. When choosing a next
restaurant to visit, a user would consider genre and location of the venue and,
if available, pictures of dishes served there. We created a pseudo restaurant
check-in history dataset from the Foursquare dataset and the FoodX-251 dataset
by converting pictures into text descriptions with a multimodal model called
LLaVA, and used a language-based sequential recommendation framework named
Recformer proposed in 2023. A model trained on this semi-multimodal dataset has
outperformed another model trained on the same dataset without picture
descriptions. This suggests that this semi-multimodal model reflects actual
human behaviours and that our path to a multimodal recommendation model is in
the right direction.