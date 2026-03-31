> Table R2. Structural token-usage comparison by entity size on GEO-AT. Variants include sequence-only, fixed-token Q-Former, sequence-exposed structural-token, and Cuttlefish, reporting the atom-count range and the corresponding structural token-usage range for each method.


| Model                  | Token policy                       | Atom-count range | Token-usage range |
| ---------------------- | ---------------------------------- | ---------------- | ----------------- |
| Sequence-only baseline | No structural tokens               | [1, 256)         | 0                 |
| Q-Former variant       | Fixed                              | [1, 256)         | 256               |
| Q-Former variant       | Fixed                              | [256, 1K)        | 256               |
| Q-Former variant       | Fixed                              | [1K, 8K)         | 256               |
| Q-Former variant       | Fixed                              | [8K, 30K)        | 256               |
| ChatNT-style baseline  | Sequence-exposed structural tokens | [1, 256)         | (0,75)            |
| ChatNT-style baseline  | Sequence-exposed structural tokens | [256, 1K)        | [75, 250)         |
| ChatNT-style baseline  | Sequence-exposed structural tokens | [1K, 8K)         | [250, 2000)       |
| ChatNT-style baseline  | Sequence-exposed structural tokens | [8K, 30K)        | [2000, 7500)      |
| **Cuttlefish**         | Adaptive                           | [1, 256)         | (0, 17)           |
| **Cuttlefish**         | Adaptive                           | [256, 1K)        | [18, 85)          |
| **Cuttlefish**         | Adaptive                           | [1K, 8K)         | [86, 816)         |
| **Cuttlefish**         | Adaptive                           | [8K, 30K)        | [217, 2116)       |


