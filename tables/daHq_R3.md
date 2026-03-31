> Table R3. Prompt-setting ablation on GEO-AT using the same reasoning-capable backbones under non-reasoning and reasoning inference settings. Results are reported as average METEOR and BERTScore (higher is better), together with the relative improvements brought by Cuttlefish under each prompt setting.

| Backbone                    | Prompt setting    | Backbone Avg. METEOR↑ | Backbone Avg. BERT-S↑ | Backbone+Cuttlefish (Ours) Avg. METEOR↑ | Backbone+Cuttlefish (Ours) Avg. BERT-S↑ | Improvement (ΔMETEOR / ΔBERT-S) |
| --------------------------- | ----------------- | -------------------: | -------------------: | ---------------------: | ---------------------: | ------------------------------: |
| Qwen3-8B                    | Non-reasoning     |                0.051 |                0.634 |                  0.055 |                  0.689 |                   7.84% / 8.68% |
| Qwen3-8B                    | Reasoning         |                0.107 |                0.674 |              **0.428** |              **0.876** |                300.00% / 29.97% |
| DeepSeek-R1-D-Qwen-7B       | Non-reasoning     |                0.201 |                0.649 |                  0.321 |                  0.703 |                  59.70% / 8.32% |
| DeepSeek-R1-D-Qwen-7B       | Reasoning         |            **0.227** |                0.662 |                  0.369 |                  0.803 |                 62.56% / 21.30% |
| Mistral-3-8B-Reasoning-2512 | Non-reasoning     |                0.113 |                0.687 |                  0.298 |                  0.703 |                 163.72% / 2.33% |
| Mistral-3-8B-Reasoning-2512 | Reasoning         |                0.176 |            **0.744** |                  0.335 |                  0.776 |                  90.34% / 4.30% |
| **Average gain**            | **Non-reasoning** |                      |                      |                        |                        |              **77.09% / 6.44%** |
| **Average gain**            | **Reasoning**     |                      |                      |                        |                        |            **150.97% / 18.52%** |
