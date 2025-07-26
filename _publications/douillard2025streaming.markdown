---
layout: publication
title: 'Streaming Diloco With Overlapping Communication: Towards A Distributed Free
  Lunch'
authors: "Arthur Douillard, Yanislav Donchev, Keith Rush, Satyen Kale, Zachary Charles,\
  \ Zachary Garrett, Gabriel Teston, Dave Lacey, Ross Mcilroy, Jiajun Shen, Alexandre\
  \ Ram\xE9, Arthur Szlam, Marc'aurelio Ranzato, Paul Barham"
conference: No Venue
year: 2025
bibkey: douillard2025streaming
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2501.18512'}]
tags: ["Training Techniques"]
short_authors: Douillard et al.
---
Training of large language models (LLMs) is typically distributed across a large number of accelerators to reduce training time. Since internal states and parameter gradients need to be exchanged at each and every single gradient step, all devices need to be co-located using low-latency high-bandwidth communication links to support the required high volume of exchanged bits. Recently, distributed algorithms like DiLoCo have relaxed such co-location constraint: accelerators can be grouped into ``workers'', where synchronizations between workers only occur infrequently. This in turn means that workers can afford being connected by lower bandwidth communication links without affecting learning quality. However, in these methods, communication across workers still requires the same peak bandwidth as before, as the synchronizations require all parameters to be exchanged across all workers. In this paper, we improve DiLoCo in three ways. First, we synchronize only subsets of parameters in sequence, rather than all at once, which greatly reduces peak bandwidth. Second, we allow workers to continue training while synchronizing, which decreases wall clock time. Third, we quantize the data exchanged by workers, which further reduces bandwidth across workers. By properly combining these modifications, we show experimentally that we can distribute training of billion-scale parameters and reach similar quality as before, but reducing required bandwidth by two orders of magnitude.

https://huggingface.co/discussions/paper/679ca01fcad2402cec0a9404