---
layout: publication
title: A Closer Look At Feature Space Data Augmentation For Few-shot Intent Classification
authors: Varun Kumar, Hadrien Glaude, Cyprien de Lichy, William Campbell
conference: Proceedings of the 2nd Workshop on Deep Learning Approaches for Low-Resource
  NLP (DeepLo 2019)
year: 2019
bibkey: kumar2019closer
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.04176'}]
tags: ["Few-Shot"]
short_authors: Kumar et al.
---
New conversation topics and functionalities are constantly being added to
conversational AI agents like Amazon Alexa and Apple Siri. As data collection
and annotation is not scalable and is often costly, only a handful of examples
for the new functionalities are available, which results in poor generalization
performance. We formulate it as a Few-Shot Integration (FSI) problem where a
few examples are used to introduce a new intent. In this paper, we study six
feature space data augmentation methods to improve classification performance
in FSI setting in combination with both supervised and unsupervised
representation learning methods such as BERT. Through realistic experiments on
two public conversational datasets, SNIPS, and the Facebook Dialog corpus, we
show that data augmentation in feature space provides an effective way to
improve intent classification performance in few-shot setting beyond
traditional transfer learning approaches. In particular, we show that (a)
upsampling in latent space is a competitive baseline for feature space
augmentation (b) adding the difference between two examples to a new example is
a simple yet effective data augmentation method.