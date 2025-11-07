--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-07 05:33:37.106077072 UTC |
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
| 1| 5836 | 10.59 | 3.36 | 0.52 |
| 2| 6035 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7651 | 28.88 | 9.10 | 0.79 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 169 | 747 | 39.93 | 11.62 | 0.59 |
| 4 | 227 | 858 | 49.34 | 14.24 | 0.69 |
| 5 | 284 | 969 | 61.06 | 17.52 | 0.81 |
| 6 | 341 | 1085 | 70.91 | 20.17 | 0.92 |
| 7 | 396 | 1196 | 72.61 | 21.06 | 0.94 |
| 8 | 451 | 1303 | 92.27 | 26.22 | 1.14 |
| 9 | 505 | 1414 | 95.99 | 27.45 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1790 | 24.00 | 7.62 | 0.48 |
| 2| 1948 | 25.84 | 8.78 | 0.51 |
| 3| 2163 | 29.01 | 10.35 | 0.55 |
| 5| 2338 | 30.04 | 11.97 | 0.58 |
| 10| 3358 | 44.83 | 19.42 | 0.80 |
| 41| 7754 | 98.98 | 55.13 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.57 | 7.31 | 0.41 |
| 2| 808 | 25.20 | 8.72 | 0.45 |
| 3| 964 | 26.06 | 9.59 | 0.47 |
| 5| 1216 | 30.12 | 12.08 | 0.53 |
| 10| 1909 | 37.74 | 17.52 | 0.67 |
| 41| 6702 | 99.07 | 55.27 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 27.54 | 8.47 | 0.46 |
| 2| 836 | 31.62 | 10.28 | 0.52 |
| 3| 954 | 30.87 | 10.74 | 0.52 |
| 5| 1210 | 34.29 | 13.02 | 0.57 |
| 10| 1947 | 43.59 | 18.96 | 0.72 |
| 35| 5638 | 93.47 | 49.59 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.15 | 9.95 | 0.52 |
| 2| 815 | 35.92 | 11.40 | 0.56 |
| 3| 1096 | 39.14 | 13.00 | 0.61 |
| 5| 1272 | 42.64 | 15.28 | 0.66 |
| 10| 2035 | 54.29 | 21.86 | 0.84 |
| 29| 5015 | 99.79 | 47.23 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 23.01 | 7.58 | 0.64 |
| 2| 5970 | 35.96 | 12.08 | 0.79 |
| 3| 6121 | 44.79 | 15.06 | 0.89 |
| 4| 6199 | 51.27 | 17.20 | 0.96 |
| 5| 6407 | 63.27 | 21.29 | 1.10 |
| 6| 6722 | 75.10 | 25.35 | 1.24 |
| 7| 6748 | 84.03 | 28.27 | 1.33 |
| 8| 6974 | 94.49 | 31.86 | 1.45 |
| 9| 6925 | 95.89 | 32.20 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 56 | 5867 | 20.52 | 6.98 | 0.62 |
| 10 | 5 | 284 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1139 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 39 | 2222 | 7162 | 99.38 | 38.04 | 1.54 |

