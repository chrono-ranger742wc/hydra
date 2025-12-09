--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-09 05:39:39.950660066 UTC |
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
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6242 | 14.48 | 4.58 | 0.57 |
| 5| 6638 | 18.88 | 5.97 | 0.64 |
| 10| 7644 | 29.38 | 9.27 | 0.79 |
| 43| 14279 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1273 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 640 | 33.25 | 9.62 | 0.52 |
| 3 | 171 | 747 | 41.23 | 11.94 | 0.60 |
| 4 | 227 | 858 | 53.70 | 15.30 | 0.73 |
| 5 | 283 | 969 | 60.07 | 17.32 | 0.80 |
| 6 | 340 | 1085 | 73.71 | 20.92 | 0.94 |
| 7 | 397 | 1192 | 78.77 | 22.53 | 1.00 |
| 8 | 448 | 1303 | 95.75 | 26.90 | 1.18 |
| 9 | 506 | 1414 | 97.24 | 27.82 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1816 | 24.29 | 7.69 | 0.48 |
| 2| 1974 | 26.54 | 9.00 | 0.52 |
| 3| 2059 | 26.95 | 9.77 | 0.53 |
| 5| 2279 | 29.01 | 11.68 | 0.57 |
| 10| 3067 | 39.57 | 17.96 | 0.73 |
| 39| 7447 | 95.37 | 52.81 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 614 | 22.57 | 7.32 | 0.41 |
| 2| 818 | 25.16 | 8.72 | 0.45 |
| 3| 836 | 24.09 | 9.03 | 0.45 |
| 5| 1267 | 31.02 | 12.33 | 0.55 |
| 10| 2105 | 41.02 | 18.45 | 0.71 |
| 41| 6603 | 95.70 | 54.32 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 645 | 29.13 | 8.90 | 0.48 |
| 2| 826 | 29.48 | 9.69 | 0.49 |
| 3| 978 | 33.40 | 11.44 | 0.55 |
| 5| 1173 | 36.31 | 13.56 | 0.59 |
| 10| 2070 | 44.98 | 19.39 | 0.74 |
| 35| 5759 | 94.73 | 49.98 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.83 | 10.15 | 0.53 |
| 2| 798 | 35.92 | 11.40 | 0.56 |
| 3| 1019 | 38.85 | 12.91 | 0.60 |
| 5| 1254 | 42.57 | 15.26 | 0.66 |
| 10| 2017 | 53.76 | 21.71 | 0.83 |
| 30| 4901 | 98.51 | 47.48 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 23.01 | 7.58 | 0.64 |
| 2| 5992 | 37.05 | 12.48 | 0.80 |
| 3| 6062 | 42.44 | 14.26 | 0.86 |
| 4| 6264 | 55.10 | 18.55 | 1.00 |
| 5| 6330 | 63.24 | 21.33 | 1.09 |
| 6| 6724 | 76.13 | 25.82 | 1.25 |
| 7| 6700 | 79.56 | 26.82 | 1.28 |
| 8| 7096 | 94.93 | 32.10 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 569 | 6173 | 39.44 | 14.43 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6853 | 79.15 | 30.16 | 1.31 |
| 10 | 40 | 2276 | 7192 | 99.66 | 38.24 | 1.55 |

