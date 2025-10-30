--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-30 05:31:42.040760756 UTC |
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
| 1| 5841 | 10.61 | 3.37 | 0.52 |
| 2| 6035 | 12.80 | 4.07 | 0.55 |
| 3| 6236 | 14.90 | 4.72 | 0.58 |
| 5| 6638 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2164 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 528 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 40.05 | 11.65 | 0.59 |
| 4 | 227 | 858 | 52.37 | 14.96 | 0.72 |
| 5 | 281 | 974 | 56.34 | 16.33 | 0.77 |
| 6 | 337 | 1081 | 65.93 | 19.06 | 0.87 |
| 7 | 394 | 1192 | 80.71 | 23.00 | 1.02 |
| 8 | 451 | 1303 | 80.90 | 23.44 | 1.03 |
| 9 | 506 | 1414 | 98.76 | 28.12 | 1.21 |
| 10 | 560 | 1525 | 99.20 | 28.56 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1791 | 24.29 | 7.69 | 0.48 |
| 2| 1884 | 24.77 | 8.48 | 0.49 |
| 3| 2108 | 28.47 | 10.18 | 0.55 |
| 5| 2437 | 32.04 | 12.53 | 0.61 |
| 10| 3061 | 40.03 | 18.08 | 0.74 |
| 40| 7590 | 97.86 | 54.15 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.57 | 7.31 | 0.41 |
| 2| 813 | 25.55 | 8.81 | 0.46 |
| 3| 1033 | 27.69 | 10.08 | 0.49 |
| 5| 1150 | 28.18 | 11.53 | 0.51 |
| 10| 1961 | 39.38 | 17.99 | 0.68 |
| 41| 6546 | 97.16 | 54.70 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 27.50 | 8.46 | 0.46 |
| 2| 834 | 31.58 | 10.27 | 0.52 |
| 3| 1045 | 34.19 | 11.67 | 0.56 |
| 5| 1176 | 36.35 | 13.57 | 0.59 |
| 10| 2051 | 47.89 | 20.19 | 0.77 |
| 33| 5614 | 93.16 | 48.26 | 1.50 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.15 | 0.53 |
| 2| 852 | 36.64 | 11.62 | 0.57 |
| 3| 1005 | 38.17 | 12.70 | 0.59 |
| 5| 1309 | 43.21 | 15.46 | 0.67 |
| 10| 1977 | 53.30 | 21.58 | 0.82 |
| 28| 5024 | 99.44 | 46.54 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.05 | 9.07 | 0.69 |
| 2| 6021 | 36.92 | 12.45 | 0.80 |
| 3| 6047 | 41.44 | 13.87 | 0.85 |
| 4| 6214 | 51.33 | 17.21 | 0.96 |
| 5| 6506 | 66.19 | 22.38 | 1.13 |
| 6| 6492 | 69.54 | 23.38 | 1.17 |
| 7| 6819 | 85.64 | 28.92 | 1.35 |
| 8| 7020 | 94.29 | 31.92 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.85 | 7.43 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 568 | 6172 | 39.51 | 14.45 | 0.85 |
| 10 | 30 | 1710 | 6856 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2222 | 7162 | 99.38 | 38.04 | 1.54 |

