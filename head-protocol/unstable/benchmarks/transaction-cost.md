--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-23 05:45:49.660798727 UTC |
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
| 1| 5841 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.41 | 3.92 | 0.54 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 19.17 | 6.07 | 0.64 |
| 10| 7646 | 29.38 | 9.27 | 0.79 |
| 43| 14282 | 99.02 | 30.95 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 171 | 751 | 40.14 | 11.65 | 0.59 |
| 4 | 227 | 858 | 47.72 | 13.85 | 0.67 |
| 5 | 283 | 969 | 59.51 | 17.06 | 0.80 |
| 6 | 338 | 1081 | 72.56 | 20.57 | 0.93 |
| 7 | 394 | 1192 | 74.00 | 21.39 | 0.95 |
| 8 | 452 | 1303 | 93.57 | 26.47 | 1.15 |
| 9 | 505 | 1414 | 89.45 | 25.84 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1817 | 24.37 | 7.71 | 0.48 |
| 2| 1920 | 25.88 | 8.79 | 0.51 |
| 3| 2070 | 27.35 | 9.87 | 0.53 |
| 5| 2333 | 30.04 | 11.97 | 0.58 |
| 10| 3112 | 40.24 | 18.14 | 0.74 |
| 39| 7561 | 96.44 | 53.10 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.84 | 7.38 | 0.41 |
| 2| 722 | 22.56 | 7.94 | 0.42 |
| 3| 838 | 24.09 | 9.05 | 0.45 |
| 5| 1146 | 28.07 | 11.49 | 0.51 |
| 10| 2176 | 44.43 | 19.38 | 0.74 |
| 40| 6347 | 94.19 | 53.23 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.17 | 8.91 | 0.48 |
| 2| 778 | 30.95 | 10.07 | 0.51 |
| 3| 1061 | 32.40 | 11.20 | 0.54 |
| 5| 1259 | 35.08 | 13.26 | 0.58 |
| 10| 2112 | 48.48 | 20.36 | 0.78 |
| 35| 5761 | 93.69 | 49.74 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.87 | 10.16 | 0.53 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 1014 | 38.55 | 12.81 | 0.60 |
| 5| 1307 | 43.17 | 15.45 | 0.67 |
| 10| 2121 | 54.94 | 22.08 | 0.85 |
| 29| 4852 | 97.87 | 46.64 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5793 | 27.00 | 9.06 | 0.69 |
| 2| 5971 | 35.88 | 12.04 | 0.79 |
| 3| 6071 | 42.49 | 14.26 | 0.86 |
| 4| 6253 | 52.12 | 17.54 | 0.97 |
| 5| 6388 | 63.00 | 21.15 | 1.09 |
| 6| 6567 | 72.98 | 24.57 | 1.21 |
| 7| 6732 | 80.18 | 27.10 | 1.29 |
| 8| 6993 | 93.65 | 31.61 | 1.44 |
| 9| 7113 | 99.83 | 33.62 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 56 | 5867 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 286 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 571 | 6175 | 39.95 | 14.60 | 0.85 |
| 10 | 30 | 1710 | 6857 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2222 | 7162 | 99.38 | 38.04 | 1.54 |

