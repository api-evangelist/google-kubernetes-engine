---
title: "Run real-time and async inference on the same infrastructure with GKE Inference Gateway"
url: "https://cloud.google.com/blog/products/containers-kubernetes/unifying-real-time-and-async-inference-with-gke-inference-gateway/"
date: "2026-04-01"
author: "Poonam Lamba"
feed_url: "https://cloudblog.withgoogle.com/products/containers-kubernetes/rss/"
---
As AI workloads transition from experimental prototypes to production-grade services, the infrastructure supporting them faces a growing utilization gap. Enterprises today typically face a binary choice: build for high-concurrency, low-latency real-time requests, or optimize for high-throughput, "async" processing. In Kubernetes environments, these requirements are traditionally handled by separate, siloed GPU and TPU accelerator clusters.
