--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-10 05:39:07.720767826 UTC |
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
| 1| 5834 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.42 | 3.93 | 0.54 |
| 3| 6242 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 29.23 | 9.22 | 0.79 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 170 | 747 | 39.96 | 11.62 | 0.59 |
| 4 | 228 | 862 | 49.41 | 14.25 | 0.69 |
| 5 | 281 | 969 | 58.10 | 16.79 | 0.78 |
| 6 | 340 | 1081 | 72.91 | 20.72 | 0.94 |
| 7 | 395 | 1196 | 84.29 | 23.76 | 1.06 |
| 8 | 448 | 1303 | 95.56 | 26.90 | 1.17 |
| 9 | 507 | 1418 | 99.61 | 28.38 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.37 | 7.71 | 0.48 |
| 2| 1886 | 24.47 | 8.41 | 0.49 |
| 3| 2095 | 27.06 | 9.80 | 0.53 |
| 5| 2407 | 30.93 | 12.22 | 0.59 |
| 10| 3071 | 39.46 | 17.94 | 0.73 |
| 41| 7739 | 99.96 | 55.42 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.77 | 7.36 | 0.42 |
| 2| 829 | 25.17 | 8.71 | 0.45 |
| 3| 895 | 25.09 | 9.31 | 0.46 |
| 5| 1120 | 26.94 | 11.17 | 0.50 |
| 10| 1922 | 38.38 | 17.72 | 0.67 |
| 43| 6781 | 97.34 | 56.13 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 29.13 | 8.90 | 0.48 |
| 2| 870 | 29.97 | 9.84 | 0.50 |
| 3| 974 | 33.40 | 11.44 | 0.55 |
| 5| 1287 | 35.01 | 13.24 | 0.59 |
| 10| 2186 | 46.96 | 20.00 | 0.77 |
| 36| 6003 | 97.26 | 51.44 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.12 | 9.94 | 0.52 |
| 2| 854 | 36.60 | 11.61 | 0.57 |
| 3| 1086 | 39.26 | 13.03 | 0.61 |
| 5| 1250 | 42.60 | 15.27 | 0.66 |
| 10| 1947 | 52.63 | 21.37 | 0.82 |
| 29| 4824 | 98.10 | 46.73 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 27.09 | 9.10 | 0.69 |
| 2| 5962 | 35.89 | 12.07 | 0.79 |
| 3| 6096 | 44.68 | 15.03 | 0.89 |
| 4| 6333 | 55.92 | 18.86 | 1.02 |
| 5| 6448 | 64.13 | 21.59 | 1.11 |
| 6| 6522 | 71.95 | 24.23 | 1.19 |
| 7| 6636 | 78.46 | 26.29 | 1.27 |
| 8| 6977 | 94.12 | 31.79 | 1.45 |
| 9| 6927 | 94.63 | 31.82 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 22.55 | 7.67 | 0.65 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6513 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2223 | 7162 | 98.05 | 37.58 | 1.53 |

