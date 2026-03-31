> Table R8. Sensitivity analysis of the anchor-selection hyperparameters on GEO-AT. The table varies the mass threshold ρ and maximum anchor count Kmax in Scaling-Aware Patching, and reports BERTScore (larger is better) on molecule, protein, and DNA&RNA tasks, together with the overall average.

| Knob              | Setting         | Molecule  | Protein   | DNA&RNA   | Average   |
|-------------------|-----------------|-----------|-----------|-----------|-----------|
| Mass threshold ρ  | 0.05            | 0.850     | 0.805     | 0.782     | 0.812     |
| Mass threshold ρ  | 0.10 (default)  | 0.875     | 0.896     | 0.836     | 0.869     |
| Mass threshold ρ  | 0.2             | 0.826     | 0.918     | 0.780     | 0.841     |
| Mass threshold ρ  | 0.3             | 0.852     | 0.903     | 0.763     | 0.839     |
| Kmax              | 256             | 0.820     | 0.903     | 0.734     | 0.819     |
| Kmax              | 512             | 0.824     | **0.929** | 0.710     | 0.821     |
| Kmax              | 1024            | 0.773     | 0.878     | 0.752     | 0.801     |
| Kmax              | 2048 (default)  | 0.875     | 0.896     | 0.836     | 0.869     |
| Kmax              | 4096            | **0.915** | 0.871     | **0.866** | **0.884** |
