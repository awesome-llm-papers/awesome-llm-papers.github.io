---
layout: publication
title: Vision-based Navigation With Language-based Assistance Via Imitation Learning
  With Indirect Intervention
authors: Khanh Nguyen, Debadeepta Dey, Chris Brockett, Bill Dolan
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2019
bibkey: nguyen2018vision
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1812.04155'}]
tags: ["CVPR", "Has Code", "Tools"]
short_authors: Nguyen et al.
---
We present Vision-based Navigation with Language-based Assistance (VNLA), a
grounded vision-language task where an agent with visual perception is guided
via language to find objects in photorealistic indoor environments. The task
emulates a real-world scenario in that (a) the requester may not know how to
navigate to the target objects and thus makes requests by only specifying
high-level end-goals, and (b) the agent is capable of sensing when it is lost
and querying an advisor, who is more qualified at the task, to obtain language
subgoals to make progress. To model language-based assistance, we develop a
general framework termed Imitation Learning with Indirect Intervention (I3L),
and propose a solution that is effective on the VNLA task. Empirical results
show that this approach significantly improves the success rate of the learning
agent over other baselines in both seen and unseen environments. Our code and
data are publicly available at https://github.com/debadeepta/vnla .