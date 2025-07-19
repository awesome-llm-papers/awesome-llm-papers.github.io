---
layout: publication
title: Scene-text Grounding For Text-based Video Question Answering
authors: Zhou et al.
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2024
bibkey: zhou2024scene
citations: 176
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.14319'}]
tags: [RAG, ICCV, Evaluation, Datasets]
---
Existing efforts in text-based video question answering (TextVideoQA) are criticized for their opaque decisionmaking and heavy reliance on scene-text recognition. In this paper, we propose to study Grounded TextVideoQA by forcing models to answer questions and spatio-temporally localize the relevant scene-text regions, thus decoupling QA from scenetext recognition and promoting research towards interpretable QA. The task has three-fold significance. First, it encourages scene-text evidence versus other short-cuts for answer predictions. Second, it directly accepts scene-text regions as visual answers, thus circumventing the problem of ineffective answer evaluation by stringent string matching. Third, it isolates the challenges inherited in VideoQA and scene-text recognition. This enables the diagnosis of the root causes for failure predictions, e.g., wrong QA or wrong scene-text recognition? To achieve Grounded TextVideoQA, we propose the T2S-QA model that highlights a disentangled temporal-to-spatial contrastive learning strategy for weakly-supervised scene-text grounding and grounded TextVideoQA. To facilitate evaluation, we construct a new dataset ViTXT-GQA which features 52K scene-text bounding boxes within 2.2K temporal segments related to 2K questions and 729 videos. With ViTXT-GQA, we perform extensive experiments and demonstrate the severe limitations of existing techniques in Grounded TextVideoQA. While T2S-QA achieves superior results, the large performance gap with human leaves ample space for improvement. Our further analysis of oracle scene-text inputs posits that the major challenge is scene-text recognition. To advance the research of Grounded TextVideoQA, our dataset and code are at https://github.com/zhousheng97/ViTXT-GQA.git