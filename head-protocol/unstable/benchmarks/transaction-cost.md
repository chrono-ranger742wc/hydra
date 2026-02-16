--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-16 06:03:33.855584073 UTC |
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
| 1| 5837 | 10.55 | 3.35 | 0.52 |
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6242 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.93 | 5.98 | 0.64 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14282 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2165 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 171 | 747 | 42.25 | 12.15 | 0.61 |
| 4 | 226 | 858 | 48.32 | 14.02 | 0.68 |
| 5 | 283 | 969 | 62.38 | 17.77 | 0.83 |
| 6 | 340 | 1081 | 70.96 | 20.22 | 0.92 |
| 7 | 393 | 1192 | 72.08 | 20.93 | 0.94 |
| 8 | 450 | 1303 | 95.36 | 26.80 | 1.17 |
| 9 | 506 | 1418 | 98.39 | 27.97 | 1.21 |
| 10 | 560 | 1525 | 97.98 | 28.52 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1787 | 24.37 | 7.71 | 0.48 |
| 2| 1942 | 25.51 | 8.70 | 0.50 |
| 3| 2013 | 26.28 | 9.57 | 0.52 |
| 5| 2495 | 33.59 | 12.95 | 0.62 |
| 10| 3288 | 43.98 | 19.19 | 0.79 |
| 42| 7869 | 99.83 | 56.04 | 1.71 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.50 | 7.29 | 0.41 |
| 2| 815 | 25.45 | 8.77 | 0.46 |
| 3| 900 | 25.58 | 9.50 | 0.47 |
| 5| 1178 | 29.18 | 11.79 | 0.52 |
| 10| 1894 | 36.47 | 17.18 | 0.65 |
| 42| 6761 | 99.72 | 56.12 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.13 | 8.90 | 0.48 |
| 2| 785 | 30.98 | 10.08 | 0.51 |
| 3| 974 | 30.86 | 10.73 | 0.52 |
| 5| 1218 | 34.33 | 13.03 | 0.58 |
| 10| 2008 | 44.30 | 19.18 | 0.73 |
| 35| 5705 | 94.22 | 49.87 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.16 | 0.53 |
| 2| 810 | 35.81 | 11.37 | 0.56 |
| 3| 996 | 38.66 | 12.84 | 0.60 |
| 5| 1322 | 43.13 | 15.44 | 0.67 |
| 10| 2054 | 54.73 | 22.01 | 0.84 |
| 29| 4838 | 97.63 | 46.60 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5836 | 26.96 | 9.06 | 0.69 |
| 2| 5874 | 34.87 | 11.67 | 0.77 |
| 3| 6127 | 46.06 | 15.51 | 0.90 |
| 4| 6201 | 54.05 | 18.14 | 0.99 |
| 5| 6379 | 61.71 | 20.74 | 1.08 |
| 6| 6643 | 74.65 | 25.12 | 1.23 |
| 7| 6846 | 82.32 | 27.77 | 1.32 |
| 8| 6747 | 84.73 | 28.44 | 1.34 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6513 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1707 | 6853 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2222 | 7161 | 98.49 | 37.73 | 1.53 |

