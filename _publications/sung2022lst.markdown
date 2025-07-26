---
layout: publication
title: 'LST: Ladder Side-tuning For Parameter And Memory Efficient Transfer Learning'
authors: Yi-lin Sung, Jaemin Cho, Mohit Bansal
conference: Arxiv
year: 2022
bibkey: sung2022lst
citations: 64
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2206.06522'}]
tags: ["Efficiency", "Fine-Tuning", "Training Techniques"]
short_authors: Yi-lin Sung, Jaemin Cho, Mohit Bansal
---
Fine-tuning large pre-trained models on downstream tasks has been adopted in
a variety of domains recently. However, it is costly to update the entire
parameter set of large pre-trained models. Although recently proposed
parameter-efficient transfer learning (PETL) techniques allow updating a small
subset of parameters (e.g. only using 2% of parameters) inside a pre-trained
backbone network for a new task, they only reduce the training memory
requirement by up to 30%. This is because the gradient computation for the
trainable parameters still requires backpropagation through the large
pre-trained backbone model. To address this, we propose Ladder Side-Tuning
(LST), a new PETL technique that can reduce training memory requirements by
more substantial amounts. Unlike existing parameter-efficient methods that
insert additional parameters inside backbone networks, we train a ladder side
network, a small and separate network that takes intermediate activations as
input via shortcut connections (called ladders) from backbone networks and
makes predictions. LST has significantly lower memory requirements than
previous methods, because it does not require backpropagation through the
backbone network, but instead only through the side network and ladder
connections. We evaluate our method with various models (T5 and CLIP-T5) on
both NLP (GLUE) and vision-and-language (VQA, GQA, NLVR2 , MSCOCO) tasks. LST
saves 69% of the memory costs to fine-tune the whole network, while other
methods only save 26% of that in similar parameter usages (hence, 2.7x more
memory savings). Moreover, LST achieves higher accuracy than Adapter and LoRA
in a low-memory regime. To further show the advantage of this better memory
efficiency, we also apply LST to larger T5 models, attaining better GLUE
performance than full fine-tuning and other PETL methods. The
accuracy-efficiency trade-off also holds on VL tasks.