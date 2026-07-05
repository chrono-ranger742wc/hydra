--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-05 07:58:40.539984086 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.50 | 5.83 | 0.63 |
| 10| 7646 | 28.80 | 9.07 | 0.78 |
| 43| 14279 | 99.08 | 30.97 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 556 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 42.62 | 12.24 | 0.62 |
| 4 | 225 | 858 | 48.97 | 14.17 | 0.69 |
| 5 | 281 | 969 | 59.50 | 17.09 | 0.80 |
| 6 | 337 | 1081 | 64.17 | 18.60 | 0.85 |
| 7 | 395 | 1192 | 74.32 | 21.42 | 0.96 |
| 8 | 451 | 1303 | 85.65 | 24.63 | 1.08 |
| 9 | 507 | 1414 | 96.29 | 27.53 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1807 | 24.29 | 7.69 | 0.48 |
| 2| 1879 | 24.77 | 8.48 | 0.49 |
| 3| 2068 | 27.33 | 9.89 | 0.53 |
| 5| 2389 | 31.52 | 12.37 | 0.60 |
| 10| 3308 | 44.33 | 19.28 | 0.79 |
| 40| 7569 | 96.81 | 53.87 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 22.84 | 7.39 | 0.41 |
| 2| 765 | 24.05 | 8.39 | 0.44 |
| 3| 969 | 26.84 | 9.84 | 0.48 |
| 5| 1296 | 30.03 | 12.04 | 0.54 |
| 10| 2041 | 40.88 | 18.42 | 0.70 |
| 39| 6309 | 97.43 | 53.39 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 27.50 | 8.46 | 0.46 |
| 2| 812 | 29.18 | 9.60 | 0.49 |
| 3| 967 | 33.47 | 11.46 | 0.55 |
| 5| 1299 | 35.76 | 13.47 | 0.59 |
| 10| 2037 | 47.41 | 20.03 | 0.77 |
| 37| 6179 | 99.59 | 52.77 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.83 | 10.15 | 0.53 |
| 2| 768 | 35.21 | 11.18 | 0.55 |
| 3| 980 | 38.66 | 12.84 | 0.60 |
| 5| 1246 | 42.64 | 15.28 | 0.66 |
| 10| 2058 | 54.84 | 22.04 | 0.84 |
| 29| 4715 | 95.60 | 45.99 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5783 | 27.09 | 9.08 | 0.69 |
| 2| 6018 | 36.93 | 12.44 | 0.80 |
| 3| 6111 | 44.85 | 15.07 | 0.89 |
| 4| 6270 | 55.10 | 18.57 | 1.01 |
| 5| 6337 | 62.33 | 20.86 | 1.08 |
| 6| 6683 | 76.34 | 25.79 | 1.25 |
| 7| 6658 | 79.56 | 26.76 | 1.28 |
| 8| 6820 | 88.61 | 29.75 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1138 | 6512 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2220 | 7159 | 98.49 | 37.73 | 1.53 |

