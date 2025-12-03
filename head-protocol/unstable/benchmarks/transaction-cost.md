--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-03 05:35:24.258048293 UTC |
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
| 1| 5836 | 10.66 | 3.39 | 0.52 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6643 | 19.02 | 6.02 | 0.64 |
| 10| 7644 | 29.23 | 9.22 | 0.79 |
| 43| 14286 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2181 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 169 | 747 | 43.64 | 12.50 | 0.63 |
| 4 | 227 | 862 | 52.26 | 14.93 | 0.72 |
| 5 | 283 | 969 | 56.31 | 16.38 | 0.77 |
| 6 | 339 | 1081 | 75.41 | 21.29 | 0.96 |
| 7 | 393 | 1192 | 76.38 | 22.00 | 0.98 |
| 8 | 451 | 1303 | 89.71 | 25.55 | 1.12 |
| 9 | 506 | 1414 | 99.27 | 28.35 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 1942 | 25.43 | 8.68 | 0.50 |
| 3| 2017 | 26.24 | 9.56 | 0.52 |
| 5| 2340 | 29.97 | 11.95 | 0.58 |
| 10| 3142 | 40.75 | 18.29 | 0.75 |
| 38| 7330 | 93.84 | 51.73 | 1.60 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 640 | 22.57 | 7.32 | 0.41 |
| 2| 696 | 22.62 | 7.96 | 0.42 |
| 3| 834 | 24.06 | 9.04 | 0.45 |
| 5| 1208 | 29.12 | 11.78 | 0.52 |
| 10| 1905 | 38.51 | 17.75 | 0.67 |
| 40| 6549 | 97.21 | 54.08 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 703 | 27.54 | 8.47 | 0.46 |
| 2| 798 | 30.95 | 10.07 | 0.51 |
| 3| 942 | 32.68 | 11.22 | 0.54 |
| 5| 1308 | 35.72 | 13.46 | 0.59 |
| 10| 1873 | 46.13 | 19.64 | 0.75 |
| 38| 6055 | 98.66 | 53.07 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.83 | 10.15 | 0.53 |
| 2| 867 | 36.56 | 11.60 | 0.57 |
| 3| 999 | 38.63 | 12.83 | 0.60 |
| 5| 1166 | 41.26 | 14.85 | 0.64 |
| 10| 1859 | 51.89 | 21.15 | 0.80 |
| 29| 4796 | 97.28 | 46.49 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 27.13 | 9.09 | 0.69 |
| 2| 5957 | 35.88 | 12.04 | 0.79 |
| 3| 6022 | 43.96 | 14.71 | 0.88 |
| 4| 6390 | 56.80 | 19.23 | 1.03 |
| 5| 6519 | 65.24 | 22.04 | 1.12 |
| 6| 6446 | 68.19 | 22.87 | 1.15 |
| 7| 6784 | 85.19 | 28.73 | 1.34 |
| 8| 7040 | 94.71 | 31.99 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 10 | 570 | 6174 | 40.83 | 14.90 | 0.86 |
| 10 | 30 | 1707 | 6853 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2220 | 7159 | 98.05 | 37.58 | 1.53 |

