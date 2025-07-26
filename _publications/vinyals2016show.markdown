---
layout: publication
title: 'Show And Tell: Lessons Learned From The 2015 MSCOCO Image Captioning Challenge'
authors: Oriol Vinyals, Alexander Toshev, Samy Bengio, Dumitru Erhan
conference: IEEE Transactions on Pattern Analysis and Machine Intelligence
year: 2016
bibkey: vinyals2016show
citations: 904
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1609.06647'}]
tags: ["Datasets", "Model Architecture", "Training Techniques"]
short_authors: Vinyals et al.
---
Automatically describing the content of an image is a fundamental problem in
artificial intelligence that connects computer vision and natural language
processing. In this paper, we present a generative model based on a deep
recurrent architecture that combines recent advances in computer vision and
machine translation and that can be used to generate natural sentences
describing an image. The model is trained to maximize the likelihood of the
target description sentence given the training image. Experiments on several
datasets show the accuracy of the model and the fluency of the language it
learns solely from image descriptions. Our model is often quite accurate, which
we verify both qualitatively and quantitatively. Finally, given the recent
surge of interest in this task, a competition was organized in 2015 using the
newly released COCO dataset. We describe and analyze the various improvements
we applied to our own baseline and show the resulting performance in the
competition, which we won ex-aequo with a team from Microsoft Research, and
provide an open source implementation in TensorFlow.