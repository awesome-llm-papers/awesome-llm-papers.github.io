---
layout: publication
title: 'EMMA: End-to-end Multimodal Model For Autonomous Driving'
authors: Hwang et al.
conference: IEEE Transactions on Intelligent Transportation Systems
year: 2024
bibkey: hwang2024emma
citations: 164
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.23262'}]
tags: [Training Techniques, Prompting, Model Architecture, Reinforcement Learning,
  Applications, Multimodal Models, Datasets]
---
We introduce EMMA, an End-to-end Multimodal Model for Autonomous driving.
Built on a multi-modal large language model foundation, EMMA directly maps raw
camera sensor data into various driving-specific outputs, including planner
trajectories, perception objects, and road graph elements. EMMA maximizes the
utility of world knowledge from the pre-trained large language models, by
representing all non-sensor inputs (e.g. navigation instructions and ego
vehicle status) and outputs (e.g. trajectories and 3D locations) as natural
language text. This approach allows EMMA to jointly process various driving
tasks in a unified language space, and generate the outputs for each task using
task-specific prompts. Empirically, we demonstrate EMMA's effectiveness by
achieving state-of-the-art performance in motion planning on nuScenes as well
as competitive results on the Waymo Open Motion Dataset (WOMD). EMMA also
yields competitive results for camera-primary 3D object detection on the Waymo
Open Dataset (WOD). We show that co-training EMMA with planner trajectories,
object detection, and road graph tasks yields improvements across all three
domains, highlighting EMMA's potential as a generalist model for autonomous
driving applications. However, EMMA also exhibits certain limitations: it can
process only a small amount of image frames, does not incorporate accurate 3D
sensing modalities like LiDAR or radar and is computationally expensive. We
hope that our results will inspire further research to mitigate these issues
and to further evolve the state of the art in autonomous driving model
architectures.