---
layout: publication
title: A Read-write Memory Network For Movie Story Understanding
authors: Seil Na, Sangho Lee, Jisung Kim, Gunhee Kim
conference: 2017 IEEE International Conference on Computer Vision (ICCV)
year: 2017
bibkey: na2017read
citations: 95
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1709.09345'}]
tags: ["ICCV"]
short_authors: Na et al.
---
We propose a novel memory network model named Read-Write Memory Network
(RWMN) to perform question and answering tasks for large-scale, multimodal
movie story understanding. The key focus of our RWMN model is to design the
read network and the write network that consist of multiple convolutional
layers, which enable memory read and write operations to have high capacity and
flexibility. While existing memory-augmented network models treat each memory
slot as an independent block, our use of multi-layered CNNs allows the model to
read and write sequential memory cells as chunks, which is more reasonable to
represent a sequential story because adjacent memory blocks often have strong
correlations. For evaluation, we apply our model to all the six tasks of the
MovieQA benchmark, and achieve the best accuracies on several tasks, especially
on the visual QA task. Our model shows a potential to better understand not
only the content in the story, but also more abstract information, such as
relationships between characters and the reasons for their actions.