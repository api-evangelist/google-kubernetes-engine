---
title: "Accelerate model downloads on GKE with NVIDIA Run:ai Model Streamer"
url: "https://cloud.google.com/blog/products/containers-kubernetes/nvidia-runai-model-streamer-supports-cloud-storage/"
date: "2025-12-04"
author: "Peter Schuurman"
feed_url: "https://cloudblog.withgoogle.com/products/containers-kubernetes/rss/"
---
As large language models (LLMs) continue to grow in size and complexity, the time it takes to load them from storage to accelerator memory for inference can become a significant bottleneck. This "cold start" problem isn't just a minor delay — it's a critical barrier to building resilient, scalable, and cost-effective AI services. Every minute spent loading a model is a minute a GPU is sitting idle, a minute your service is delayed from scaling to meet demand, and a minute a user request is waiting.
