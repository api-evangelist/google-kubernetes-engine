---
title: "Guardrails at the gateway: Securing AI inference on GKE with Model Armor"
url: "https://cloud.google.com/blog/products/identity-security/securing-ai-inference-on-gke-with-model-armor/"
date: "2026-04-09"
author: "Sunny Song"
feed_url: "https://cloudblog.withgoogle.com/products/containers-kubernetes/rss/"
---
Enterprises are rapidly moving AI workloads from experimentation to production on Google Kubernetes Engine (GKE), using its scalability to serve powerful inference endpoints. However, as these models handle increasingly sensitive data, they introduce unique AI-driven attack vectors — from prompt injection to sensitive data leakage — that traditional firewalls aren't designed to catch. Prompt injection remains a critical attack vector , so it’s not enough to hope that the model will simply refuse to act on the prompt.
