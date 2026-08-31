--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-31 11:10:41.118286069 UTC |
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
| 1| 5834 | 10.38 | 3.29 | 0.51 |
| 2| 6035 | 12.72 | 4.03 | 0.55 |
| 3| 6239 | 14.84 | 4.71 | 0.58 |
| 5| 6640 | 18.88 | 5.97 | 0.64 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14279 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 43.86 | 12.56 | 0.63 |
| 4 | 228 | 858 | 52.19 | 14.94 | 0.72 |
| 5 | 282 | 969 | 60.86 | 17.41 | 0.81 |
| 6 | 339 | 1081 | 66.09 | 19.06 | 0.87 |
| 7 | 395 | 1192 | 75.50 | 21.84 | 0.97 |
| 8 | 451 | 1303 | 87.54 | 25.08 | 1.10 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.29 | 7.69 | 0.48 |
| 2| 1943 | 25.39 | 8.68 | 0.50 |
| 3| 2105 | 27.94 | 10.05 | 0.54 |
| 5| 2391 | 30.89 | 12.21 | 0.59 |
| 10| 3157 | 41.53 | 18.50 | 0.76 |
| 37| 7367 | 94.92 | 51.39 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.84 | 7.38 | 0.42 |
| 2| 847 | 25.45 | 8.78 | 0.46 |
| 3| 1013 | 27.73 | 10.09 | 0.49 |
| 5| 1189 | 29.22 | 11.82 | 0.52 |
| 10| 1985 | 38.70 | 17.79 | 0.68 |
| 43| 6789 | 98.83 | 56.50 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 27.54 | 8.47 | 0.46 |
| 2| 780 | 30.91 | 10.06 | 0.51 |
| 3| 1046 | 31.57 | 10.95 | 0.53 |
| 5| 1270 | 35.01 | 13.24 | 0.58 |
| 10| 2001 | 47.59 | 20.08 | 0.77 |
| 36| 5995 | 97.75 | 51.54 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.87 | 10.16 | 0.53 |
| 2| 765 | 35.17 | 11.17 | 0.55 |
| 3| 941 | 37.91 | 12.62 | 0.59 |
| 5| 1251 | 42.68 | 15.29 | 0.66 |
| 10| 2087 | 54.92 | 22.06 | 0.84 |
| 29| 4891 | 99.46 | 47.13 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5808 | 27.08 | 9.09 | 0.69 |
| 2| 5912 | 36.04 | 12.09 | 0.79 |
| 3| 6049 | 43.83 | 14.70 | 0.88 |
| 4| 6103 | 49.08 | 16.43 | 0.93 |
| 5| 6421 | 61.13 | 20.62 | 1.08 |
| 6| 6497 | 71.69 | 24.11 | 1.19 |
| 7| 6665 | 82.72 | 27.88 | 1.31 |
| 8| 7002 | 95.21 | 32.17 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 30 | 1708 | 6854 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2218 | 7158 | 99.12 | 37.95 | 1.54 |

