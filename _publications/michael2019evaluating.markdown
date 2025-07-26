---
layout: publication
title: Evaluating Sequence-to-sequence Models For Handwritten Text Recognition
authors: "Johannes Michael, Roger Labahn, Tobias Gr\xFCning, Jochen Z\xF6llner"
conference: 2019 International Conference on Document Analysis and Recognition (ICDAR)
year: 2019
bibkey: michael2019evaluating
citations: 107
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1903.07377'}]
tags: ["Evaluation"]
short_authors: Michael et al.
---
Encoder-decoder models have become an effective approach for sequence
learning tasks like machine translation, image captioning and speech
recognition, but have yet to show competitive results for handwritten text
recognition. To this end, we propose an attention-based sequence-to-sequence
model. It combines a convolutional neural network as a generic feature
extractor with a recurrent neural network to encode both the visual
information, as well as the temporal context between characters in the input
image, and uses a separate recurrent neural network to decode the actual
character sequence. We make experimental comparisons between various attention
mechanisms and positional encodings, in order to find an appropriate alignment
between the input and output sequence. The model can be trained end-to-end and
the optional integration of a hybrid loss allows the encoder to retain an
interpretable and usable output, if desired. We achieve competitive results on
the IAM and ICFHR2016 READ data sets compared to the state-of-the-art without
the use of a language model, and we significantly improve over any recent
sequence-to-sequence approaches.