--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-18 06:05:54.046042497 UTC |
| _Max. memory units_ | 14000000 |
| _Max. CPU units_ | 10000000000 |
| _Max. tx size (kB)_ | 16384 |

## Script summary

| Name   | Hash | Size (Bytes) 
| :----- | :--- | -----------: 
| νInitial | c8a101a5c8ac4816b0dceb59ce31fc2258e387de828f02961d2f2045 | 2652 | 
| νCommit | 61458bc2f297fff3cc5df6ac7ab57cefd87763b0b7bd722146a1035c | 685 | 
| νHead | a1442faf26d4ec409e2f62a685c1d4893f8d6bcbaf7bcb59d6fa1340 | 14599 | 
| μHead | fd173b993e12103cd734ca6710d364e17120a5eb37a224c64ab2b188* | 5284 | 
| νDeposit | ae01dade3a9c346d5c93ae3ce339412b90a0b8f83f94ec6baa24e30c | 1102 | 

* The minting policy hash is only usable for comparison. As the script is parameterized, the actual script is unique per head.

## `Init` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5840 | 10.40 | 3.30 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.69 | 4.65 | 0.58 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 171 | 747 | 41.39 | 11.95 | 0.60 |
| 4 | 224 | 858 | 50.36 | 14.48 | 0.70 |
| 5 | 283 | 969 | 60.65 | 17.33 | 0.81 |
| 6 | 340 | 1081 | 64.06 | 18.61 | 0.85 |
| 7 | 394 | 1192 | 81.05 | 23.12 | 1.02 |
| 8 | 451 | 1303 | 91.86 | 26.16 | 1.14 |
| 9 | 504 | 1414 | 94.33 | 27.12 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.29 | 7.69 | 0.48 |
| 2| 1933 | 25.84 | 8.78 | 0.51 |
| 3| 2123 | 28.42 | 10.17 | 0.55 |
| 5| 2363 | 31.53 | 12.37 | 0.60 |
| 10| 3187 | 42.72 | 18.83 | 0.77 |
| 38| 7357 | 94.06 | 51.77 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.53 | 7.30 | 0.41 |
| 2| 847 | 25.49 | 8.79 | 0.46 |
| 3| 1021 | 28.33 | 10.23 | 0.50 |
| 5| 1198 | 29.97 | 12.04 | 0.53 |
| 10| 2053 | 39.80 | 18.10 | 0.69 |
| 44| 6833 | 99.58 | 57.39 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 29.13 | 8.90 | 0.48 |
| 2| 827 | 29.15 | 9.59 | 0.49 |
| 3| 868 | 31.97 | 11.00 | 0.53 |
| 5| 1277 | 37.81 | 14.01 | 0.61 |
| 10| 1929 | 45.79 | 19.55 | 0.75 |
| 37| 6064 | 98.73 | 52.46 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.83 | 10.16 | 0.53 |
| 2| 827 | 35.92 | 11.40 | 0.56 |
| 3| 958 | 37.95 | 12.63 | 0.59 |
| 5| 1207 | 41.86 | 15.04 | 0.65 |
| 10| 2211 | 56.27 | 22.47 | 0.86 |
| 29| 4790 | 97.03 | 46.41 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5829 | 27.05 | 9.07 | 0.69 |
| 2| 6030 | 36.76 | 12.41 | 0.80 |
| 3| 6072 | 44.57 | 15.00 | 0.89 |
| 4| 6275 | 54.81 | 18.47 | 1.00 |
| 5| 6584 | 66.89 | 22.64 | 1.14 |
| 6| 6351 | 65.40 | 21.86 | 1.12 |
| 7| 6858 | 85.98 | 29.04 | 1.36 |
| 8| 6868 | 93.85 | 31.61 | 1.44 |
| 9| 7036 | 98.90 | 33.38 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 570 | 6175 | 40.58 | 14.82 | 0.86 |
| 10 | 30 | 1707 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2160 | 7122 | 96.00 | 36.77 | 1.50 |

