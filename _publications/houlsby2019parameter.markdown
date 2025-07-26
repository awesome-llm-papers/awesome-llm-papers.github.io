---
layout: publication
title: Parameter-efficient Transfer Learning For NLP
authors: Neil Houlsby, Andrei Giurgiu, Stanislaw Jastrzebski, Bruna Morrone, Quentin
  de Laroussilhe, Andrea Gesmundo, Mona Attariyan, Sylvain Gelly
conference: Arxiv
year: 2019
bibkey: houlsby2019parameter
citations: 1102
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.00751'}]
tags: ["Fine-Tuning", "Model Architecture"]
short_authors: Houlsby et al.
---
Fine-tuning large pre-trained models is an effective transfer mechanism in
NLP. However, in the presence of many downstream tasks, fine-tuning is
parameter inefficient: an entire new model is required for every task. As an
alternative, we propose transfer with adapter modules. Adapter modules yield a
compact and extensible model; they add only a few trainable parameters per
task, and new tasks can be added without revisiting previous ones. The
parameters of the original network remain fixed, yielding a high degree of
parameter sharing. To demonstrate adapter's effectiveness, we transfer the
recently proposed BERT Transformer model to 26 diverse text classification
tasks, including the GLUE benchmark. Adapters attain near state-of-the-art
performance, whilst adding only a few parameters per task. On GLUE, we attain
within 0.4% of the performance of full fine-tuning, adding only 3.6% parameters
per task. By contrast, fine-tuning trains 100% of the parameters per task.