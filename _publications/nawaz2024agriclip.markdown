---
layout: publication
title: 'Agriclip: Adapting CLIP For Agriculture And Livestock Via Domain-specialized
  Cross-model Alignment'
authors: Nawaz et al.
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: nawaz2024agriclip
citations: 287
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.01407'}]
tags: [RAG, Training Techniques, Alt, Prompting, Tools, CVPR, Applications, Multimodal
    Models, Datasets]
---
Capitalizing on vast amount of image-text data, large-scale vision-language
pre-training has demonstrated remarkable zero-shot capabilities and has been
utilized in several applications. However, models trained on general everyday
web-crawled data often exhibit sub-optimal performance for specialized domains,
likely due to domain shift. Recent works have tackled this problem for some
domains (e.g., healthcare) by constructing domain-specialized image-text data.
However, constructing a dedicated large-scale image-text dataset for
sustainable area of agriculture and livestock is still open to research.
Further, this domain desires fine-grained feature learning due to the subtle
nature of the downstream tasks (e.g, nutrient deficiency detection, livestock
breed classification). To address this we present AgriCLIP, a vision-language
foundational model dedicated to the domain of agriculture and livestock. First,
we propose a large-scale dataset, named ALive, that leverages customized prompt
generation strategy to overcome the scarcity of expert annotations. Our ALive
dataset covers crops, livestock, and fishery, with around 600,000 image-text
pairs. Second, we propose a training pipeline that integrates both contrastive
and self-supervised learning to learn both global semantic and local
fine-grained domain-specialized features. Experiments on diverse set of 20
downstream tasks demonstrate the effectiveness of AgriCLIP framework, achieving
an absolute gain of 7.8% in terms of average zero-shot classification
accuracy, over the standard CLIP adaptation via domain-specialized ALive
dataset. Our ALive dataset and code can be accessible at
\href\{https://github.com/umair1221/AgriCLIP/tree/main\}\{Github\}.