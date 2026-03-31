
> Table R1. Comparison between Cuttlefish and general LLM backbones on GEO-AT under reasoning and non-reasoning settings. Results are reported as average METEOR and BERTScore over the GEO-AT evaluation tasks, with the corresponding absolute improvements over the baseline backbone.

| Backbone                    | Reasoning | Backbone Avg. METEOR↑ | Backbone Avg. BERT-S↑ | Backbone+Cuttlefish Avg. METEOR↑ | Backbone+Cuttlefish Avg. BERT-S↑ | Improvement (ΔMETEOR / ΔBERT-S) |
| --------------------------- | --------- | -------------------- | -------------------- | ---------------------- | ---------------------- | ------------------------------- |
| Qwen-2.5-7B-Instruct        | No        | 0.143                | 0.653                | 0.330                  | 0.840                  | +0.187 / +0.187                 |
| Mistral-3-8B-Instruct-2512  | No        | 0.172                | 0.683                | 0.310                  | 0.750                  | +0.138 / +0.067                 |
| GLM-4-9B-0414               | No        | 0.155                | 0.621                | 0.367                  | 0.727                  | +0.212 / +0.106                 |
| Qwen3-8B                    | **Yes**   | 0.107                | 0.674                | **0.428**              | **0.876**              | +0.321 / +0.202                 |
| DeepSeek-R1-D-Qwen-7B       | **Yes**   | 0.169                | 0.692                | 0.369                  | 0.803                  | +0.200 / +0.111                 |
| Mistral-3-8B-Reasoning-2512 | **Yes**   | **0.176**            | **0.744**            | 0.335                  | **0.876**              | +0.159 / +0.132                 |


