---
layout: publication
title: 'Motionclip: Exposing Human Motion Generation To CLIP Space'
authors: Guy Tevet, Brian Gordon, Amir Hertz, Amit H. Bermano, Daniel Cohen-or
conference: Lecture Notes in Computer Science
year: 2022
bibkey: tevet2022motionclip
citations: 155
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.08063'}]
tags: ["Model Architecture"]
short_authors: Tevet et al.
---
We introduce MotionCLIP, a 3D human motion auto-encoder featuring a latent
embedding that is disentangled, well behaved, and supports highly semantic
textual descriptions. MotionCLIP gains its unique power by aligning its latent
space with that of the Contrastive Language-Image Pre-training (CLIP) model.
Aligning the human motion manifold to CLIP space implicitly infuses the
extremely rich semantic knowledge of CLIP into the manifold. In particular, it
helps continuity by placing semantically similar motions close to one another,
and disentanglement, which is inherited from the CLIP-space structure.
MotionCLIP comprises a transformer-based motion auto-encoder, trained to
reconstruct motion while being aligned to its text label's position in
CLIP-space. We further leverage CLIP's unique visual understanding and inject
an even stronger signal through aligning motion to rendered frames in a
self-supervised manner. We show that although CLIP has never seen the motion
domain, MotionCLIP offers unprecedented text-to-motion abilities, allowing
out-of-domain actions, disentangled editing, and abstract language
specification. For example, the text prompt "couch" is decoded into a sitting
down motion, due to lingual similarity, and the prompt "Spiderman" results in a
web-swinging-like solution that is far from seen during training. In addition,
we show how the introduced latent space can be leveraged for motion
interpolation, editing and recognition.