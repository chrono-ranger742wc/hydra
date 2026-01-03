--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-03 05:37:56.862320769 UTC |
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
| 1| 5840 | 10.61 | 3.37 | 0.52 |
| 2| 6041 | 12.63 | 4.00 | 0.55 |
| 3| 6236 | 14.50 | 4.58 | 0.57 |
| 5| 6641 | 18.58 | 5.86 | 0.63 |
| 10| 7651 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 99.14 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.39 | 9.43 | 0.51 |
| 3 | 170 | 747 | 42.55 | 12.23 | 0.62 |
| 4 | 225 | 858 | 47.87 | 13.88 | 0.67 |
| 5 | 282 | 969 | 60.66 | 17.33 | 0.81 |
| 6 | 338 | 1081 | 73.88 | 21.00 | 0.95 |
| 7 | 393 | 1192 | 73.07 | 21.21 | 0.95 |
| 8 | 450 | 1303 | 90.09 | 25.69 | 1.12 |
| 9 | 506 | 1414 | 98.84 | 28.19 | 1.21 |
| 10 | 560 | 1525 | 99.91 | 28.85 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1801 | 24.00 | 7.62 | 0.48 |
| 2| 1919 | 25.43 | 8.69 | 0.50 |
| 3| 2222 | 29.17 | 10.39 | 0.56 |
| 5| 2393 | 31.09 | 12.26 | 0.60 |
| 10| 2978 | 37.89 | 17.48 | 0.71 |
| 40| 7477 | 98.37 | 54.28 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 610 | 22.84 | 7.37 | 0.41 |
| 2| 767 | 24.32 | 8.46 | 0.44 |
| 3| 987 | 28.10 | 10.17 | 0.49 |
| 5| 1315 | 30.60 | 12.23 | 0.54 |
| 10| 2025 | 39.52 | 18.03 | 0.69 |
| 43| 6703 | 99.61 | 56.70 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 680 | 29.13 | 8.90 | 0.48 |
| 2| 837 | 31.66 | 10.28 | 0.52 |
| 3| 980 | 33.51 | 11.47 | 0.55 |
| 5| 1343 | 35.68 | 13.45 | 0.59 |
| 10| 2005 | 47.85 | 20.16 | 0.77 |
| 36| 5905 | 97.03 | 51.31 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.87 | 10.16 | 0.53 |
| 2| 811 | 35.92 | 11.40 | 0.56 |
| 3| 984 | 38.55 | 12.81 | 0.60 |
| 5| 1322 | 43.32 | 15.49 | 0.67 |
| 10| 1991 | 53.30 | 21.58 | 0.82 |
| 29| 4840 | 96.94 | 46.40 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5811 | 27.05 | 9.07 | 0.69 |
| 2| 5962 | 36.07 | 12.13 | 0.79 |
| 3| 6060 | 44.85 | 15.08 | 0.89 |
| 4| 6206 | 53.73 | 18.07 | 0.99 |
| 5| 6292 | 59.11 | 19.82 | 1.05 |
| 6| 6611 | 74.65 | 25.19 | 1.23 |
| 7| 6792 | 83.97 | 28.30 | 1.33 |
| 8| 6784 | 85.53 | 28.76 | 1.35 |
| 9| 6937 | 98.34 | 33.12 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6175 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6514 | 61.05 | 22.90 | 1.10 |
| 10 | 30 | 1710 | 6857 | 80.92 | 30.76 | 1.33 |
| 10 | 40 | 2276 | 7192 | 99.66 | 38.24 | 1.55 |

