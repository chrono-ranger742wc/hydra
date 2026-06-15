--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-15 10:57:52.969906814 UTC |
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
| 1| 5837 | 10.85 | 3.45 | 0.52 |
| 2| 6041 | 12.44 | 3.94 | 0.54 |
| 3| 6242 | 14.71 | 4.65 | 0.58 |
| 5| 6645 | 18.50 | 5.83 | 0.63 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 170 | 747 | 39.92 | 11.61 | 0.59 |
| 4 | 227 | 858 | 49.66 | 14.34 | 0.69 |
| 5 | 282 | 969 | 59.24 | 16.99 | 0.79 |
| 6 | 337 | 1081 | 75.26 | 21.25 | 0.96 |
| 7 | 393 | 1192 | 82.68 | 23.47 | 1.04 |
| 8 | 450 | 1303 | 84.95 | 24.46 | 1.07 |
| 9 | 504 | 1414 | 91.54 | 26.44 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1799 | 24.29 | 7.69 | 0.48 |
| 2| 1955 | 25.51 | 8.70 | 0.51 |
| 3| 2073 | 26.87 | 9.75 | 0.53 |
| 5| 2347 | 29.96 | 11.95 | 0.58 |
| 10| 3060 | 39.04 | 17.80 | 0.73 |
| 40| 7598 | 96.62 | 53.85 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 604 | 22.53 | 7.31 | 0.41 |
| 2| 793 | 23.98 | 8.37 | 0.44 |
| 3| 930 | 27.07 | 9.88 | 0.48 |
| 5| 1260 | 31.09 | 12.34 | 0.55 |
| 10| 1961 | 40.13 | 18.20 | 0.69 |
| 41| 6660 | 99.83 | 55.45 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.09 | 8.89 | 0.48 |
| 2| 741 | 30.27 | 9.86 | 0.50 |
| 3| 1017 | 34.18 | 11.67 | 0.56 |
| 5| 1385 | 38.41 | 14.20 | 0.62 |
| 10| 2020 | 45.02 | 19.40 | 0.74 |
| 36| 6020 | 98.26 | 51.69 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.16 | 0.53 |
| 2| 827 | 35.92 | 11.40 | 0.56 |
| 3| 1017 | 38.66 | 12.84 | 0.60 |
| 5| 1453 | 44.79 | 15.93 | 0.69 |
| 10| 2063 | 54.69 | 22.00 | 0.84 |
| 29| 4694 | 95.95 | 46.06 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5825 | 27.08 | 9.08 | 0.69 |
| 2| 5827 | 31.56 | 10.51 | 0.74 |
| 3| 6096 | 42.69 | 14.32 | 0.87 |
| 4| 6235 | 51.00 | 17.16 | 0.96 |
| 5| 6436 | 61.55 | 20.67 | 1.08 |
| 6| 6608 | 70.72 | 23.78 | 1.18 |
| 7| 6808 | 81.16 | 27.33 | 1.30 |
| 8| 6873 | 86.78 | 29.21 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1137 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 37 | 2109 | 7095 | 93.06 | 35.66 | 1.47 |

