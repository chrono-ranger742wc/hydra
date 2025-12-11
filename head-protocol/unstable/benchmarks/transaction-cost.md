--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-11 05:44:51.627062387 UTC |
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
| 1| 5834 | 10.59 | 3.36 | 0.52 |
| 2| 6039 | 12.23 | 3.86 | 0.54 |
| 3| 6236 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 19.10 | 6.05 | 0.64 |
| 10| 7647 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 99.02 | 30.95 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 170 | 747 | 42.53 | 12.22 | 0.61 |
| 4 | 226 | 858 | 53.39 | 15.21 | 0.73 |
| 5 | 282 | 969 | 56.19 | 16.32 | 0.76 |
| 6 | 339 | 1081 | 73.92 | 21.01 | 0.95 |
| 7 | 396 | 1192 | 76.82 | 22.07 | 0.98 |
| 8 | 449 | 1303 | 91.27 | 25.92 | 1.13 |
| 9 | 507 | 1414 | 98.92 | 28.16 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1816 | 24.29 | 7.69 | 0.48 |
| 2| 1971 | 26.92 | 9.08 | 0.52 |
| 3| 2106 | 28.39 | 10.16 | 0.55 |
| 5| 2415 | 32.60 | 12.67 | 0.61 |
| 10| 3268 | 43.02 | 18.92 | 0.78 |
| 42| 7746 | 96.41 | 55.12 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 22.81 | 7.37 | 0.42 |
| 2| 836 | 25.53 | 8.79 | 0.46 |
| 3| 970 | 26.61 | 9.78 | 0.48 |
| 5| 1231 | 30.74 | 12.27 | 0.54 |
| 10| 2075 | 39.70 | 18.07 | 0.69 |
| 42| 6649 | 97.01 | 55.36 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.50 | 8.46 | 0.46 |
| 2| 816 | 29.18 | 9.60 | 0.49 |
| 3| 1019 | 31.57 | 10.95 | 0.53 |
| 5| 1204 | 36.35 | 13.57 | 0.59 |
| 10| 1972 | 44.19 | 19.15 | 0.73 |
| 36| 6064 | 97.97 | 51.65 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 845 | 36.60 | 11.61 | 0.57 |
| 3| 996 | 38.55 | 12.81 | 0.60 |
| 5| 1251 | 42.72 | 15.30 | 0.66 |
| 10| 1999 | 54.13 | 21.83 | 0.83 |
| 29| 4996 | 98.99 | 47.03 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5791 | 27.13 | 9.09 | 0.69 |
| 2| 5973 | 35.83 | 12.03 | 0.79 |
| 3| 6024 | 41.29 | 13.82 | 0.85 |
| 4| 6223 | 53.81 | 18.07 | 0.99 |
| 5| 6386 | 63.16 | 21.22 | 1.09 |
| 6| 6512 | 73.41 | 24.73 | 1.21 |
| 7| 6732 | 79.91 | 26.89 | 1.29 |
| 8| 6884 | 92.50 | 31.16 | 1.43 |
| 9| 6984 | 99.02 | 33.34 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 56 | 5867 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2220 | 7159 | 97.79 | 37.50 | 1.53 |

