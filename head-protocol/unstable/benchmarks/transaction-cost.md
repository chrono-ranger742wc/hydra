--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-29 05:38:58.940413291 UTC |
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
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.72 | 4.66 | 0.58 |
| 5| 6638 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.81 | 9.07 | 0.78 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 169 | 747 | 41.27 | 11.92 | 0.60 |
| 4 | 226 | 858 | 49.56 | 14.37 | 0.69 |
| 5 | 281 | 969 | 62.41 | 17.85 | 0.83 |
| 6 | 338 | 1081 | 72.07 | 20.57 | 0.93 |
| 7 | 392 | 1192 | 72.69 | 21.08 | 0.94 |
| 8 | 449 | 1303 | 85.08 | 24.39 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1822 | 24.00 | 7.62 | 0.48 |
| 2| 1937 | 25.43 | 8.68 | 0.50 |
| 3| 2101 | 28.39 | 10.16 | 0.55 |
| 5| 2409 | 32.11 | 12.55 | 0.61 |
| 10| 3213 | 42.91 | 18.89 | 0.77 |
| 40| 7685 | 99.36 | 54.60 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 658 | 22.81 | 7.38 | 0.42 |
| 2| 764 | 23.98 | 8.37 | 0.44 |
| 3| 913 | 25.10 | 9.32 | 0.46 |
| 5| 1277 | 32.02 | 12.60 | 0.56 |
| 10| 1990 | 38.80 | 17.83 | 0.68 |
| 41| 6523 | 96.82 | 54.62 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 662 | 29.17 | 8.91 | 0.48 |
| 2| 872 | 29.86 | 9.81 | 0.50 |
| 3| 964 | 30.94 | 10.75 | 0.52 |
| 5| 1238 | 36.95 | 13.76 | 0.60 |
| 10| 2134 | 48.60 | 20.41 | 0.78 |
| 35| 5839 | 95.76 | 50.35 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 625 | 33.15 | 9.95 | 0.52 |
| 2| 844 | 36.64 | 11.62 | 0.57 |
| 3| 1008 | 38.59 | 12.82 | 0.60 |
| 5| 1252 | 42.68 | 15.29 | 0.66 |
| 10| 1912 | 52.63 | 21.37 | 0.81 |
| 28| 4692 | 95.78 | 45.40 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.00 | 9.07 | 0.69 |
| 2| 6045 | 36.89 | 12.45 | 0.80 |
| 3| 6186 | 45.92 | 15.46 | 0.90 |
| 4| 6279 | 54.90 | 18.53 | 1.00 |
| 5| 6392 | 64.27 | 21.66 | 1.11 |
| 6| 6582 | 74.57 | 25.15 | 1.22 |
| 7| 6609 | 76.50 | 25.68 | 1.24 |
| 8| 7027 | 94.59 | 31.93 | 1.45 |
| 9| 6957 | 98.27 | 33.07 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 22.55 | 7.67 | 0.65 |
| 10 | 5 | 285 | 6004 | 27.76 | 9.89 | 0.71 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6514 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 37 | 2102 | 7088 | 94.39 | 36.12 | 1.49 |

