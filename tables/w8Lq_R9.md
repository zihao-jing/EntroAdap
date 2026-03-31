> Table R9. Sensitivity analysis of soft patch growth and adapter-side hyperparameters on GEO-AT. BERTScore (higher is better) on four tasks is reported, together with the overall average.

| Knob                        | Setting         | Molecule ↑| Protein ↑ | DNA&RNA ↑  | Average ↑|
|-----------------------------|-----------------|-----------|-----------|-----------|-----------|
| Assignment temperature τ    | 0.05            | 0.843     | **0.915** | 0.827     | 0.862     |
| Assignment temperature τ    | 0.10 (default)  | 0.875     | 0.896     | 0.836     | **0.869** |
| Assignment temperature τ    | 0.2             | **0.897** | 0.869     | 0.830     | 0.865     |
| Assignment distance scale s | 0.5             | 0.845     | 0.828     | **0.873** | 0.849     |
| Assignment distance scale s | 1.0 (default)   | 0.875     | 0.896     | 0.836     | **0.869** |
| Assignment distance scale s | 2               | 0.817     | 0.881     | 0.846     | 0.848     |
| Fusion blocks Lf            | 4               | **0.897** | 0.862     | 0.827     | 0.862     |
| Fusion blocks Lf            | 8 (default)     | 0.875     | 0.896     | 0.836     | **0.869** |
| Fusion blocks Lf            | 12              | 0.887     | 0.818     | 0.820     | 0.842     |
