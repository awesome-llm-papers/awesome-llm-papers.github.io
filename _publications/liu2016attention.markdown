---
layout: publication
title: Attention-based Recurrent Neural Network Models For Joint Intent Detection
  And Slot Filling
authors: Bing Liu, Ian Lane
conference: Interspeech 2016
year: 2016
bibkey: liu2016attention
citations: 720
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1609.01454'}]
tags: ["INTERSPEECH", "Model Architecture"]
short_authors: Bing Liu, Ian Lane
---
Attention-based encoder-decoder neural network models have recently shown
promising results in machine translation and speech recognition. In this work,
we propose an attention-based neural network model for joint intent detection
and slot filling, both of which are critical steps for many speech
understanding and dialog systems. Unlike in machine translation and speech
recognition, alignment is explicit in slot filling. We explore different
strategies in incorporating this alignment information to the encoder-decoder
framework. Learning from the attention mechanism in encoder-decoder model, we
further propose introducing attention to the alignment-based RNN models. Such
attentions provide additional information to the intent classification and slot
label prediction. Our independent task models achieve state-of-the-art intent
detection error rate and slot filling F1 score on the benchmark ATIS task. Our
joint training model further obtains 0.56% absolute (23.8% relative) error
reduction on intent detection and 0.23% absolute gain on slot filling over the
independent task models.