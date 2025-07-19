---
layout: publication
title: 'NEAT: Neural Attention Fields For End-to-end Autonomous Driving'
authors: Chitta Kashyap, Prakash Aditya, Geiger Andreas
conference: 2021 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2021
bibkey: chitta2021neat
citations: 129
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.04456'}]
tags: [Interpretability And Explainability, ICCV, Training Techniques, Attention Mechanism,
  Evaluation, Model Architecture, Reinforcement Learning]
---
Efficient reasoning about the semantic, spatial, and temporal structure of a
scene is a crucial prerequisite for autonomous driving. We present NEural
ATtention fields (NEAT), a novel representation that enables such reasoning for
end-to-end imitation learning models. NEAT is a continuous function which maps
locations in Bird's Eye View (BEV) scene coordinates to waypoints and
semantics, using intermediate attention maps to iteratively compress
high-dimensional 2D image features into a compact representation. This allows
our model to selectively attend to relevant regions in the input while ignoring
information irrelevant to the driving task, effectively associating the images
with the BEV representation. In a new evaluation setting involving adverse
environmental conditions and challenging scenarios, NEAT outperforms several
strong baselines and achieves driving scores on par with the privileged CARLA
expert used to generate its training data. Furthermore, visualizing the
attention maps for models with NEAT intermediate representations provides
improved interpretability.