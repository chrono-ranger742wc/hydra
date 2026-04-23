--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-23 06:29:40.482595923 UTC |
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
| 1| 5836 | 10.85 | 3.45 | 0.52 |
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 28.80 | 9.07 | 0.78 |
| 43| 14279 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 170 | 747 | 42.77 | 12.32 | 0.62 |
| 4 | 225 | 858 | 48.31 | 14.01 | 0.68 |
| 5 | 284 | 969 | 60.22 | 17.23 | 0.80 |
| 6 | 339 | 1081 | 69.95 | 20.02 | 0.91 |
| 7 | 395 | 1192 | 86.10 | 24.24 | 1.07 |
| 8 | 448 | 1303 | 81.38 | 23.66 | 1.04 |
| 9 | 506 | 1414 | 91.49 | 26.43 | 1.14 |
| 10 | 561 | 1529 | 99.16 | 28.81 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1816 | 23.92 | 7.60 | 0.48 |
| 2| 1938 | 25.84 | 8.78 | 0.51 |
| 3| 2059 | 26.87 | 9.75 | 0.53 |
| 5| 2334 | 30.33 | 12.04 | 0.58 |
| 10| 3371 | 44.94 | 19.47 | 0.80 |
| 40| 7617 | 99.25 | 54.58 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.77 | 7.36 | 0.41 |
| 2| 708 | 22.55 | 7.95 | 0.42 |
| 3| 1012 | 28.12 | 10.19 | 0.50 |
| 5| 1335 | 32.28 | 12.67 | 0.56 |
| 10| 2107 | 42.19 | 18.76 | 0.72 |
| 40| 6670 | 99.89 | 54.82 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.09 | 8.89 | 0.48 |
| 2| 784 | 30.94 | 10.07 | 0.51 |
| 3| 917 | 32.80 | 11.25 | 0.54 |
| 5| 1302 | 35.26 | 13.32 | 0.59 |
| 10| 2016 | 44.70 | 19.32 | 0.74 |
| 37| 6081 | 98.57 | 52.43 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 33.83 | 10.16 | 0.53 |
| 2| 768 | 35.14 | 11.16 | 0.55 |
| 3| 942 | 37.91 | 12.62 | 0.59 |
| 5| 1226 | 41.93 | 15.06 | 0.65 |
| 10| 2049 | 53.87 | 21.76 | 0.83 |
| 29| 4932 | 99.07 | 47.03 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 27.12 | 9.10 | 0.69 |
| 2| 5928 | 35.95 | 12.10 | 0.79 |
| 3| 6148 | 44.79 | 15.08 | 0.89 |
| 4| 6230 | 53.85 | 18.10 | 0.99 |
| 5| 6413 | 62.79 | 21.07 | 1.09 |
| 6| 6462 | 69.59 | 23.42 | 1.17 |
| 7| 6752 | 83.21 | 28.05 | 1.32 |
| 8| 6840 | 93.48 | 31.49 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 284 | 6003 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 568 | 6172 | 39.69 | 14.52 | 0.85 |
| 10 | 30 | 1708 | 6854 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2220 | 7159 | 99.31 | 38.01 | 1.54 |

