---
title: "Accelerate GKE cluster autoscaling with faster concurrent node pool auto-creation"
url: "https://cloud.google.com/blog/products/containers-kubernetes/faster-gke-node-pool-auto-creation/"
date: "2026-01-28"
author: "Daniel Kłobuszewski"
feed_url: "https://cloudblog.withgoogle.com/products/containers-kubernetes/rss/"
---
We're excited to announce concurrency in Google Kubernetes Engine (GKE) node pool auto-creation, to significantly reduce provisioning latency and autoscaling performance. Internal benchmarks show up to an 85% improvement in provisioning speed, especially benefiting heterogeneous workloads, multi-tenant clusters, workloads that use multiple ComputeClass priorities, and large AI training workloads, by cutting deployment time and enhancing goodput. The improvements are already under the hood when you allow GKE to automatically create node pools for pending Pods .
