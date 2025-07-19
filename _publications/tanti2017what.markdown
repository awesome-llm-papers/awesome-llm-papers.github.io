---
layout: publication
title: What Is The Role Of Recurrent Neural Networks (rnns) In An Image Caption Generator?
authors: Tanti Marc, Gatt Albert, Camilleri Kenneth P.
conference: Proceedings of the 10th International Conference on Natural Language Generation
year: 2017
bibkey: tanti2017what
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1708.02043'}]
tags: [Alt, Model Architecture, Merging]
---
In neural image captioning systems, a recurrent neural network (RNN) is
typically viewed as the primary `generation' component. This view suggests that
the image features should be `injected' into the RNN. This is in fact the
dominant view in the literature. Alternatively, the RNN can instead be viewed
as only encoding the previously generated words. This view suggests that the
RNN should only be used to encode linguistic features and that only the final
representation should be `merged' with the image features at a later stage.
This paper compares these two architectures. We find that, in general, late
merging outperforms injection, suggesting that RNNs are better viewed as
encoders, rather than generators.