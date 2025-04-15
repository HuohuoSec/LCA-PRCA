# LCA-PRCA: Lowest Common Ancestor Embedding for Provenance-Based Intrusion Detection

[![License](https://v01canotypora.oss-cn-hangzhou.aliyuncs.com/img/license-MIT-blue.svg)](LICENSE)
[![Python Version](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)

Official implementation of the paper: 
**"LCA-PRCA: Lowest Common Ancestor Embedding for Provenance-Based Intrusion Detection"** 

---

## 📌 Overview
Advanced Persistent Threats (APTs) have emerged as one of the most challenging security issues due to their stealthy nature, sophisticated techniques, and use of zero-day exploits. While provenance graph analysis has shown promise in APT detection, current methods suffer from three critical limitations: (1) loss of contextual information in graph embeddings, (2) insensitivity to processes with minimal malicious behavior, and (3) lack of automated root cause analysis. To address these challenges, we propose \textbf{LCA-PRCA}, a novel root cause-preserving detection framework that precomputes the lowest common ancestor (LCA) for all process nodes—where the LCA represents the root node—and embeds this root node information directly into the provenance graph. By connecting each process to its root node, LCA-PRCA preserves long-range contextual relationships, enhancing sensitivity to subtle anomalies and enabling automated root cause analysis. This approach significantly improves the detection of APTs by linking malicious activities to their origins, even for processes with minimal deviations from normal behavior.We evaluate LCA-PRCA on the \textit{DARPA OPTC} dataset across three attack scenarios: \textit{Plain PowerShell Empire}, \textit{Custom PowerShell Empire}, and \textit{Malicious Upgrade}. Results show that LCA-PRCA achieves higher true positive rates (TPR) and lower false positive rates (FPR) compared to state-of-the-art methods, demonstrating its effectiveness in precise APT detection and efficient root cause analysis.

Key Features:

- ✅ LCA-based graph embedding for provenance graphs
- ✅ Root Cause Analysis
- ✅ Benchmark results on DARPA  OPTC datasets
