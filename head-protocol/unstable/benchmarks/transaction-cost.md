--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-21 09:07:10.041989788 UTC |
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
| 1| 5834 | 10.55 | 3.35 | 0.52 |
| 2| 6038 | 12.32 | 3.89 | 0.54 |
| 3| 6236 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7651 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1284 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 169 | 747 | 43.72 | 12.52 | 0.63 |
| 4 | 226 | 858 | 52.15 | 14.94 | 0.72 |
| 5 | 282 | 974 | 56.24 | 16.34 | 0.77 |
| 6 | 337 | 1081 | 72.06 | 20.53 | 0.93 |
| 7 | 395 | 1192 | 73.06 | 21.21 | 0.95 |
| 8 | 449 | 1303 | 85.17 | 24.47 | 1.07 |
| 9 | 504 | 1414 | 91.71 | 26.54 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 24.29 | 7.69 | 0.48 |
| 2| 1933 | 25.39 | 8.68 | 0.50 |
| 3| 2184 | 29.47 | 10.46 | 0.56 |
| 5| 2391 | 31.15 | 12.28 | 0.60 |
| 10| 3352 | 44.34 | 19.28 | 0.80 |
| 40| 7512 | 98.18 | 54.25 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 22.84 | 7.39 | 0.41 |
| 2| 746 | 23.61 | 8.25 | 0.43 |
| 3| 878 | 25.05 | 9.30 | 0.46 |
| 5| 1255 | 31.33 | 12.40 | 0.55 |
| 10| 2044 | 40.86 | 18.41 | 0.70 |
| 42| 6669 | 99.92 | 56.16 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 641 | 29.17 | 8.91 | 0.48 |
| 2| 807 | 30.91 | 10.06 | 0.51 |
| 3| 1010 | 31.65 | 10.97 | 0.53 |
| 5| 1130 | 35.56 | 13.34 | 0.58 |
| 10| 1960 | 43.66 | 19.00 | 0.73 |
| 35| 6037 | 99.34 | 51.39 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 33.15 | 9.95 | 0.52 |
| 2| 858 | 36.56 | 11.60 | 0.57 |
| 3| 991 | 38.59 | 12.82 | 0.60 |
| 5| 1302 | 43.24 | 15.47 | 0.67 |
| 10| 2012 | 53.99 | 21.79 | 0.83 |
| 29| 4836 | 97.20 | 46.43 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5779 | 27.13 | 9.09 | 0.69 |
| 2| 5960 | 35.88 | 12.05 | 0.79 |
| 3| 6195 | 46.89 | 15.88 | 0.92 |
| 4| 6230 | 52.66 | 17.71 | 0.98 |
| 5| 6473 | 61.45 | 20.71 | 1.08 |
| 6| 6583 | 74.58 | 25.15 | 1.22 |
| 7| 6780 | 84.52 | 28.60 | 1.34 |
| 8| 6883 | 89.21 | 30.00 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 56 | 5867 | 21.41 | 7.28 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1705 | 6851 | 80.22 | 30.52 | 1.32 |
| 10 | 37 | 2105 | 7090 | 94.83 | 36.27 | 1.49 |

