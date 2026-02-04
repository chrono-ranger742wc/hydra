--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-04 05:35:48.88360366 UTC |
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
| 1| 5836 | 10.40 | 3.30 | 0.51 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 18.84 | 5.95 | 0.64 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14279 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.34 | 9.42 | 0.51 |
| 3 | 170 | 747 | 40.17 | 11.66 | 0.59 |
| 4 | 226 | 858 | 49.72 | 14.38 | 0.69 |
| 5 | 282 | 974 | 59.03 | 16.94 | 0.79 |
| 6 | 339 | 1081 | 66.53 | 19.28 | 0.87 |
| 7 | 393 | 1192 | 84.90 | 24.04 | 1.06 |
| 8 | 451 | 1303 | 96.72 | 27.28 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1749 | 22.92 | 7.32 | 0.47 |
| 2| 2008 | 26.92 | 9.08 | 0.52 |
| 3| 2148 | 28.05 | 10.08 | 0.54 |
| 5| 2511 | 33.56 | 12.94 | 0.63 |
| 10| 3247 | 42.03 | 18.64 | 0.77 |
| 38| 7529 | 98.26 | 52.95 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 604 | 22.57 | 7.31 | 0.41 |
| 2| 824 | 25.33 | 8.74 | 0.45 |
| 3| 949 | 26.09 | 9.60 | 0.47 |
| 5| 1205 | 30.10 | 12.06 | 0.53 |
| 10| 1985 | 40.84 | 18.40 | 0.70 |
| 41| 6739 | 99.79 | 55.45 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 29.13 | 8.90 | 0.48 |
| 2| 824 | 29.18 | 9.60 | 0.49 |
| 3| 975 | 33.43 | 11.44 | 0.55 |
| 5| 1351 | 35.65 | 13.44 | 0.59 |
| 10| 1983 | 46.77 | 19.83 | 0.76 |
| 35| 5919 | 96.77 | 50.62 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.87 | 10.16 | 0.53 |
| 2| 869 | 36.60 | 11.61 | 0.57 |
| 3| 1018 | 38.55 | 12.81 | 0.60 |
| 5| 1225 | 41.93 | 15.06 | 0.65 |
| 10| 2134 | 55.52 | 22.25 | 0.85 |
| 28| 4849 | 98.17 | 46.13 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5794 | 27.00 | 9.07 | 0.69 |
| 2| 5996 | 37.16 | 12.52 | 0.80 |
| 3| 6117 | 44.76 | 15.03 | 0.89 |
| 4| 6167 | 53.17 | 17.80 | 0.98 |
| 5| 6316 | 60.44 | 20.27 | 1.06 |
| 6| 6558 | 71.23 | 24.04 | 1.19 |
| 7| 6642 | 79.68 | 26.90 | 1.28 |
| 8| 6897 | 93.40 | 31.42 | 1.43 |
| 9| 6957 | 95.14 | 32.14 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1709 | 6855 | 80.92 | 30.76 | 1.33 |
| 10 | 40 | 2279 | 7195 | 99.84 | 38.30 | 1.55 |

