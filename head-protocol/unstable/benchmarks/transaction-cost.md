--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-20 07:19:23.18194806 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6236 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 19.17 | 6.07 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2167 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 40.20 | 11.70 | 0.59 |
| 4 | 225 | 858 | 52.31 | 14.97 | 0.72 |
| 5 | 282 | 969 | 57.13 | 16.62 | 0.77 |
| 6 | 338 | 1081 | 70.03 | 20.04 | 0.91 |
| 7 | 394 | 1192 | 84.58 | 23.88 | 1.06 |
| 8 | 449 | 1307 | 82.69 | 23.82 | 1.05 |
| 9 | 507 | 1414 | 96.42 | 27.56 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1808 | 24.00 | 7.62 | 0.48 |
| 2| 2030 | 26.42 | 8.96 | 0.52 |
| 3| 2076 | 26.90 | 9.76 | 0.53 |
| 5| 2463 | 33.15 | 12.84 | 0.62 |
| 10| 3280 | 44.05 | 19.21 | 0.79 |
| 40| 7605 | 98.76 | 54.40 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 650 | 22.81 | 7.38 | 0.42 |
| 2| 759 | 24.35 | 8.46 | 0.44 |
| 3| 884 | 25.05 | 9.30 | 0.46 |
| 5| 1184 | 29.11 | 11.79 | 0.52 |
| 10| 1903 | 37.00 | 17.32 | 0.66 |
| 43| 6795 | 99.56 | 56.70 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.17 | 8.91 | 0.48 |
| 2| 774 | 28.47 | 9.38 | 0.48 |
| 3| 976 | 33.43 | 11.44 | 0.55 |
| 5| 1168 | 33.70 | 12.84 | 0.57 |
| 10| 2050 | 44.67 | 19.31 | 0.74 |
| 35| 5791 | 95.75 | 50.31 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 33.87 | 10.16 | 0.53 |
| 2| 835 | 35.92 | 11.40 | 0.56 |
| 3| 1036 | 39.14 | 13.00 | 0.61 |
| 5| 1293 | 43.20 | 15.46 | 0.67 |
| 10| 1941 | 52.44 | 21.32 | 0.81 |
| 29| 4991 | 99.34 | 47.08 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 27.09 | 9.08 | 0.69 |
| 2| 6001 | 36.93 | 12.46 | 0.80 |
| 3| 5978 | 40.47 | 13.52 | 0.84 |
| 4| 6367 | 55.99 | 18.90 | 1.02 |
| 5| 6338 | 60.00 | 20.16 | 1.06 |
| 6| 6682 | 75.48 | 25.48 | 1.24 |
| 7| 6651 | 80.00 | 26.87 | 1.28 |
| 8| 6753 | 88.07 | 29.55 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 569 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2221 | 7161 | 98.49 | 37.73 | 1.53 |

