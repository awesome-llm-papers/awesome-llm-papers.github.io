---
layout: publication
title: Diagonal Batching Unlocks Parallelism In Recurrent Memory Transformers For
  Long Contexts
authors: Danil Sivtsov, Ivan Rodkin, Gleb Kuzmin, Yuri Kuratov, Ivan Oseledets
conference: No Venue
year: 2025
bibkey: sivtsov2025diagonal
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.05229'}]
tags: ["Memory & Context", "Model Architecture"]
short_authors: Sivtsov et al.
---
Transformer models struggle with long-context inference due to their quadratic time and linear memory complexity. Recurrent Memory Transformers (RMTs) offer a solution by reducing the asymptotic cost to linear time and constant memory usage. However, their memory update mechanism leads to sequential execution, causing a performance bottleneck. We introduce Diagonal Batching, a scheduling scheme that unlocks parallelism across segments in RMTs while preserving exact recurrence. This approach eliminates the sequential constraint, enabling efficient GPU inference even for single long-context inputs without complex batching and pipelining techniques. Because the technique is purely a run-time computation reordering, existing RMT models adopt it with no retraining. Applied to a LLaMA-1B ARMT model, Diagonal Batching yields a 3.3x speedup over standard full-attention LLaMA-1B and a 1.8x speedup over the sequential RMT implementation on 131,072-token sequences. By removing sequential bottleneck, Diagonal Batching reduces inference cost and latency, thereby strengthening RMTs as a practical solution for real-world, long-context applications.

https://huggingface.co/discussions/paper/6842bc6955574a112d573421