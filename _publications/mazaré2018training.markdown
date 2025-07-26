---
layout: publication
title: Training Millions Of Personalized Dialogue Agents
authors: "Pierre-emmanuel Mazar\xE9, Samuel Humeau, Martin Raison, Antoine Bordes"
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: "mazar\xE92018training"
citations: 217
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.01984'}]
tags: ["EMNLP"]
short_authors: "Mazar\xE9 et al."
---
Current dialogue systems are not very engaging for users, especially when
trained end-to-end without relying on proactive reengaging scripted strategies.
Zhang et al. (2018) showed that the engagement level of end-to-end dialogue
models increases when conditioning them on text personas providing some
personalized back-story to the model. However, the dataset used in Zhang et al.
(2018) is synthetic and of limited size as it contains around 1k different
personas. In this paper we introduce a new dataset providing 5 million personas
and 700 million persona-based dialogues. Our experiments show that, at this
scale, training using personas still improves the performance of end-to-end
systems. In addition, we show that other tasks benefit from the wide coverage
of our dataset by fine-tuning our model on the data from Zhang et al. (2018)
and achieving state-of-the-art results.