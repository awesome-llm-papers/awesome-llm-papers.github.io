---
layout: publication
title: 'Howto100m: Learning A Text-video Embedding By Watching Hundred Million Narrated
  Video Clips'
authors: Antoine Miech, Dimitri Zhukov, Jean-baptiste Alayrac, Makarand Tapaswi, Ivan
  Laptev, Josef Sivic
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2019
bibkey: miech2019howto100m
citations: 782
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.03327'}]
tags: ["Datasets", "ICCV"]
short_authors: Miech et al.
---
Learning text-video embeddings usually requires a dataset of video clips with
manually provided captions. However, such datasets are expensive and time
consuming to create and therefore difficult to obtain on a large scale. In this
work, we propose instead to learn such embeddings from video data with readily
available natural language annotations in the form of automatically transcribed
narrations. The contributions of this work are three-fold. First, we introduce
HowTo100M: a large-scale dataset of 136 million video clips sourced from 1.22M
narrated instructional web videos depicting humans performing and describing
over 23k different visual tasks. Our data collection procedure is fast,
scalable and does not require any additional manual annotation. Second, we
demonstrate that a text-video embedding trained on this data leads to
state-of-the-art results for text-to-video retrieval and action localization on
instructional video datasets such as YouCook2 or CrossTask. Finally, we show
that this embedding transfers well to other domains: fine-tuning on generic
Youtube videos (MSR-VTT dataset) and movies (LSMDC dataset) outperforms models
trained on these datasets alone. Our dataset, code and models will be publicly
available at: www.di.ens.fr/willow/research/howto100m/.