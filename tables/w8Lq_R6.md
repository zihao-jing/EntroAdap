> Table R6. Coordinate-noise robustness analysis on the GEO-AT protein tasks. Isotropic Gaussian noise with different standard deviations is added to the input coordinates, and ROUGE-L is reported for protein function (PF), functional description (FD), catalytic activity (CA), and domain or motif prediction (DM), together with the average.

| Coordinate noise (std. in Å) | PF ↑   | FD ↑   | CA ↑   | DM ↑   | Average |
| ---------------------------- | ----- | ----- | ----- | ----- | ------- |
| 0                            | 0.486     | **0.520** | **0.551** | 0.495     | **0.513** |
| 0.25                         | 0.523     | 0.475     | 0.521     | **0.517** | 0.509     |
| 0.5                          | **0.526** | 0.418     | 0.475     | 0.452     | 0.468     |
| 1                            | 0.460 | 0.438 | 0.477 | 0.405 | 0.445   |
| 2                            | 0.443 | 0.396 | 0.422 | 0.432 | 0.423   |


