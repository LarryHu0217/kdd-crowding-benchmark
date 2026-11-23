# Institutional portfolio crowding benchmark

Replication artifact for *A Point-in-Time Benchmark for Forecasting Institutional Portfolio Crowding* by Liang Hu. It evaluates next-quarter changes in peer overlap from public Form 13F and Form N-PORT holdings disclosures.

[Version v1.0.0](https://github.com/LarryHu0217/kdd-crowding-benchmark/releases/tag/v1.0.0) · [Reviewer ZIP](https://github.com/LarryHu0217/kdd-crowding-benchmark/releases/download/v1.0.0/kdd-crowding-reviewer-20261123-b01e30d6ba77.zip) · [SHA-256](https://github.com/LarryHu0217/kdd-crowding-benchmark/releases/download/v1.0.0/kdd-crowding-reviewer-20261123-b01e30d6ba77.zip.sha256)

## Quick start

Extract the ZIP and run these commands from its `kdd-crowding-replication` directory. Use Python 3.11 or later.

```sh
python3 -s research/check_reviewer_examples.py
```

The two examples check matched NDCG, originally issued gain, and observed coverage using one historical top-500 cohort per panel. The archive README explains how to verify the checksums, replay the historical results, and rebuild the panels from public sources.

Project-authored code is available under MIT. Project-authored documentation and outputs are available under CC BY 4.0. The ZIP includes the full project license texts and a notice listing the pinned upstream sources and their terms.
