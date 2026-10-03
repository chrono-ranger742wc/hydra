--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-03 10:14:07.215899341 UTC |
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
| 1| 5834 | 10.48 | 3.33 | 0.52 |
| 2| 6038 | 12.53 | 3.97 | 0.55 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6638 | 18.50 | 5.83 | 0.63 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 40.02 | 11.62 | 0.59 |
| 4 | 226 | 858 | 52.62 | 15.07 | 0.72 |
| 5 | 284 | 969 | 61.52 | 17.67 | 0.82 |
| 6 | 337 | 1081 | 66.74 | 19.29 | 0.88 |
| 7 | 393 | 1192 | 77.40 | 22.15 | 0.99 |
| 8 | 449 | 1303 | 94.21 | 26.63 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.37 | 7.71 | 0.48 |
| 2| 1924 | 25.88 | 8.79 | 0.51 |
| 3| 2107 | 28.23 | 10.12 | 0.54 |
| 5| 2375 | 31.15 | 12.28 | 0.60 |
| 10| 3179 | 40.92 | 18.35 | 0.75 |
| 40| 7695 | 98.59 | 54.39 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 653 | 22.54 | 7.31 | 0.41 |
| 2| 769 | 23.51 | 8.21 | 0.43 |
| 3| 861 | 24.07 | 9.03 | 0.45 |
| 5| 1162 | 27.97 | 11.46 | 0.51 |
| 10| 2001 | 39.95 | 18.15 | 0.69 |
| 42| 6563 | 97.48 | 55.47 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 597 | 28.46 | 8.69 | 0.47 |
| 2| 801 | 30.87 | 10.05 | 0.51 |
| 3| 998 | 31.61 | 10.96 | 0.53 |
| 5| 1237 | 37.10 | 13.79 | 0.60 |
| 10| 2045 | 44.78 | 19.34 | 0.74 |
| 37| 6092 | 99.65 | 52.71 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.87 | 10.16 | 0.53 |
| 2| 865 | 36.60 | 11.61 | 0.57 |
| 3| 1066 | 39.34 | 13.05 | 0.61 |
| 5| 1309 | 43.24 | 15.46 | 0.67 |
| 10| 2024 | 54.17 | 21.83 | 0.83 |
| 28| 4622 | 94.46 | 45.01 | 1.44 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5843 | 27.08 | 9.09 | 0.69 |
| 2| 5824 | 31.45 | 10.45 | 0.74 |
| 3| 6218 | 46.58 | 15.76 | 0.91 |
| 4| 6378 | 55.73 | 18.85 | 1.02 |
| 5| 6448 | 64.32 | 21.73 | 1.11 |
| 6| 6650 | 72.24 | 24.36 | 1.20 |
| 7| 6813 | 84.62 | 28.49 | 1.34 |
| 8| 6817 | 86.65 | 29.13 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1140 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2218 | 7157 | 98.05 | 37.58 | 1.53 |

