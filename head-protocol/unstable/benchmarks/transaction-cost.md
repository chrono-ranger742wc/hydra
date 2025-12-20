--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-20 05:37:22.642197708 UTC |
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
| 1| 5834 | 10.28 | 3.25 | 0.51 |
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6243 | 14.67 | 4.64 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14279 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 560 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2181 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 169 | 747 | 43.57 | 12.47 | 0.63 |
| 4 | 225 | 858 | 53.82 | 15.31 | 0.73 |
| 5 | 283 | 969 | 63.95 | 18.15 | 0.84 |
| 6 | 339 | 1085 | 69.18 | 19.83 | 0.90 |
| 7 | 395 | 1192 | 86.45 | 24.33 | 1.08 |
| 8 | 449 | 1303 | 89.43 | 25.48 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1819 | 24.29 | 7.69 | 0.48 |
| 2| 1942 | 25.39 | 8.68 | 0.50 |
| 3| 2114 | 28.35 | 10.15 | 0.55 |
| 5| 2389 | 31.38 | 12.33 | 0.60 |
| 10| 3084 | 40.15 | 18.11 | 0.74 |
| 40| 7698 | 99.98 | 54.78 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 613 | 22.53 | 7.30 | 0.41 |
| 2| 845 | 25.39 | 8.78 | 0.46 |
| 3| 909 | 25.07 | 9.31 | 0.46 |
| 5| 1138 | 28.11 | 11.49 | 0.51 |
| 10| 1958 | 39.30 | 18.00 | 0.68 |
| 40| 6223 | 91.52 | 52.50 | 1.54 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 702 | 27.47 | 8.46 | 0.46 |
| 2| 847 | 31.62 | 10.28 | 0.52 |
| 3| 918 | 32.72 | 11.23 | 0.54 |
| 5| 1294 | 35.08 | 13.26 | 0.59 |
| 10| 2100 | 48.90 | 20.48 | 0.79 |
| 37| 6105 | 99.72 | 52.73 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 662 | 33.83 | 10.16 | 0.53 |
| 2| 840 | 35.85 | 11.38 | 0.56 |
| 3| 1025 | 38.59 | 12.82 | 0.60 |
| 5| 1306 | 43.36 | 15.49 | 0.67 |
| 10| 2069 | 54.84 | 22.06 | 0.84 |
| 29| 4923 | 97.99 | 46.71 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5832 | 26.96 | 9.06 | 0.69 |
| 2| 5902 | 34.91 | 11.70 | 0.78 |
| 3| 6097 | 44.69 | 15.03 | 0.89 |
| 4| 6346 | 56.12 | 18.94 | 1.02 |
| 5| 6471 | 64.76 | 21.86 | 1.12 |
| 6| 6830 | 77.50 | 26.26 | 1.27 |
| 7| 6820 | 84.55 | 28.53 | 1.34 |
| 8| 6933 | 91.35 | 30.80 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 10 | 569 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 40 | 2277 | 7193 | 99.66 | 38.24 | 1.55 |

