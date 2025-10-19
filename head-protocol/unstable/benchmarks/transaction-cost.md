--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-19 04:39:50.937966044 UTC |
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
| 2| 6035 | 12.65 | 4.01 | 0.55 |
| 3| 6236 | 14.50 | 4.58 | 0.57 |
| 5| 6638 | 18.58 | 5.86 | 0.63 |
| 10| 7650 | 29.09 | 9.17 | 0.79 |
| 43| 14279 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 41.20 | 11.90 | 0.60 |
| 4 | 228 | 858 | 49.73 | 14.36 | 0.69 |
| 5 | 281 | 969 | 59.81 | 17.22 | 0.80 |
| 6 | 339 | 1081 | 72.62 | 20.58 | 0.93 |
| 7 | 396 | 1192 | 86.83 | 24.46 | 1.08 |
| 8 | 450 | 1307 | 85.48 | 24.68 | 1.08 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1802 | 24.29 | 7.69 | 0.48 |
| 2| 1947 | 25.76 | 8.76 | 0.51 |
| 3| 2117 | 28.01 | 10.07 | 0.54 |
| 5| 2321 | 30.00 | 11.96 | 0.58 |
| 10| 3161 | 41.06 | 18.37 | 0.75 |
| 40| 7732 | 99.37 | 54.61 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 620 | 22.84 | 7.37 | 0.42 |
| 2| 730 | 22.60 | 7.95 | 0.42 |
| 3| 989 | 28.15 | 10.18 | 0.49 |
| 5| 1387 | 32.17 | 12.65 | 0.56 |
| 10| 1955 | 37.54 | 17.47 | 0.67 |
| 40| 6478 | 94.99 | 53.43 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 642 | 29.17 | 8.91 | 0.48 |
| 2| 782 | 30.90 | 10.06 | 0.51 |
| 3| 952 | 30.86 | 10.73 | 0.52 |
| 5| 1271 | 35.05 | 13.25 | 0.58 |
| 10| 1885 | 46.09 | 19.63 | 0.75 |
| 36| 5730 | 99.42 | 51.88 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 33.83 | 10.15 | 0.53 |
| 2| 802 | 35.89 | 11.39 | 0.56 |
| 3| 1002 | 38.59 | 12.82 | 0.60 |
| 5| 1161 | 41.29 | 14.86 | 0.64 |
| 10| 2108 | 55.16 | 22.16 | 0.85 |
| 30| 5015 | 99.54 | 47.79 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.04 | 9.08 | 0.69 |
| 2| 5824 | 31.56 | 10.49 | 0.74 |
| 3| 6068 | 44.76 | 15.04 | 0.89 |
| 4| 6267 | 54.95 | 18.50 | 1.00 |
| 5| 6303 | 62.22 | 20.89 | 1.08 |
| 6| 6469 | 65.87 | 22.07 | 1.13 |
| 7| 6723 | 80.87 | 27.28 | 1.30 |
| 8| 6621 | 81.91 | 27.49 | 1.30 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 5 | 284 | 6004 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 569 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1137 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2221 | 7160 | 98.93 | 37.88 | 1.54 |

