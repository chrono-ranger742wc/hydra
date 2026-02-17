--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-17 05:57:43.085246546 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7647 | 29.12 | 9.18 | 0.79 |
| 43| 14279 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 43.71 | 12.51 | 0.63 |
| 4 | 227 | 858 | 48.28 | 14.01 | 0.68 |
| 5 | 282 | 969 | 56.39 | 16.32 | 0.77 |
| 6 | 339 | 1081 | 73.44 | 20.78 | 0.94 |
| 7 | 395 | 1192 | 80.77 | 23.01 | 1.02 |
| 8 | 449 | 1303 | 91.65 | 26.01 | 1.14 |
| 9 | 505 | 1414 | 96.96 | 27.64 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1824 | 24.37 | 7.71 | 0.48 |
| 2| 1990 | 26.38 | 8.96 | 0.52 |
| 3| 2110 | 28.09 | 10.09 | 0.54 |
| 5| 2385 | 31.42 | 12.34 | 0.60 |
| 10| 3079 | 39.68 | 17.99 | 0.74 |
| 38| 7235 | 93.24 | 51.50 | 1.59 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 665 | 22.81 | 7.38 | 0.42 |
| 2| 832 | 25.33 | 8.74 | 0.45 |
| 3| 955 | 27.06 | 9.88 | 0.48 |
| 5| 1170 | 28.66 | 11.67 | 0.52 |
| 10| 1900 | 37.12 | 17.35 | 0.66 |
| 40| 6465 | 96.19 | 53.76 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 29.17 | 8.91 | 0.48 |
| 2| 842 | 29.26 | 9.62 | 0.49 |
| 3| 999 | 31.58 | 10.95 | 0.53 |
| 5| 1315 | 35.31 | 13.33 | 0.59 |
| 10| 1993 | 46.73 | 19.83 | 0.76 |
| 36| 6157 | 99.83 | 52.20 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.87 | 10.16 | 0.53 |
| 2| 812 | 35.89 | 11.39 | 0.56 |
| 3| 942 | 37.91 | 12.62 | 0.59 |
| 5| 1265 | 42.53 | 15.25 | 0.66 |
| 10| 2062 | 54.14 | 21.83 | 0.84 |
| 28| 4737 | 96.85 | 45.72 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5815 | 27.16 | 9.12 | 0.69 |
| 2| 5950 | 36.04 | 12.13 | 0.79 |
| 3| 6059 | 41.16 | 13.78 | 0.85 |
| 4| 6324 | 55.13 | 18.54 | 1.01 |
| 5| 6433 | 64.01 | 21.56 | 1.11 |
| 6| 6553 | 72.97 | 24.52 | 1.20 |
| 7| 6579 | 76.18 | 25.56 | 1.24 |
| 8| 7015 | 94.80 | 31.98 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1138 | 6512 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2219 | 7159 | 98.93 | 37.88 | 1.54 |

