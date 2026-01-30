--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-30 05:34:44.925545592 UTC |
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
| 1| 5840 | 10.74 | 3.42 | 0.52 |
| 2| 6035 | 12.92 | 4.11 | 0.55 |
| 3| 6239 | 14.76 | 4.67 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 28.94 | 9.11 | 0.79 |
| 43| 14279 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10075 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 169 | 751 | 42.60 | 12.26 | 0.62 |
| 4 | 225 | 858 | 49.57 | 14.34 | 0.69 |
| 5 | 281 | 969 | 64.18 | 18.21 | 0.84 |
| 6 | 338 | 1081 | 73.63 | 20.90 | 0.94 |
| 7 | 393 | 1192 | 84.22 | 23.79 | 1.05 |
| 8 | 455 | 1303 | 89.52 | 25.45 | 1.11 |
| 9 | 505 | 1414 | 89.00 | 25.89 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1801 | 24.00 | 7.62 | 0.48 |
| 2| 1943 | 25.84 | 8.78 | 0.51 |
| 3| 2191 | 29.10 | 10.38 | 0.56 |
| 5| 2457 | 31.88 | 12.49 | 0.61 |
| 10| 3249 | 43.11 | 18.96 | 0.78 |
| 38| 7250 | 92.20 | 51.27 | 1.58 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 661 | 22.77 | 7.37 | 0.42 |
| 2| 803 | 25.43 | 8.76 | 0.45 |
| 3| 919 | 24.99 | 9.29 | 0.46 |
| 5| 1278 | 31.18 | 12.38 | 0.55 |
| 10| 2088 | 40.74 | 18.37 | 0.70 |
| 39| 6213 | 92.92 | 52.20 | 1.55 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 26.79 | 8.25 | 0.45 |
| 2| 782 | 30.95 | 10.07 | 0.51 |
| 3| 988 | 33.47 | 11.45 | 0.55 |
| 5| 1319 | 35.53 | 13.41 | 0.59 |
| 10| 1974 | 44.04 | 19.11 | 0.73 |
| 35| 5504 | 96.65 | 50.42 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.79 | 10.15 | 0.53 |
| 2| 853 | 36.60 | 11.61 | 0.57 |
| 3| 1089 | 39.30 | 13.04 | 0.61 |
| 5| 1311 | 42.87 | 15.35 | 0.66 |
| 10| 2152 | 55.63 | 22.28 | 0.86 |
| 28| 4713 | 96.05 | 45.48 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5827 | 26.92 | 9.04 | 0.69 |
| 2| 5997 | 37.05 | 12.48 | 0.80 |
| 3| 6022 | 41.48 | 13.89 | 0.85 |
| 4| 6261 | 55.21 | 18.58 | 1.01 |
| 5| 6366 | 62.98 | 21.17 | 1.09 |
| 6| 6517 | 73.50 | 24.76 | 1.21 |
| 7| 6798 | 81.90 | 27.60 | 1.31 |
| 8| 7019 | 93.42 | 31.49 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.52 | 6.98 | 0.62 |
| 10 | 20 | 1139 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 39 | 2223 | 7162 | 98.49 | 37.73 | 1.53 |

