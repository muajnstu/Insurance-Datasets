##  Feature Subset Abbreviations
- **D_MI** → Dataset derived from applying **Mutual Information** feature selection technique  
- **D_SFS** → Dataset derived from applying **Sequential Feature Selection** technique  
- **D_RFE** → Dataset derived from applying **Recursive Feature Elimination (RFE)** technique  
- **D_PI** → Dataset derived from applying **Permutation Importance** technique 

---

## Transformation Methods  
- **MinMax** → MinMaxScaler applied (values scaled between 0 and 1)  
- **ZScore** → StandardScaler applied (mean = 0, variance = 1)  
- **Log** → Log transformation applied (reduces skewness, stabilizes variance)

---

## File Naming Convention
Each file follows the format:

D-<FeatureSubset>-<Transformation>

---

## Dataset Index

| File Name        | Short Note |
|------------------|------------|
| **D_MI**         | Dataset derived from applying **Mutual Information** feature selection technique |
| **D_SFS**        | Dataset derived from applying **Sequential Feature Selection** technique |
| **D_RFE**        | Dataset derived from applying **Recursive Feature Elimination (RFE)** technique |
| **D_PI**         | Dataset derived from applying **Permutation Importance** technique |
| **D_MI_MinMax**  | Mutual Information subset scaled using **MinMaxScaler** (values between 0 and 1) |
| **D_SFS_MinMax** | Sequential Feature Selection subset scaled using **MinMaxScaler** |
| **D_RFE_MinMax** | Recursive Feature Elimination subset scaled using **MinMaxScaler** |
| **D_PI_MinMax**  | Permutation Importance subset scaled using **MinMaxScaler** |
| **D_MI_ZScore**  | Mutual Information subset scaled using **StandardScaler** (mean = 0, variance = 1) |
| **D_SFS_ZScore** | Sequential Feature Selection subset scaled using **StandardScaler** |
| **D_RFE_ZScore** | Recursive Feature Elimination subset scaled using **StandardScaler** |
| **D_PI_ZScore**  | Permutation Importance subset scaled using **StandardScaler** |
| **D_MI_Log**     | Mutual Information subset transformed using **LogScaler** (reduces skewness) |
| **D_SFS_Log**    | Sequential Feature Selection subset transformed using **LogScaler** |
| **D_RFE_Log**    | Recursive Feature Elimination subset transformed using **LogScaler** |
| **D_PI_Log**     | Permutation Importance subset transformed using **LogScaler** |
| **D_ZScore**     | Entire dataset scaled using **StandardScaler** |
| **D_MinMax**     | Entire dataset scaled using **MinMaxScaler** |
| **D_Log**        | Entire dataset transformed using **LogScaler** |

---

This README ensures reviewers can **map abbreviations to their meaning** and understand the transformations applied.

