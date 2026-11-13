---
title: "CoT Faithfulness Audit for Health LLMs"
order: 1
status: "PhD Research · CHIL 2027 (In Prep)"
period: "2024 – Present"
institution: "Northeastern University · Robust Systems Lab"
tags:
  - "Python"
  - "PyTorch"
  - "vLLM"
  - "Hugging Face"
  - "NNSight"
  - "MLflow"
  - "SLURM (HPC)"
---

Engineered a reproducible multi-GPU evaluation pipeline (sharded SLURM array jobs, checkpoint merging, version-pinned environments) benchmarking **10 open-weight LLMs (2B–27B)** across 4 numeric health prediction tasks from wearable data. Adapted chain-of-thought faithfulness interventions (input shifts, reasoning corruption, planted conclusions) with positive controls—discovering that reasoning predicts response direction only **~6/10 times** (vs. **9/10** on a known-rule control) and exposing a critical evaluation tooling fault.
