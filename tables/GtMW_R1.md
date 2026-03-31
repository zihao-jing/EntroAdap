> Table R1. Same-backbone comparison on GEO-AT using Llama-3.1-8B-Instruct. METEOR and BERTScore are reported (larger is better) by modality and as overall averages.

**METEOR↑**

| Method                     | Backbone              |  Molecule |   Protein |       DNA |       RNA |   Average |
| -------------------------- | --------------------- | --------: | --------: | --------: | --------: | --------: |
| Backbone Only              | Llama-3.1-8B-Instruct |     0.229 |     0.178 |     0.175 |     0.175 |   0.18925 |
| Mol-Instructions connector | Llama-3.1-8B-Instruct |     0.291 |     0.315 |     0.364 |     0.330 |     0.325 |
| Mol-LLaMA connector        | Llama-3.1-8B-Instruct |     0.319 |     0.328 |     0.381 |     0.306 |     0.334 |
| **Cuttlefish**             | Llama-3.1-8B-Instruct | **0.391** | **0.417** | **0.529** | **0.403** | **0.435** |



**BERTScore↑**


| Method                     | Backbone              |  Molecule |   Protein |       DNA |       RNA |   Average |
| -------------------------- | --------------------- | --------: | --------: | --------: | --------: | --------: |
| Backbone Only              | Llama-3.1-8B-Instruct |     0.778 |     0.742 |     0.658 |     0.646 |     0.706 |
| Mol-Instructions connector | Llama-3.1-8B-Instruct |     0.789 |     0.789 |     0.786 |     0.738 |     0.775 |
| Mol-LLaMA connector        | Llama-3.1-8B-Instruct |     0.830 |     0.758 |     0.754 |     0.731 |     0.768 |
| **Cuttlefish**             | Llama-3.1-8B-Instruct | **0.875** | **0.896** | **0.816** | **0.868** | **0.864** |
