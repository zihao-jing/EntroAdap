| Variant                                         | Molecule | Protein | DNA   | RNA   | Average |
|-------------------------------------------------|----------|---------|-------|-------|---------|
| Base LLM (no tuning)                            | 0.778    | 0.742   | 0.658 | 0.646 | 0.706   |
| Sequence-only fine-tuning                       | 0.752    | 0.820   | 0.710 | 0.698 | 0.745   |
| Structure-trained, structure removed at inference | 0.867  | 0.788   | 0.730 | 0.860 | 0.811   |
| Full Cuttlefish (structure available at inference) | 0.875 | 0.896   | 0.816 | 0.868 | 0.864   |