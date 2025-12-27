--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-27 05:41:39.894156163 UTC |
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
| 1| 5836 | 10.35 | 3.28 | 0.51 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.81 | 4.69 | 0.58 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2181 | 12.13 | 7.25 | 0.40 |
| 54| 10046 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 751 | 43.95 | 12.60 | 0.63 |
| 4 | 225 | 858 | 49.22 | 14.21 | 0.69 |
| 5 | 282 | 974 | 60.98 | 17.41 | 0.81 |
| 6 | 337 | 1081 | 70.27 | 20.13 | 0.91 |
| 7 | 393 | 1196 | 74.39 | 21.44 | 0.96 |
| 8 | 450 | 1303 | 85.78 | 24.71 | 1.08 |
| 9 | 505 | 1414 | 89.21 | 25.83 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1817 | 24.00 | 7.62 | 0.48 |
| 2| 1960 | 25.85 | 8.78 | 0.51 |
| 3| 2017 | 26.28 | 9.57 | 0.52 |
| 5| 2426 | 32.02 | 12.53 | 0.61 |
| 10| 3125 | 39.32 | 17.90 | 0.73 |
| 40| 7546 | 96.41 | 53.78 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 641 | 22.81 | 7.37 | 0.42 |
| 2| 801 | 24.32 | 8.46 | 0.44 |
| 3| 1007 | 27.95 | 10.13 | 0.49 |
| 5| 1178 | 29.14 | 11.78 | 0.52 |
| 10| 2031 | 39.50 | 18.02 | 0.69 |
| 42| 6692 | 97.70 | 55.51 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.13 | 8.90 | 0.48 |
| 2| 838 | 29.26 | 9.62 | 0.49 |
| 3| 914 | 32.76 | 11.24 | 0.54 |
| 5| 1346 | 35.69 | 13.45 | 0.59 |
| 10| 2051 | 44.77 | 19.33 | 0.74 |
| 37| 6210 | 99.69 | 52.78 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 33.87 | 10.16 | 0.53 |
| 2| 816 | 35.89 | 11.39 | 0.56 |
| 3| 891 | 37.24 | 12.41 | 0.58 |
| 5| 1262 | 42.61 | 15.27 | 0.66 |
| 10| 1981 | 53.27 | 21.57 | 0.82 |
| 29| 4924 | 98.01 | 46.71 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5820 | 26.92 | 9.04 | 0.69 |
| 2| 5996 | 37.12 | 12.51 | 0.80 |
| 3| 6042 | 44.96 | 15.13 | 0.89 |
| 4| 6275 | 54.96 | 18.49 | 1.00 |
| 5| 6451 | 61.31 | 20.61 | 1.08 |
| 6| 6504 | 69.67 | 23.44 | 1.17 |
| 7| 6710 | 82.35 | 27.67 | 1.31 |
| 8| 6766 | 88.69 | 29.83 | 1.38 |
| 9| 7066 | 99.54 | 33.49 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 570 | 6175 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1136 | 6511 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 40 | 2277 | 7194 | 99.66 | 38.24 | 1.55 |
| 10 | 39 | 2224 | 7163 | 99.12 | 37.95 | 1.54 |

