---
layout: publication
title: Training Recurrent Answering Units With Joint Loss Minimization For VQA
authors: Hyeonwoo Noh, Bohyung Han
conference: Arxiv
year: 2016
bibkey: noh2016training
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.03647'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Hyeonwoo Noh, Bohyung Han
---
We propose a novel algorithm for visual question answering based on a
recurrent deep neural network, where every module in the network corresponds to
a complete answering unit with attention mechanism by itself. The network is
optimized by minimizing loss aggregated from all the units, which share model
parameters while receiving different information to compute attention
probability. For training, our model attends to a region within image feature
map, updates its memory based on the question and attended image feature, and
answers the question based on its memory state. This procedure is performed to
compute loss in each step. The motivation of this approach is our observation
that multi-step inferences are often required to answer questions while each
problem may have a unique desirable number of steps, which is difficult to
identify in practice. Hence, we always make the first unit in the network solve
problems, but allow it to learn the knowledge from the rest of units by
backpropagation unless it degrades the model. To implement this idea, we
early-stop training each unit as soon as it starts to overfit. Note that, since
more complex models tend to overfit on easier questions quickly, the last
answering unit in the unfolded recurrent neural network is typically killed
first while the first one remains last. We make a single-step prediction for a
new question using the shared model. This strategy works better than the other
options within our framework since the selected model is trained effectively
from all units without overfitting. The proposed algorithm outperforms other
multi-step attention based approaches using a single step prediction in VQA
dataset.