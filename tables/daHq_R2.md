> Table R2. Results on the reasoning-oriented benchmarks ChemIQ and MolecularIQ. Non-reasoning and reasoning backbones are compared before and after adding Cuttlefish, and relative gains are reported for each benchmark. Metrics are success rate and accuracy for ChemIQ and MolecularIQ, respectively.

| Backbone                      | Type          | ChemIQ Base↑ | ChemIQ + Cuttlefish↑ | Gain       | MolecularIQ Base↑ | MolecularIQ + Cuttlefish↑ | Gain       |
| ----------------------------- | ------------- | ----------- | ------------------- | ---------- | ---------------- | ------------------------ | ---------- |
| Qwen-2.5-7B-Instruct          | Non-reasoning | 0.051       | 0.055               | 7.84%      | 0.101            | 0.105                    | 3.96%      |
| Llama-3.1-8B-Instruct         | Non-reasoning | 0.077       | 0.081               | 5.19%      | 0.077            | 0.081                    | 5.19%      |
| Qwen3-8B                      | Reasoning     | 0.066       | 0.091               | **37.88%** | 0.155            | 0.188                    | 21.29%     |
| DeepSeek-R1-D-Qwen-7B         | Reasoning     | **0.232**   | **0.312**           | 34.48%     | **0.234**        | **0.277**                | 18.38%     |
| Mistral-3-8B-Reasoning-2512   | Reasoning     | 0.112       | 0.134               | 19.64%     | 0.123            | 0.163                    | **32.52%** |
| **Avg. Gain (non-reasoning)** |               |             |                     | **6.50%**  |                  |                          | **4.58%**  |
| **Average gain (reasoning)**  |               |             |                     | **30.67%** |                  |                          | **24.06%** |


