--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-12 06:00:33.044986892 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7650 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 99.32 | 31.06 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1284 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 40.18 | 11.66 | 0.59 |
| 4 | 227 | 858 | 49.57 | 14.31 | 0.69 |
| 5 | 285 | 969 | 63.23 | 18.05 | 0.83 |
| 6 | 337 | 1081 | 69.28 | 19.78 | 0.90 |
| 7 | 397 | 1192 | 78.67 | 22.51 | 1.00 |
| 8 | 451 | 1303 | 81.03 | 23.47 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1829 | 24.37 | 7.71 | 0.48 |
| 2| 1947 | 25.84 | 8.78 | 0.51 |
| 3| 2165 | 29.42 | 10.45 | 0.56 |
| 5| 2527 | 33.36 | 12.89 | 0.62 |
| 10| 3114 | 40.61 | 18.25 | 0.75 |
| 38| 7274 | 93.17 | 51.51 | 1.59 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.84 | 7.38 | 0.42 |
| 2| 802 | 25.47 | 8.78 | 0.45 |
| 3| 942 | 26.91 | 9.86 | 0.48 |
| 5| 1116 | 27.12 | 11.22 | 0.50 |
| 10| 1987 | 39.84 | 18.11 | 0.69 |
| 41| 6595 | 97.28 | 54.77 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 27.54 | 8.47 | 0.46 |
| 2| 858 | 29.93 | 9.83 | 0.50 |
| 3| 968 | 30.90 | 10.74 | 0.52 |
| 5| 1231 | 34.26 | 13.01 | 0.58 |
| 10| 1993 | 47.21 | 19.98 | 0.76 |
| 35| 5902 | 98.10 | 50.99 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.87 | 10.16 | 0.53 |
| 2| 820 | 35.85 | 11.38 | 0.56 |
| 3| 993 | 38.59 | 12.82 | 0.60 |
| 5| 1398 | 44.11 | 15.72 | 0.68 |
| 10| 2120 | 54.66 | 22.00 | 0.84 |
| 28| 4733 | 94.78 | 45.13 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5820 | 27.00 | 9.09 | 0.69 |
| 2| 6021 | 37.01 | 12.46 | 0.80 |
| 3| 6097 | 42.45 | 14.27 | 0.86 |
| 4| 6215 | 50.12 | 16.81 | 0.95 |
| 5| 6345 | 63.53 | 21.36 | 1.10 |
| 6| 6594 | 71.18 | 24.00 | 1.19 |
| 7| 6835 | 85.48 | 28.92 | 1.35 |
| 8| 6789 | 86.11 | 29.00 | 1.35 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.38 | 6.48 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 286 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6175 | 39.51 | 14.45 | 0.85 |
| 10 | 30 | 1708 | 6854 | 79.60 | 30.31 | 1.31 |
| 10 | 40 | 2277 | 7193 | 99.66 | 38.24 | 1.55 |
| 10 | 38 | 2164 | 7127 | 96.88 | 37.08 | 1.51 |

