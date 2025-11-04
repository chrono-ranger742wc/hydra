--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-04 05:34:05.663582426 UTC |
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
| 1| 5836 | 10.76 | 3.42 | 0.52 |
| 2| 6035 | 12.32 | 3.89 | 0.54 |
| 3| 6239 | 14.90 | 4.72 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 29.12 | 9.18 | 0.79 |
| 43| 14285 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 914 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 42.65 | 12.27 | 0.62 |
| 4 | 228 | 858 | 52.43 | 15.00 | 0.72 |
| 5 | 284 | 969 | 56.38 | 16.31 | 0.77 |
| 6 | 338 | 1081 | 71.67 | 20.43 | 0.92 |
| 7 | 395 | 1196 | 72.25 | 20.92 | 0.94 |
| 8 | 452 | 1303 | 84.67 | 24.34 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1808 | 24.00 | 7.62 | 0.48 |
| 2| 1989 | 26.92 | 9.08 | 0.52 |
| 3| 2062 | 27.28 | 9.85 | 0.53 |
| 5| 2391 | 30.85 | 12.20 | 0.59 |
| 10| 3132 | 40.47 | 18.22 | 0.75 |
| 40| 7645 | 98.78 | 54.38 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 609 | 22.57 | 7.30 | 0.41 |
| 2| 745 | 23.62 | 8.24 | 0.43 |
| 3| 959 | 26.57 | 9.77 | 0.48 |
| 5| 1222 | 29.19 | 11.80 | 0.52 |
| 10| 1817 | 35.60 | 16.92 | 0.64 |
| 42| 6809 | 99.44 | 56.02 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 27.54 | 8.47 | 0.46 |
| 2| 824 | 31.62 | 10.28 | 0.52 |
| 3| 934 | 32.72 | 11.23 | 0.54 |
| 5| 1335 | 35.83 | 13.49 | 0.60 |
| 10| 2109 | 45.47 | 19.55 | 0.75 |
| 35| 5774 | 95.22 | 50.14 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.87 | 10.16 | 0.53 |
| 2| 830 | 35.85 | 11.38 | 0.56 |
| 3| 1019 | 38.92 | 12.92 | 0.60 |
| 5| 1248 | 42.53 | 15.25 | 0.66 |
| 10| 2068 | 54.77 | 22.02 | 0.84 |
| 30| 4911 | 98.13 | 47.38 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 26.96 | 9.06 | 0.69 |
| 2| 5963 | 36.00 | 12.10 | 0.79 |
| 3| 5951 | 40.48 | 13.51 | 0.84 |
| 4| 6260 | 53.81 | 18.08 | 0.99 |
| 5| 6528 | 64.63 | 21.81 | 1.12 |
| 6| 6427 | 68.76 | 23.07 | 1.15 |
| 7| 6714 | 76.79 | 25.87 | 1.25 |
| 8| 6658 | 85.88 | 28.76 | 1.34 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 56 | 5867 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 284 | 6003 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 569 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6513 | 60.17 | 22.59 | 1.09 |
| 10 | 38 | 2166 | 7129 | 96.88 | 37.08 | 1.51 |

