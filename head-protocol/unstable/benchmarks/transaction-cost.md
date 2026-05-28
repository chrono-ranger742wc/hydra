--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-28 08:23:14.064417851 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6035 | 12.70 | 4.03 | 0.55 |
| 3| 6239 | 14.40 | 4.55 | 0.57 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 29.19 | 9.21 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2167 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 640 | 33.33 | 9.64 | 0.52 |
| 3 | 169 | 747 | 42.46 | 12.22 | 0.61 |
| 4 | 227 | 858 | 50.24 | 14.45 | 0.70 |
| 5 | 282 | 969 | 63.02 | 17.93 | 0.83 |
| 6 | 341 | 1081 | 67.41 | 19.33 | 0.88 |
| 7 | 394 | 1196 | 82.83 | 23.51 | 1.04 |
| 8 | 451 | 1303 | 88.28 | 25.31 | 1.10 |
| 9 | 504 | 1414 | 98.94 | 28.22 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.37 | 7.71 | 0.48 |
| 2| 1942 | 25.55 | 8.71 | 0.50 |
| 3| 2073 | 27.43 | 9.89 | 0.53 |
| 5| 2472 | 32.79 | 12.75 | 0.62 |
| 10| 3026 | 38.59 | 17.69 | 0.72 |
| 40| 7655 | 97.74 | 54.12 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 658 | 22.77 | 7.37 | 0.42 |
| 2| 746 | 23.61 | 8.25 | 0.43 |
| 3| 887 | 25.51 | 9.48 | 0.46 |
| 5| 1322 | 31.07 | 12.34 | 0.55 |
| 10| 1921 | 37.37 | 17.46 | 0.66 |
| 42| 6724 | 99.83 | 56.11 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 29.09 | 8.89 | 0.48 |
| 2| 774 | 28.55 | 9.40 | 0.48 |
| 3| 937 | 32.76 | 11.24 | 0.54 |
| 5| 1320 | 35.76 | 13.47 | 0.59 |
| 10| 2034 | 45.23 | 19.47 | 0.75 |
| 36| 5900 | 97.15 | 51.34 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.79 | 10.15 | 0.53 |
| 2| 891 | 36.64 | 11.62 | 0.57 |
| 3| 900 | 37.20 | 12.40 | 0.58 |
| 5| 1352 | 43.92 | 15.67 | 0.68 |
| 10| 2035 | 53.91 | 21.77 | 0.83 |
| 29| 4959 | 99.49 | 47.17 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5826 | 27.08 | 9.09 | 0.69 |
| 2| 5946 | 36.00 | 12.09 | 0.79 |
| 3| 6070 | 44.61 | 15.04 | 0.89 |
| 4| 6260 | 54.94 | 18.49 | 1.00 |
| 5| 6432 | 65.05 | 21.94 | 1.12 |
| 6| 6517 | 69.08 | 23.21 | 1.16 |
| 7| 6720 | 83.53 | 28.16 | 1.32 |
| 8| 6768 | 88.99 | 30.05 | 1.38 |
| 9| 6883 | 95.32 | 32.00 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1137 | 6511 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1707 | 6854 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2220 | 7160 | 98.05 | 37.58 | 1.53 |

