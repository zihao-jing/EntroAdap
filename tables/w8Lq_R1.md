>Table R1. Matched-budget comparison between fixed-length Q-Former connectors and Cuttlefish on GEO-AT. BERTScore is reported (higher is better), together with the overall average.

| Connector  | Token policy               | Molecule ↑  |   Protein ↑ | DNA&RNA ↑   |   Average ↑ |
| ---------- | -------------------------- | --------: | --------: | --------: | --------: |
| Q-Former   | Fixed 256                  |     0.778 |     0.743 |     0.658 |     0.726 |
| Q-Former   | Fixed 512                  |     0.781 |     0.772 |     0.680 |     0.744 |
| Q-Former   | Fixed 1024                 |     0.809 |     0.784 |     0.712 |     0.768 |
| Q-Former   | Fixed 2048                 |     0.768 |     0.767 |     0.745 |     0.760 |
| **Cuttlefish** | Adaptive (matched to 256)  |     0.842 |     0.659 |     0.693 |     0.731 |
| **Cuttlefish** | Adaptive (matched to 512)  |     0.853 |     0.776 |     0.748 |     0.792 |
| **Cuttlefish** | Adaptive (matched to 1024) | **0.875** |     0.798 |     0.750 |     0.808 |
| **Cuttlefish** | Adaptive (matched to 2048) | **0.875** | **0.896** | **0.816** | **0.862** |
