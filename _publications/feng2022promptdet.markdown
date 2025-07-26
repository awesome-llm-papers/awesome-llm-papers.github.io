---
layout: publication
title: 'Promptdet: Towards Open-vocabulary Detection Using Uncurated Images'
authors: Chengjian Feng, Yujie Zhong, Zequn Jie, Xiangxiang Chu, Haibing Ren, Xiaolin
  Wei, Weidi Xie, Lin Ma
conference: Lecture Notes in Computer Science
year: 2022
bibkey: feng2022promptdet
citations: 89
additional_links: [{name: Code, url: 'https://fcjian.github.io/promptdet'}, {name: Paper,
    url: 'https://arxiv.org/abs/2203.16513'}]
tags: ["Datasets", "Prompting", "Tools"]
short_authors: Feng et al.
---
The goal of this work is to establish a scalable pipeline for expanding an
object detector towards novel/unseen categories, using zero manual annotations.
To achieve that, we make the following four contributions: (i) in pursuit of
generalisation, we propose a two-stage open-vocabulary object detector, where
the class-agnostic object proposals are classified with a text encoder from
pre-trained visual-language model; (ii) To pair the visual latent space (of RPN
box proposals) with that of the pre-trained text encoder, we propose the idea
of regional prompt learning to align the textual embedding space with regional
visual object features; (iii) To scale up the learning procedure towards
detecting a wider spectrum of objects, we exploit the available online resource
via a novel self-training framework, which allows to train the proposed
detector on a large corpus of noisy uncurated web images. Lastly, (iv) to
evaluate our proposed detector, termed as PromptDet, we conduct extensive
experiments on the challenging LVIS and MS-COCO dataset. PromptDet shows
superior performance over existing approaches with fewer additional training
images and zero manual annotations whatsoever. Project page with code:
https://fcjian.github.io/promptdet.