--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-19 09:37:51.725185984 UTC |
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
| 1| 5834 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6645 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.38 | 9.43 | 0.51 |
| 3 | 169 | 747 | 43.71 | 12.54 | 0.63 |
| 4 | 227 | 858 | 49.40 | 14.25 | 0.69 |
| 5 | 282 | 974 | 61.09 | 17.50 | 0.81 |
| 6 | 340 | 1081 | 70.74 | 20.24 | 0.92 |
| 7 | 393 | 1192 | 84.51 | 23.86 | 1.06 |
| 8 | 449 | 1303 | 92.12 | 26.13 | 1.14 |
| 10 | 560 | 1525 | 99.83 | 28.83 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.37 | 7.71 | 0.48 |
| 2| 1981 | 26.96 | 9.09 | 0.52 |
| 3| 2079 | 26.95 | 9.77 | 0.53 |
| 5| 2332 | 29.89 | 11.93 | 0.58 |
| 10| 3311 | 44.38 | 19.31 | 0.79 |
| 38| 7409 | 96.97 | 52.59 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 22.81 | 7.37 | 0.42 |
| 2| 869 | 25.49 | 8.79 | 0.46 |
| 3| 908 | 25.52 | 9.47 | 0.46 |
| 5| 1150 | 28.18 | 11.53 | 0.51 |
| 10| 2058 | 39.68 | 18.07 | 0.69 |
| 42| 6773 | 99.74 | 56.11 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 659 | 29.13 | 8.90 | 0.48 |
| 2| 887 | 29.90 | 9.82 | 0.50 |
| 3| 928 | 32.76 | 11.24 | 0.54 |
| 5| 1218 | 37.10 | 13.80 | 0.60 |
| 10| 1942 | 46.61 | 19.79 | 0.75 |
| 35| 5691 | 99.19 | 51.20 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.87 | 10.16 | 0.53 |
| 2| 856 | 36.64 | 11.62 | 0.57 |
| 3| 998 | 38.55 | 12.81 | 0.60 |
| 5| 1231 | 41.97 | 15.07 | 0.65 |
| 10| 2118 | 55.49 | 22.24 | 0.85 |
| 29| 4964 | 99.36 | 47.10 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5826 | 27.08 | 9.09 | 0.69 |
| 2| 5924 | 32.52 | 10.89 | 0.75 |
| 3| 5943 | 38.24 | 12.74 | 0.81 |
| 4| 6224 | 53.92 | 18.10 | 0.99 |
| 5| 6475 | 65.21 | 22.01 | 1.12 |
| 6| 6479 | 70.44 | 23.65 | 1.17 |
| 7| 6680 | 79.74 | 26.81 | 1.28 |
| 8| 6789 | 88.05 | 29.56 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6175 | 39.25 | 14.36 | 0.84 |
| 10 | 38 | 2156 | 7119 | 96.44 | 36.92 | 1.51 |

