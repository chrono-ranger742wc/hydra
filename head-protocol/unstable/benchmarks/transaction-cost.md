--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-08 05:35:14.437149295 UTC |
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
| 2| 6041 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6645 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 29.12 | 9.18 | 0.79 |
| 43| 14285 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2182 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 170 | 747 | 42.48 | 12.24 | 0.61 |
| 4 | 226 | 858 | 53.93 | 15.36 | 0.73 |
| 5 | 283 | 974 | 59.66 | 17.19 | 0.80 |
| 6 | 339 | 1081 | 75.06 | 21.21 | 0.96 |
| 7 | 393 | 1192 | 84.83 | 23.99 | 1.06 |
| 8 | 449 | 1303 | 84.42 | 24.23 | 1.06 |
| 9 | 505 | 1414 | 89.16 | 25.93 | 1.12 |
| 10 | 561 | 1525 | 99.42 | 28.67 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 24.00 | 7.62 | 0.48 |
| 2| 1970 | 26.84 | 9.06 | 0.52 |
| 3| 2013 | 26.32 | 9.58 | 0.52 |
| 5| 2549 | 34.31 | 13.16 | 0.63 |
| 10| 3264 | 43.32 | 19.01 | 0.78 |
| 40| 7673 | 99.20 | 54.54 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 781 | 24.32 | 8.46 | 0.44 |
| 3| 858 | 24.11 | 9.04 | 0.45 |
| 5| 1190 | 29.10 | 11.77 | 0.52 |
| 10| 1942 | 37.74 | 17.52 | 0.67 |
| 40| 6449 | 99.00 | 54.51 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 598 | 28.46 | 8.69 | 0.47 |
| 2| 778 | 28.51 | 9.39 | 0.48 |
| 3| 1063 | 32.21 | 11.15 | 0.54 |
| 5| 1241 | 34.30 | 13.02 | 0.58 |
| 10| 2060 | 48.04 | 20.23 | 0.77 |
| 36| 5946 | 97.07 | 51.32 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.87 | 10.16 | 0.53 |
| 2| 889 | 36.60 | 11.61 | 0.57 |
| 3| 945 | 37.84 | 12.60 | 0.59 |
| 5| 1354 | 43.32 | 15.48 | 0.67 |
| 10| 2078 | 54.63 | 21.99 | 0.84 |
| 28| 4772 | 96.48 | 45.64 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.58 | 0.64 |
| 2| 5892 | 32.61 | 10.88 | 0.75 |
| 3| 6111 | 45.07 | 15.14 | 0.89 |
| 4| 6243 | 54.82 | 18.50 | 1.00 |
| 5| 6529 | 65.03 | 21.98 | 1.12 |
| 6| 6621 | 74.37 | 25.02 | 1.22 |
| 7| 6629 | 79.19 | 26.56 | 1.27 |
| 8| 6912 | 90.66 | 30.62 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6175 | 39.51 | 14.45 | 0.85 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2220 | 7160 | 98.49 | 37.73 | 1.53 |

