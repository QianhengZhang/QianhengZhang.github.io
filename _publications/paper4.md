---
title: "AutoSDT: Scaling Data-Driven Discovery Tasks Toward Open Co-Scientists"
collection: publications
category: conferences
permalink: /publication/2025-06-09-autosdt
excerpt: "We present AutoSDT, an automatic pipeline for collecting high-quality coding tasks in real-world data-driven scientific discovery workflows. AutoSDT-5K, the resulting dataset, contains 5,404 coding tasks across four scientific disciplines and 756 unique Python packages, enabling the training of LLM-based co-scientists. Models trained on AutoSDT-5K, dubbed AutoSDT-Coder, achieve state-of-the-art results on ScienceAgentBench and DiscoveryBench, closing the gap with proprietary models."
date: 2025-11-04
venue: 'EMNLP 2025'
paperurl: 'https://arxiv.org/pdf/2506.08140.pdf'
authors:
  - Yifei Li
  - Hanane Nour Moussa
  - Ziru Chen
  - Shijie Chen
  - Botao Yu
  - Mingyi Xue
  - Benjamin Burns
  - Tzu-Yao Chiu
  - Vishal Dey
  - Zitong Lu
  - Chen Wei
  - Qianheng Zhang
  - Tianyu Zhang
  - Song Gao
  - Xuhui Huang
  - Xia Ning
  - Nesreen K Ahmed
  - Ali Payani
  - Huan Sun

---

**Authors:**
Yifei Li, Hanane Nour Moussa, Ziru Chen, Shijie Chen, Botao Yu, Mingyi Xue, Benjamin Burns, Tzu-Yao Chiu, Vishal Dey, Zitong Lu, Chen Wei, Qianheng Zhang, Tianyu Zhang, Song Gao, Xuhui Huang, Xia Ning, Nesreen K Ahmed, Ali Payani, Huan Sun

**Publication date:** 2025/6/9
**Journal:** arXiv preprint arXiv:2506.08140
**PDF:** [Available from arXiv](https://arxiv.org/pdf/2506.08140.pdf)

**Description:**
Despite long-standing efforts in accelerating scientific discovery with AI, building AI co-scientists remains challenging due to limited high-quality data for training and evaluation. To tackle this data scarcity issue, we present AutoSDT, an automatic pipeline that collects high-quality coding tasks in real-world data-driven discovery workflows. AutoSDT leverages the coding capabilities and parametric knowledge of LLMs to search for diverse sources, select ecologically valid tasks, and synthesize accurate task instructions and code solutions. Using our pipeline, we construct AutoSDT-5K, a dataset of 5,404 coding tasks for data-driven discovery that covers four scientific disciplines and 756 unique Python packages. To the best of our knowledge, AutoSDT-5K is the only automatically collected and the largest open dataset for data-driven scientific discovery. Expert feedback on a subset of 256 tasks shows the effectiveness of AutoSDT: 93% of the collected tasks are ecologically valid, and 92.2% of the synthesized programs are functionally correct. Trained on AutoSDT-5K, the Qwen2.5-Coder-Instruct LLM series, dubbed AutoSDT-Coder, show substantial improvement on two challenging data-driven discovery benchmarks, ScienceAgentBench and DiscoveryBench. Most notably, AutoSDT-Coder-32B reaches the same level of performance as GPT-4o on ScienceAgentBench with a success rate of 7.8%, doubling the performance of its base model. On DiscoveryBench, it lifts the hypothesis matching score to 8.1, bringing a 17.4% relative improvement and closing the gap between open-weight models and GPT-4o.

