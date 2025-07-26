---
layout: publication
title: 'Clipcap: CLIP Prefix For Image Captioning'
authors: Ron Mokady, Amir Hertz, Amit H. Bermano
conference: Arxiv
year: 2021
bibkey: mokady2021clipcap
citations: 275
additional_links: [{name: Code, url: 'https://github.com/rmokady/CLIP_prefix_caption'},
  {name: Paper, url: 'https://arxiv.org/abs/2111.09734'}]
tags: ["Model Architecture"]
short_authors: Ron Mokady, Amir Hertz, Amit H. Bermano
---
Image captioning is a fundamental task in vision-language understanding,
where the model predicts a textual informative caption to a given input image.
In this paper, we present a simple approach to address this task. We use CLIP
encoding as a prefix to the caption, by employing a simple mapping network, and
then fine-tunes a language model to generate the image captions. The recently
proposed CLIP model contains rich semantic features which were trained with
textual context, making it best for vision-language perception. Our key idea is
that together with a pre-trained language model (GPT2), we obtain a wide
understanding of both visual and textual data. Hence, our approach only
requires rather quick training to produce a competent captioning model. Without
additional annotations or pre-training, it efficiently generates meaningful
captions for large-scale and diverse datasets. Surprisingly, our method works
well even when only the mapping network is trained, while both CLIP and the
language model remain frozen, allowing a lighter architecture with less
trainable parameters. Through quantitative evaluation, we demonstrate our model
achieves comparable results to state-of-the-art methods on the challenging
Conceptual Captions and nocaps datasets, while it is simpler, faster, and
lighter. Our code is available in
https://github.com/rmokady/CLIP_prefix_caption.