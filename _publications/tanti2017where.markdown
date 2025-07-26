---
layout: publication
title: Where To Put The Image In An Image Caption Generator
authors: Marc Tanti, Albert Gatt, Kenneth P. Camilleri
conference: Natural Language Engineering
year: 2018
bibkey: tanti2017where
citations: 114
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1703.09137'}]
tags: ["Model Architecture"]
short_authors: Marc Tanti, Albert Gatt, Kenneth P. Camilleri
---
When a recurrent neural network language model is used for caption
generation, the image information can be fed to the neural network either by
directly incorporating it in the RNN -- conditioning the language model by
`injecting' image features -- or in a layer following the RNN -- conditioning
the language model by `merging' image features. While both options are attested
in the literature, there is as yet no systematic comparison between the two. In
this paper we empirically show that it is not especially detrimental to
performance whether one architecture is used or another. The merge architecture
does have practical advantages, as conditioning by merging allows the RNN's
hidden state vector to shrink in size by up to four times. Our results suggest
that the visual and linguistic modalities for caption generation need not be
jointly encoded by the RNN as that yields large, memory-intensive models with
few tangible advantages in performance; rather, the multimodal integration
should be delayed to a subsequent stage.