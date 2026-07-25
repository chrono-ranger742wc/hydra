--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-25 06:50:19.067684981 UTC |
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
| 1| 5834 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.34 | 3.90 | 0.54 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.83 | 5.95 | 0.64 |
| 10| 7650 | 28.88 | 9.10 | 0.79 |
| 43| 14279 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 747 | 43.49 | 12.45 | 0.62 |
| 4 | 225 | 858 | 53.54 | 15.24 | 0.73 |
| 5 | 282 | 974 | 60.94 | 17.46 | 0.81 |
| 6 | 336 | 1081 | 75.33 | 21.27 | 0.96 |
| 7 | 397 | 1192 | 76.74 | 22.13 | 0.98 |
| 8 | 450 | 1303 | 96.42 | 27.21 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1819 | 23.92 | 7.60 | 0.48 |
| 2| 1995 | 26.55 | 9.00 | 0.52 |
| 3| 2130 | 27.94 | 10.05 | 0.54 |
| 5| 2449 | 32.37 | 12.61 | 0.61 |
| 10| 3194 | 41.97 | 18.63 | 0.76 |
| 39| 7552 | 98.35 | 53.65 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 598 | 22.57 | 7.30 | 0.41 |
| 2| 840 | 25.16 | 8.71 | 0.45 |
| 3| 942 | 26.06 | 9.59 | 0.47 |
| 5| 1119 | 27.12 | 11.22 | 0.50 |
| 10| 1841 | 37.49 | 17.45 | 0.66 |
| 42| 6740 | 98.77 | 55.84 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.46 | 8.69 | 0.47 |
| 2| 808 | 30.90 | 10.06 | 0.51 |
| 3| 966 | 33.43 | 11.44 | 0.55 |
| 5| 1277 | 35.01 | 13.24 | 0.58 |
| 10| 2060 | 44.93 | 19.37 | 0.74 |
| 35| 6006 | 97.68 | 50.90 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.15 | 0.53 |
| 2| 768 | 35.17 | 11.17 | 0.55 |
| 3| 967 | 37.84 | 12.60 | 0.59 |
| 5| 1300 | 43.16 | 15.45 | 0.67 |
| 10| 2231 | 55.66 | 22.30 | 0.86 |
| 29| 5041 | 99.56 | 47.21 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5836 | 26.92 | 9.05 | 0.69 |
| 2| 5920 | 36.07 | 12.13 | 0.79 |
| 3| 6170 | 45.66 | 15.40 | 0.90 |
| 4| 6296 | 55.02 | 18.52 | 1.01 |
| 5| 6407 | 64.04 | 21.57 | 1.11 |
| 6| 6561 | 74.51 | 25.08 | 1.22 |
| 7| 6863 | 82.80 | 27.97 | 1.32 |
| 8| 6896 | 93.04 | 31.36 | 1.43 |
| 9| 6903 | 95.07 | 32.00 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 10 | 570 | 6174 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1138 | 6512 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1710 | 6856 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2218 | 7157 | 99.38 | 38.04 | 1.54 |

