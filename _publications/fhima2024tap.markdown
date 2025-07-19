---
layout: publication
title: 'TAP-VL: Text Layout-aware Pre-training For Enriched Vision-language Models'
authors: Fhima et al.
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2024
bibkey: fhima2024tap
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.04642'}]
tags: [Training Techniques, Tools, CVPR, Evaluation, Transformer, Model Architecture,
  Fine Tuning, Multimodal Models, Datasets]
---
Vision-Language (VL) models have garnered considerable research interest;
however, they still face challenges in effectively handling text within images.
To address this limitation, researchers have developed two approaches. The
first method involves utilizing external Optical Character Recognition (OCR)
tools to extract textual information from images, which is then prepended to
other textual inputs. The second strategy focuses on employing extremely
high-resolution images to improve text recognition capabilities. In this paper,
we focus on enhancing the first strategy by introducing a novel method, named
TAP-VL, which treats OCR information as a distinct modality and seamlessly
integrates it into any VL model. TAP-VL employs a lightweight transformer-based
OCR module to receive OCR with layout information, compressing it into a short
fixed-length sequence for input into the LLM. Initially, we conduct
model-agnostic pretraining of the OCR module on unlabeled documents, followed
by its integration into any VL architecture through brief fine-tuning.
Extensive experiments demonstrate consistent performance improvements when
applying TAP-VL to top-performing VL models, across scene-text and
document-based VL benchmarks.