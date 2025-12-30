--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-30 05:49:25.230277739 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6035 | 12.46 | 3.94 | 0.54 |
| 3| 6243 | 14.60 | 4.62 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.80 | 9.07 | 0.78 |
| 43| 14279 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2181 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 170 | 747 | 39.85 | 11.58 | 0.59 |
| 4 | 225 | 858 | 51.10 | 14.68 | 0.71 |
| 5 | 283 | 974 | 62.57 | 17.79 | 0.83 |
| 6 | 341 | 1081 | 63.71 | 18.48 | 0.85 |
| 7 | 394 | 1192 | 72.60 | 21.06 | 0.94 |
| 8 | 452 | 1303 | 94.11 | 26.70 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 22.92 | 7.32 | 0.47 |
| 2| 1882 | 24.77 | 8.48 | 0.49 |
| 3| 2017 | 26.32 | 9.58 | 0.52 |
| 5| 2424 | 32.11 | 12.55 | 0.61 |
| 10| 3189 | 42.23 | 18.69 | 0.77 |
| 39| 7474 | 97.32 | 53.36 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 602 | 22.57 | 7.30 | 0.41 |
| 2| 866 | 25.44 | 8.78 | 0.46 |
| 3| 1039 | 28.16 | 10.20 | 0.50 |
| 5| 1169 | 28.76 | 11.72 | 0.52 |
| 10| 2027 | 40.89 | 18.41 | 0.70 |
| 40| 6531 | 98.83 | 54.46 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 658 | 29.13 | 8.90 | 0.48 |
| 2| 823 | 31.62 | 10.28 | 0.52 |
| 3| 1049 | 31.65 | 10.97 | 0.53 |
| 5| 1207 | 36.27 | 13.55 | 0.59 |
| 10| 2008 | 44.71 | 19.32 | 0.74 |
| 38| 6167 | 99.56 | 53.35 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 33.83 | 10.15 | 0.53 |
| 2| 813 | 35.85 | 11.38 | 0.56 |
| 3| 946 | 37.95 | 12.63 | 0.59 |
| 5| 1245 | 42.61 | 15.27 | 0.66 |
| 10| 2122 | 55.28 | 22.19 | 0.85 |
| 29| 4937 | 97.90 | 46.68 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5790 | 27.00 | 9.07 | 0.69 |
| 2| 5994 | 36.93 | 12.43 | 0.80 |
| 3| 6066 | 44.57 | 15.00 | 0.89 |
| 4| 6260 | 54.00 | 18.13 | 0.99 |
| 5| 6488 | 63.90 | 21.61 | 1.11 |
| 6| 6731 | 75.94 | 25.70 | 1.25 |
| 7| 6782 | 84.92 | 28.63 | 1.34 |
| 8| 6926 | 91.81 | 31.01 | 1.42 |
| 9| 6899 | 97.81 | 32.95 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.08 | 6.83 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.98 | 10.65 | 0.73 |
| 10 | 20 | 1139 | 6513 | 59.91 | 22.51 | 1.08 |
| 10 | 30 | 1709 | 6856 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2220 | 7159 | 98.93 | 37.88 | 1.54 |

