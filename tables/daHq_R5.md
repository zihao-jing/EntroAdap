>Table R5. Backbone-size ablation on GEO-AT using the Qwen-2.5 family. Results are reported by modality with BERTScore (higher is better) used as the evaluation metric.

| Model Size | Molecule ↑| Protein ↑| DNA&RNA ↑| Average ↑|
| ---------- | -------: | ------: | ------: | ------: |
| 0.5B       |    0.453 |   0.422 |   0.382 |   0.419 |
| 1.5B       |    0.586 |   0.577 |   0.544 |   0.569 |
| 3B         |    0.608 |   0.578 |   0.621 |   0.602 |
| 7B         |    0.863 |   0.816 |   0.832 |   0.840 |
| 14B        |    0.897 |   0.861 |   0.834 |   0.864 |
| 32B        | **0.903** | **0.877** | **0.840** | **0.873** |