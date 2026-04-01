--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-01 06:19:08.148988938 UTC |
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
| 1| 5841 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6638 | 18.84 | 5.95 | 0.64 |
| 10| 7644 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 99.32 | 31.06 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.24 | 7.32 | 0.43 |
| 2 | 112 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 171 | 747 | 43.74 | 12.55 | 0.63 |
| 4 | 225 | 858 | 48.33 | 14.07 | 0.68 |
| 5 | 285 | 969 | 62.14 | 17.69 | 0.82 |
| 6 | 338 | 1081 | 73.87 | 20.96 | 0.95 |
| 7 | 395 | 1196 | 84.49 | 23.86 | 1.06 |
| 8 | 450 | 1303 | 90.79 | 25.80 | 1.13 |
| 9 | 506 | 1414 | 97.78 | 28.01 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1812 | 23.92 | 7.60 | 0.48 |
| 2| 1981 | 26.76 | 9.04 | 0.52 |
| 3| 2086 | 26.98 | 9.78 | 0.53 |
| 5| 2394 | 31.11 | 12.27 | 0.60 |
| 10| 3047 | 38.67 | 17.71 | 0.72 |
| 40| 7542 | 95.19 | 53.44 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.81 | 7.37 | 0.42 |
| 2| 767 | 24.00 | 8.38 | 0.44 |
| 3| 857 | 23.99 | 9.01 | 0.45 |
| 5| 1094 | 27.11 | 11.21 | 0.50 |
| 10| 2001 | 38.88 | 17.85 | 0.68 |
| 40| 6558 | 97.38 | 54.13 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 27.54 | 8.47 | 0.46 |
| 2| 775 | 28.47 | 9.38 | 0.48 |
| 3| 907 | 30.26 | 10.55 | 0.51 |
| 5| 1210 | 34.22 | 13.01 | 0.57 |
| 10| 1996 | 44.37 | 19.20 | 0.74 |
| 34| 5553 | 98.17 | 50.22 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 33.83 | 10.15 | 0.53 |
| 2| 769 | 35.14 | 11.16 | 0.55 |
| 3| 1005 | 38.59 | 12.82 | 0.60 |
| 5| 1344 | 43.43 | 15.51 | 0.67 |
| 10| 2183 | 56.00 | 22.41 | 0.86 |
| 29| 5027 | 99.40 | 47.17 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 27.00 | 9.07 | 0.69 |
| 2| 5992 | 36.92 | 12.44 | 0.80 |
| 3| 6069 | 45.03 | 15.14 | 0.89 |
| 4| 6400 | 57.30 | 19.41 | 1.03 |
| 5| 6359 | 62.51 | 21.01 | 1.09 |
| 6| 6640 | 75.90 | 25.70 | 1.24 |
| 7| 6752 | 80.71 | 27.17 | 1.30 |
| 8| 6701 | 87.22 | 29.27 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 571 | 6175 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1705 | 6851 | 79.15 | 30.16 | 1.31 |
| 10 | 40 | 2277 | 7193 | 99.66 | 38.24 | 1.55 |
| 10 | 40 | 2277 | 7193 | 99.84 | 38.30 | 1.55 |

