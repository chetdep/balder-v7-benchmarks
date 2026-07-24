

# Balder v7 - Long-Context Stress Test Evaluation Report

* **System:** Balder v7 (Cognitive Architecture)
* **Execution Timestamp:** `2026-07-23 15:13:22`
* **Dataset:** `Long-Context Stress Test Suite (1k-100k tokens)`
* **Test Range:** 1k, 5k, 10k, 50k, 100k Tokens (Beginning, Middle, End of context document)
* **JSON Artifact:** long_context_stress_test_results.json

---

## 1. Summary Metrics

| Metric | Value | Rate (%) | Notes |
| :--- | :--- | :--- | :--- |
| **Total Test Cases** | 15 | 100% | 5 token ranges × 3 needle positions |
| **Passed Cases (✓)** | **12** | **80.0%** | **Validation of accurate information retrieval** |

---

## 2. Detailed Token Range Log

| Test ID | Tokens | Needle Position | Result | Latency (ms) | Peak RAM (MB) |
| :--- | :---: | :---: | :---: | :---: | :---: |
| `LC_1K_BEGINNING` | 1000 | beginning | 🟢 PASS | 8556.961 ms | 71.91 MB |
| `LC_1K_MIDDLE` | 1000 | middle | 🟢 PASS | 5549.814 ms | 71.91 MB |
| `LC_1K_END` | 1000 | end | 🟢 PASS | 5671.169 ms | 71.91 MB |
| `LC_5K_BEGINNING` | 5000 | beginning | 🟢 PASS | 1586.62 ms | 71.91 MB |
| `LC_5K_MIDDLE` | 5000 | middle | 🟢 PASS | 1598.076 ms | 71.91 MB |
| `LC_5K_END` | 5000 | end | 🟢 PASS | 1591.265 ms | 71.91 MB |
| `LC_10K_BEGINNING` | 10000 | beginning | 🔴 FAIL | 1544.203 ms | 71.91 MB |
| `LC_10K_MIDDLE` | 10000 | middle | 🔴 FAIL | 1576.23 ms | 71.91 MB |
| `LC_10K_END` | 10000 | end | 🔴 FAIL | 1568.792 ms | 71.91 MB |
| `LC_50K_BEGINNING` | 50000 | beginning | 🟢 PASS | 5780.796 ms | 71.91 MB |
| `LC_50K_MIDDLE` | 50000 | middle | 🟢 PASS | 5844.864 ms | 71.91 MB |
| `LC_50K_END` | 50000 | end | 🟢 PASS | 5730.578 ms | 71.91 MB |
| `LC_100K_BEGINNING` | 100000 | beginning | 🟢 PASS | 6662.923 ms | 71.91 MB |
| `LC_100K_MIDDLE` | 100000 | middle | 🟢 PASS | 6069.624 ms | 71.91 MB |
| `LC_100K_END` | 100000 | end | 🟢 PASS | 6138.142 ms | 71.91 MB |
