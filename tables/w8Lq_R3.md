> Table R3. Hallucination evaluation on GEO-AT across three failure modes. For both settings, hallucination rate (HR) and answer rate (AR) are reported.

**Molecule**

| Model       | Func.-group HR↓ | Func.-group AR↑ | Mech.-expl. HR↓ | Mech.-expl. AR↑ | Long-range HR↓ | Long-range AR↑ | Avg. HR↓ | Avg. AR↑ |
|-------------|------------------|------------------|------------------|------------------|----------------|----------------|----------|----------|
| Mol-LLaMA   | 0.12             | 0.94             | 0.23             | 0.98             | 0.19           | **1.00**       | 0.18     | 0.97     |
| 3D-MoLM     | 0.23             | 0.83             | 0.72             | 0.95             | 0.32           | 0.81           | 0.42     | 0.86     |
| Cuttlefish  | **0.07**         | **0.99**         | **0.13**         | **0.99**         | **0.16**       | **1.00**       | **0.12** | **0.99** |

**Protein**

| Model        | Func.-group HR↓ | Func.-group AR↑ | Mech.-expl. HR↓ | Mech.-expl. AR↑ | Long-range HR↓ | Long-range AR↑ | Avg. HR↓ | Avg. AR↑ |
|--------------|------------------|------------------|------------------|------------------|----------------|----------------|----------|----------|
| ProtChatGPT  | 0.10             | 0.94             | 0.20             | 0.96             | 0.24           | **1.00**       | 0.18     | 0.97     |
| Prot2Chat    | 0.06             | 0.95             | 0.71             | 0.89             | 0.33           | 0.76           | 0.37     | 0.86     |
| Cuttlefish   | **0.04**         | **0.97**         | **0.16**         | **0.98**         | **0.20**       | 0.98           | **0.13** | **0.98** |
