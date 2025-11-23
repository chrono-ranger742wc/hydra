--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-23 05:43:41.978948143 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6236 | 14.48 | 4.58 | 0.57 |
| 5| 6640 | 18.93 | 5.98 | 0.64 |
| 10| 7646 | 29.47 | 9.30 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 169 | 747 | 42.75 | 12.31 | 0.62 |
| 4 | 228 | 858 | 51.98 | 14.89 | 0.72 |
| 5 | 284 | 969 | 61.05 | 17.49 | 0.81 |
| 6 | 337 | 1081 | 71.98 | 20.51 | 0.93 |
| 7 | 394 | 1192 | 77.01 | 22.20 | 0.98 |
| 8 | 448 | 1303 | 86.84 | 24.81 | 1.09 |
| 9 | 505 | 1414 | 98.87 | 28.20 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 24.00 | 7.62 | 0.48 |
| 2| 1932 | 25.76 | 8.76 | 0.51 |
| 3| 2059 | 27.24 | 9.84 | 0.53 |
| 5| 2385 | 31.25 | 12.30 | 0.60 |
| 10| 3222 | 42.78 | 18.86 | 0.77 |
| 40| 7608 | 98.27 | 54.27 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.77 | 7.36 | 0.41 |
| 2| 773 | 23.66 | 8.26 | 0.44 |
| 3| 888 | 25.01 | 9.29 | 0.46 |
| 5| 1235 | 29.07 | 11.76 | 0.52 |
| 10| 2153 | 43.13 | 19.04 | 0.73 |
| 42| 6606 | 95.19 | 54.85 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 700 | 27.51 | 8.47 | 0.46 |
| 2| 811 | 30.94 | 10.07 | 0.51 |
| 3| 944 | 32.76 | 11.24 | 0.54 |
| 5| 1134 | 35.56 | 13.33 | 0.58 |
| 10| 2100 | 45.73 | 19.61 | 0.75 |
| 35| 5730 | 98.66 | 51.05 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 33.79 | 10.15 | 0.53 |
| 2| 834 | 35.92 | 11.40 | 0.56 |
| 3| 1032 | 38.84 | 12.91 | 0.60 |
| 5| 1272 | 42.56 | 15.26 | 0.66 |
| 10| 2012 | 54.02 | 21.80 | 0.83 |
| 30| 4951 | 99.96 | 47.90 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.13 | 9.10 | 0.69 |
| 2| 5993 | 36.97 | 12.46 | 0.80 |
| 3| 6182 | 47.13 | 15.94 | 0.92 |
| 4| 6388 | 55.85 | 18.86 | 1.02 |
| 5| 6378 | 64.57 | 21.69 | 1.11 |
| 6| 6700 | 74.96 | 25.35 | 1.23 |
| 7| 6951 | 86.54 | 29.25 | 1.37 |
| 8| 6717 | 85.50 | 28.68 | 1.34 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 19.45 | 6.61 | 0.61 |
| 10 | 5 | 287 | 6006 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1137 | 6511 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1711 | 6857 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2223 | 7162 | 98.49 | 37.73 | 1.53 |

