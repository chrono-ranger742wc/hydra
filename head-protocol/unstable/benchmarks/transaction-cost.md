--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-20 05:33:08.425861159 UTC |
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
| 1| 5836 | 10.59 | 3.36 | 0.52 |
| 2| 6037 | 12.84 | 4.08 | 0.55 |
| 3| 6236 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 19.08 | 6.04 | 0.64 |
| 10| 7648 | 28.92 | 9.11 | 0.79 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10047 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 34.19 | 9.84 | 0.53 |
| 3 | 170 | 747 | 41.48 | 11.99 | 0.60 |
| 4 | 227 | 858 | 52.45 | 15.03 | 0.72 |
| 5 | 283 | 969 | 64.64 | 18.32 | 0.85 |
| 6 | 340 | 1081 | 66.24 | 19.10 | 0.87 |
| 7 | 394 | 1192 | 72.34 | 20.91 | 0.94 |
| 8 | 449 | 1303 | 82.96 | 23.94 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1807 | 24.29 | 7.69 | 0.48 |
| 2| 2001 | 26.91 | 9.08 | 0.52 |
| 3| 2060 | 26.94 | 9.77 | 0.53 |
| 5| 2370 | 30.80 | 12.19 | 0.59 |
| 10| 3195 | 41.78 | 18.58 | 0.76 |
| 40| 7785 | 99.95 | 54.72 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 606 | 22.57 | 7.30 | 0.41 |
| 2| 764 | 24.27 | 8.46 | 0.44 |
| 3| 933 | 25.83 | 9.55 | 0.47 |
| 5| 1399 | 33.00 | 12.89 | 0.57 |
| 10| 2026 | 41.13 | 18.50 | 0.71 |
| 43| 6758 | 98.35 | 56.37 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 641 | 29.17 | 8.91 | 0.48 |
| 2| 836 | 31.62 | 10.28 | 0.52 |
| 3| 948 | 33.47 | 11.46 | 0.55 |
| 5| 1315 | 37.85 | 14.02 | 0.62 |
| 10| 1995 | 45.00 | 19.39 | 0.74 |
| 35| 5776 | 99.62 | 51.31 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 705 | 33.87 | 10.16 | 0.53 |
| 2| 853 | 36.56 | 11.60 | 0.57 |
| 3| 1007 | 38.84 | 12.90 | 0.60 |
| 5| 1321 | 43.40 | 15.50 | 0.67 |
| 10| 1989 | 53.53 | 21.64 | 0.83 |
| 29| 5043 | 99.98 | 47.28 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5833 | 27.08 | 9.09 | 0.69 |
| 2| 5985 | 37.01 | 12.46 | 0.80 |
| 3| 6001 | 40.38 | 13.47 | 0.84 |
| 4| 6241 | 51.62 | 17.34 | 0.97 |
| 5| 6344 | 62.52 | 21.05 | 1.09 |
| 6| 6566 | 70.60 | 23.73 | 1.18 |
| 7| 6687 | 81.75 | 27.46 | 1.30 |
| 8| 7089 | 95.56 | 32.39 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 56 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1137 | 6511 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6854 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2223 | 7163 | 98.49 | 37.73 | 1.53 |

