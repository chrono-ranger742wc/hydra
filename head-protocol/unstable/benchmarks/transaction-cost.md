--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-06 04:40:41.271479089 UTC |
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
| 1| 5834 | 10.17 | 3.22 | 0.51 |
| 2| 6039 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.50 | 5.83 | 0.63 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14286 | 99.02 | 30.95 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 747 | 41.35 | 11.96 | 0.60 |
| 4 | 228 | 858 | 53.73 | 15.31 | 0.73 |
| 5 | 282 | 969 | 58.24 | 16.79 | 0.78 |
| 6 | 341 | 1081 | 68.43 | 19.66 | 0.89 |
| 7 | 395 | 1192 | 71.97 | 20.90 | 0.93 |
| 8 | 451 | 1303 | 84.39 | 24.22 | 1.06 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1817 | 23.92 | 7.60 | 0.48 |
| 2| 1884 | 24.81 | 8.49 | 0.49 |
| 3| 2059 | 27.35 | 9.87 | 0.53 |
| 5| 2331 | 29.96 | 11.95 | 0.58 |
| 10| 3217 | 41.60 | 18.54 | 0.76 |
| 40| 7530 | 94.68 | 53.28 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.84 | 7.40 | 0.42 |
| 2| 830 | 25.57 | 8.80 | 0.46 |
| 3| 976 | 26.88 | 9.84 | 0.48 |
| 5| 1366 | 33.50 | 13.03 | 0.57 |
| 10| 1969 | 39.03 | 17.90 | 0.68 |
| 43| 6713 | 99.48 | 56.66 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 653 | 29.13 | 8.90 | 0.48 |
| 2| 861 | 31.65 | 10.28 | 0.52 |
| 3| 941 | 32.76 | 11.24 | 0.54 |
| 5| 1232 | 37.06 | 13.79 | 0.60 |
| 10| 2040 | 45.69 | 19.60 | 0.75 |
| 36| 6086 | 99.03 | 51.94 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 33.87 | 10.16 | 0.53 |
| 2| 839 | 35.89 | 11.39 | 0.56 |
| 3| 965 | 37.88 | 12.61 | 0.59 |
| 5| 1295 | 43.35 | 15.49 | 0.67 |
| 10| 2011 | 53.83 | 21.75 | 0.83 |
| 29| 4683 | 95.82 | 46.03 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.13 | 9.11 | 0.69 |
| 2| 6025 | 36.88 | 12.46 | 0.80 |
| 3| 6119 | 44.56 | 15.00 | 0.89 |
| 4| 6240 | 51.36 | 17.26 | 0.96 |
| 5| 6328 | 63.09 | 21.20 | 1.09 |
| 6| 6644 | 74.54 | 25.13 | 1.23 |
| 7| 6686 | 81.16 | 27.28 | 1.30 |
| 8| 6913 | 94.01 | 31.66 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1706 | 6852 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2220 | 7159 | 98.05 | 37.58 | 1.53 |

