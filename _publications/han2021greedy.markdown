---
layout: publication
title: Greedy Gradient Ensemble For Robust Visual Question Answering
authors: Xinzhe Han, Shuhui Wang, Chi Su, Qingming Huang, Qi Tian
conference: 2021 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2021
bibkey: han2021greedy
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2107.12651'}]
tags: ["ICCV"]
short_authors: Han et al.
---
Language bias is a critical issue in Visual Question Answering (VQA), where
models often exploit dataset biases for the final decision without considering
the image information. As a result, they suffer from performance drop on
out-of-distribution data and inadequate visual explanation. Based on
experimental analysis for existing robust VQA methods, we stress the language
bias in VQA that comes from two aspects, i.e., distribution bias and shortcut
bias. We further propose a new de-bias framework, Greedy Gradient Ensemble
(GGE), which combines multiple biased models for unbiased base model learning.
With the greedy strategy, GGE forces the biased models to over-fit the biased
data distribution in priority, thus makes the base model pay more attention to
examples that are hard to solve by biased models. The experiments demonstrate
that our method makes better use of visual information and achieves
state-of-the-art performance on diagnosing dataset VQA-CP without using extra
annotations.