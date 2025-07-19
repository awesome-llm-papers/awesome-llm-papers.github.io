---
layout: publication
title: Test-time Alignment For Tracking User Interest Shifts In Sequential Recommendation
authors: Zhang et al.
conference: Proceedings of the ACM Web Conference 2023
year: 2025
bibkey: zhang2025test
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.01489'}]
tags: [RAG, Training Techniques, Evaluation, Reinforcement Learning, Datasets]
---
Sequential recommendation is essential in modern recommender systems, aiming
to predict the next item a user may interact with based on their historical
behaviors. However, real-world scenarios are often dynamic and subject to
shifts in user interests. Conventional sequential recommendation models are
typically trained on static historical data, limiting their ability to adapt to
such shifts and resulting in significant performance degradation during
testing. Recently, Test-Time Training (TTT) has emerged as a promising
paradigm, enabling pre-trained models to dynamically adapt to test data by
leveraging unlabeled examples during testing. However, applying TTT to
effectively track and address user interest shifts in recommender systems
remains an open and challenging problem. Key challenges include how to capture
temporal information effectively and explicitly identifying shifts in user
interests during the testing phase. To address these issues, we propose
T\\(^2\\)ARec, a novel model leveraging state space model for TTT by introducing
two Test-Time Alignment modules tailored for sequential recommendation,
effectively capturing the distribution shifts in user interest patterns over
time. Specifically, T\\(^2\\)ARec aligns absolute time intervals with
model-adaptive learning intervals to capture temporal dynamics and introduce an
interest state alignment mechanism to effectively and explicitly identify the
user interest shifts with theoretical guarantees. These two alignment modules
enable efficient and incremental updates to model parameters in a
self-supervised manner during testing, enhancing predictions for online
recommendation. Extensive evaluations on three benchmark datasets demonstrate
that T\\(^2\\)ARec achieves state-of-the-art performance and robustly mitigates the
challenges posed by user interest shifts.