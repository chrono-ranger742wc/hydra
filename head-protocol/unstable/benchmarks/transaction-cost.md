--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-19 05:57:44.918631215 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6041 | 12.32 | 3.89 | 0.54 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6646 | 18.41 | 5.80 | 0.63 |
| 10| 7650 | 29.11 | 9.17 | 0.79 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10050 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 170 | 747 | 42.66 | 12.27 | 0.62 |
| 4 | 226 | 858 | 51.15 | 14.72 | 0.71 |
| 5 | 283 | 969 | 57.81 | 16.71 | 0.78 |
| 6 | 338 | 1081 | 66.35 | 19.12 | 0.87 |
| 7 | 395 | 1192 | 78.35 | 22.43 | 1.00 |
| 8 | 449 | 1303 | 94.63 | 26.73 | 1.16 |
| 9 | 504 | 1414 | 96.65 | 27.67 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1747 | 23.30 | 7.40 | 0.47 |
| 2| 1932 | 25.39 | 8.68 | 0.50 |
| 3| 2084 | 26.94 | 9.77 | 0.53 |
| 5| 2454 | 32.04 | 12.53 | 0.61 |
| 10| 3086 | 39.80 | 18.02 | 0.74 |
| 40| 7463 | 95.67 | 53.56 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 613 | 22.84 | 7.37 | 0.41 |
| 2| 772 | 24.28 | 8.45 | 0.44 |
| 3| 998 | 26.92 | 9.85 | 0.48 |
| 5| 1101 | 27.11 | 11.23 | 0.50 |
| 10| 2007 | 39.76 | 18.09 | 0.69 |
| 41| 6336 | 92.75 | 53.50 | 1.56 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 27.54 | 8.47 | 0.46 |
| 2| 796 | 30.94 | 10.07 | 0.51 |
| 3| 996 | 31.65 | 10.97 | 0.53 |
| 5| 1235 | 36.99 | 13.77 | 0.60 |
| 10| 2219 | 50.32 | 20.92 | 0.81 |
| 36| 5794 | 99.83 | 52.00 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 702 | 33.87 | 10.16 | 0.53 |
| 2| 842 | 35.92 | 11.40 | 0.56 |
| 3| 958 | 37.88 | 12.61 | 0.59 |
| 5| 1294 | 43.20 | 15.46 | 0.67 |
| 10| 2027 | 54.13 | 21.83 | 0.83 |
| 29| 4954 | 98.47 | 46.84 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5814 | 26.97 | 9.07 | 0.69 |
| 2| 5826 | 31.45 | 10.46 | 0.74 |
| 3| 6119 | 45.85 | 15.47 | 0.90 |
| 4| 6166 | 50.66 | 16.99 | 0.95 |
| 5| 6542 | 64.93 | 21.95 | 1.12 |
| 6| 6648 | 75.48 | 25.48 | 1.24 |
| 7| 7038 | 88.06 | 29.83 | 1.39 |
| 8| 6948 | 89.88 | 30.29 | 1.40 |
| 9| 6895 | 95.04 | 31.91 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1140 | 6514 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1710 | 6856 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2218 | 7158 | 98.93 | 37.88 | 1.54 |

