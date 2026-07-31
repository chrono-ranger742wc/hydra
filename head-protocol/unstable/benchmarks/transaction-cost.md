--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-31 07:15:47.465478833 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 28.90 | 9.10 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10095 | 98.61 | 68.52 | 1.89 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 171 | 747 | 40.17 | 11.66 | 0.59 |
| 4 | 227 | 858 | 53.84 | 15.34 | 0.73 |
| 5 | 282 | 969 | 62.56 | 17.82 | 0.83 |
| 6 | 339 | 1081 | 76.10 | 21.57 | 0.97 |
| 7 | 393 | 1192 | 72.44 | 20.97 | 0.94 |
| 8 | 448 | 1307 | 86.39 | 24.70 | 1.08 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.29 | 7.69 | 0.48 |
| 2| 1976 | 27.00 | 9.10 | 0.52 |
| 3| 2017 | 26.24 | 9.56 | 0.52 |
| 5| 2476 | 32.91 | 12.78 | 0.62 |
| 10| 3297 | 42.45 | 18.76 | 0.77 |
| 41| 7665 | 98.27 | 54.93 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 22.77 | 7.37 | 0.42 |
| 2| 784 | 23.59 | 8.23 | 0.43 |
| 3| 977 | 27.04 | 9.88 | 0.48 |
| 5| 1186 | 29.03 | 11.76 | 0.52 |
| 10| 1974 | 38.61 | 17.78 | 0.68 |
| 42| 6548 | 94.90 | 54.79 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 27.51 | 8.47 | 0.46 |
| 2| 820 | 29.18 | 9.60 | 0.49 |
| 3| 971 | 30.94 | 10.75 | 0.52 |
| 5| 1264 | 37.85 | 14.02 | 0.61 |
| 10| 2176 | 49.49 | 20.69 | 0.80 |
| 36| 6119 | 98.10 | 51.69 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.12 | 9.94 | 0.52 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 900 | 37.13 | 12.38 | 0.58 |
| 5| 1221 | 41.90 | 15.05 | 0.65 |
| 10| 2127 | 55.55 | 22.26 | 0.85 |
| 29| 4939 | 97.98 | 46.72 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.09 | 9.09 | 0.69 |
| 2| 5916 | 34.90 | 11.68 | 0.78 |
| 3| 5974 | 40.28 | 13.44 | 0.84 |
| 4| 6338 | 56.97 | 19.28 | 1.03 |
| 5| 6315 | 60.69 | 20.37 | 1.07 |
| 6| 6462 | 68.75 | 23.14 | 1.16 |
| 7| 6744 | 83.13 | 28.00 | 1.32 |
| 8| 6756 | 89.15 | 29.92 | 1.38 |
| 9| 6822 | 93.18 | 31.38 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 56 | 5867 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6174 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1136 | 6510 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1710 | 6857 | 81.11 | 30.83 | 1.33 |
| 10 | 40 | 2278 | 7195 | 99.66 | 38.24 | 1.55 |
| 10 | 40 | 2279 | 7196 | 99.66 | 38.24 | 1.55 |

