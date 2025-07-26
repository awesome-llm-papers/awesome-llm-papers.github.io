---
layout: publication
title: Generalized Data Augmentation For Low-resource Translation
authors: Mengzhou Xia, Xiang Kong, Antonios Anastasopoulos, Graham Neubig
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: xia2019generalized
citations: 110
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.03785'}]
tags: ["Datasets", "Tools"]
short_authors: Xia et al.
---
Translation to or from low-resource languages LRLs poses challenges for
machine translation in terms of both adequacy and fluency. Data augmentation
utilizing large amounts of monolingual data is regarded as an effective way to
alleviate these problems. In this paper, we propose a general framework for
data augmentation in low-resource machine translation that not only uses
target-side monolingual data, but also pivots through a related high-resource
language HRL. Specifically, we experiment with a two-step pivoting method to
convert high-resource data to the LRL, making use of available resources to
better approximate the true data distribution of the LRL. First, we inject LRL
words into HRL sentences through an induced bilingual dictionary. Second, we
further edit these modified sentences using a modified unsupervised machine
translation framework. Extensive experiments on four low-resource datasets show
that under extreme low-resource settings, our data augmentation techniques
improve translation quality by up to~1.5 to~8 BLEU points compared to
supervised back-translation baselines