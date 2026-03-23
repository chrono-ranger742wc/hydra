--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-23 06:04:18.162099807 UTC |
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
| 2| 6037 | 12.34 | 3.90 | 0.54 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6646 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 747 | 43.56 | 12.48 | 0.63 |
| 4 | 227 | 858 | 48.56 | 14.15 | 0.68 |
| 5 | 283 | 974 | 64.15 | 18.20 | 0.84 |
| 6 | 339 | 1081 | 68.71 | 19.77 | 0.90 |
| 7 | 395 | 1192 | 82.61 | 23.45 | 1.04 |
| 8 | 449 | 1303 | 91.52 | 25.98 | 1.13 |
| 9 | 505 | 1414 | 91.72 | 26.49 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1819 | 24.37 | 7.71 | 0.48 |
| 2| 2018 | 26.55 | 9.00 | 0.52 |
| 3| 2131 | 28.06 | 10.08 | 0.54 |
| 5| 2323 | 30.00 | 11.96 | 0.58 |
| 10| 3210 | 41.47 | 18.48 | 0.76 |
| 38| 7103 | 90.12 | 50.67 | 1.56 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.57 | 7.31 | 0.41 |
| 2| 782 | 24.05 | 8.39 | 0.44 |
| 3| 925 | 25.10 | 9.32 | 0.46 |
| 5| 1216 | 29.19 | 11.80 | 0.52 |
| 10| 2022 | 39.43 | 18.00 | 0.69 |
| 41| 6576 | 98.09 | 54.96 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 29.17 | 8.91 | 0.48 |
| 2| 783 | 30.94 | 10.07 | 0.51 |
| 3| 975 | 33.51 | 11.47 | 0.55 |
| 5| 1320 | 35.65 | 13.44 | 0.59 |
| 10| 2027 | 47.85 | 20.16 | 0.77 |
| 36| 5867 | 96.90 | 51.29 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.83 | 10.15 | 0.53 |
| 2| 803 | 35.92 | 11.40 | 0.56 |
| 3| 900 | 37.20 | 12.40 | 0.58 |
| 5| 1207 | 42.01 | 15.08 | 0.65 |
| 10| 2117 | 55.33 | 22.20 | 0.85 |
| 30| 5052 | 99.27 | 47.71 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5846 | 27.00 | 9.07 | 0.69 |
| 2| 5948 | 36.01 | 12.11 | 0.79 |
| 3| 6121 | 46.01 | 15.51 | 0.90 |
| 4| 6262 | 55.19 | 18.66 | 1.01 |
| 5| 6376 | 61.83 | 20.76 | 1.08 |
| 6| 6423 | 66.19 | 22.25 | 1.13 |
| 7| 6575 | 77.94 | 26.13 | 1.26 |
| 8| 7097 | 92.25 | 31.17 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 285 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6173 | 40.39 | 14.75 | 0.85 |
| 10 | 30 | 1707 | 6854 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2218 | 7157 | 99.38 | 38.04 | 1.54 |

