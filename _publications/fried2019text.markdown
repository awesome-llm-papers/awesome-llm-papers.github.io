---
layout: publication
title: Text-based Editing Of Talking-head Video
authors: Fried et al.
conference: ACM Transactions on Graphics
year: 2019
bibkey: fried2019text
citations: 256
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.01524'}]
tags: [Alt, Efficiency And Optimization, Datasets]
---
Editing talking-head video to change the speech content or to remove filler
words is challenging. We propose a novel method to edit talking-head video
based on its transcript to produce a realistic output video in which the
dialogue of the speaker has been modified, while maintaining a seamless
audio-visual flow (i.e. no jump cuts). Our method automatically annotates an
input talking-head video with phonemes, visemes, 3D face pose and geometry,
reflectance, expression and scene illumination per frame. To edit a video, the
user has to only edit the transcript, and an optimization strategy then chooses
segments of the input corpus as base material. The annotated parameters
corresponding to the selected segments are seamlessly stitched together and
used to produce an intermediate video representation in which the lower half of
the face is rendered with a parametric face model. Finally, a recurrent video
generation network transforms this representation to a photorealistic video
that matches the edited transcript. We demonstrate a large variety of edits,
such as the addition, removal, and alteration of words, as well as convincing
language translation and full sentence synthesis.