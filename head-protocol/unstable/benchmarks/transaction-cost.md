--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-06 05:37:26.184362226 UTC |
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
| 2| 6035 | 12.67 | 4.01 | 0.55 |
| 3| 6236 | 15.05 | 4.78 | 0.58 |
| 5| 6640 | 18.83 | 5.95 | 0.64 |
| 10| 7644 | 29.14 | 9.19 | 0.79 |
| 43| 14286 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2181 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.39 | 9.43 | 0.51 |
| 3 | 171 | 747 | 41.27 | 11.92 | 0.60 |
| 4 | 226 | 858 | 53.69 | 15.33 | 0.73 |
| 5 | 283 | 969 | 60.91 | 17.45 | 0.81 |
| 6 | 339 | 1081 | 64.79 | 18.79 | 0.86 |
| 7 | 396 | 1192 | 72.43 | 20.97 | 0.94 |
| 8 | 451 | 1303 | 86.83 | 24.81 | 1.09 |
| 10 | 561 | 1525 | 96.67 | 28.01 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 24.37 | 7.71 | 0.48 |
| 2| 1987 | 26.55 | 9.00 | 0.52 |
| 3| 2131 | 27.94 | 10.05 | 0.54 |
| 5| 2337 | 30.00 | 11.96 | 0.58 |
| 10| 3126 | 41.07 | 18.37 | 0.75 |
| 42| 7759 | 99.84 | 56.03 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 606 | 22.84 | 7.37 | 0.41 |
| 2| 718 | 22.52 | 7.93 | 0.42 |
| 3| 903 | 25.10 | 9.32 | 0.46 |
| 5| 1289 | 30.08 | 12.05 | 0.54 |
| 10| 2059 | 41.16 | 18.49 | 0.71 |
| 44| 6922 | 99.92 | 57.48 | 1.68 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 27.50 | 8.46 | 0.46 |
| 2| 839 | 29.15 | 9.59 | 0.49 |
| 3| 1029 | 31.65 | 10.97 | 0.53 |
| 5| 1270 | 37.62 | 13.96 | 0.61 |
| 10| 1835 | 45.15 | 19.35 | 0.74 |
| 36| 6109 | 98.64 | 51.84 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.83 | 10.15 | 0.53 |
| 2| 892 | 36.60 | 11.61 | 0.57 |
| 3| 993 | 38.66 | 12.84 | 0.60 |
| 5| 1221 | 41.86 | 15.04 | 0.65 |
| 10| 1990 | 53.42 | 21.61 | 0.83 |
| 29| 4943 | 99.13 | 47.05 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.09 | 9.09 | 0.69 |
| 2| 6024 | 37.00 | 12.48 | 0.80 |
| 3| 5974 | 40.28 | 13.43 | 0.84 |
| 4| 6322 | 55.31 | 18.62 | 1.01 |
| 5| 6411 | 64.21 | 21.63 | 1.11 |
| 6| 6433 | 66.04 | 22.18 | 1.13 |
| 7| 6737 | 81.07 | 27.26 | 1.30 |
| 8| 7043 | 96.13 | 32.56 | 1.47 |
| 9| 6876 | 94.99 | 31.93 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.98 | 10.65 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1132 | 6506 | 59.98 | 22.53 | 1.08 |
| 10 | 40 | 2278 | 7194 | 99.22 | 38.09 | 1.54 |
| 10 | 39 | 2224 | 7163 | 99.12 | 37.95 | 1.54 |

