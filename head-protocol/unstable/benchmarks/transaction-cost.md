--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-10 06:56:42.33654323 UTC |
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
| 1| 5836 | 10.47 | 3.32 | 0.52 |
| 2| 6038 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.48 | 4.58 | 0.57 |
| 5| 6640 | 18.52 | 5.84 | 0.63 |
| 10| 7644 | 29.31 | 9.25 | 0.79 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 169 | 751 | 43.70 | 12.54 | 0.63 |
| 4 | 225 | 858 | 50.86 | 14.60 | 0.70 |
| 5 | 281 | 969 | 58.92 | 16.92 | 0.79 |
| 6 | 338 | 1081 | 70.04 | 20.01 | 0.91 |
| 7 | 395 | 1192 | 82.49 | 23.38 | 1.04 |
| 8 | 449 | 1303 | 96.33 | 27.14 | 1.18 |
| 9 | 505 | 1414 | 91.28 | 26.32 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1747 | 22.92 | 7.32 | 0.47 |
| 2| 1989 | 26.38 | 8.96 | 0.52 |
| 3| 2059 | 27.43 | 9.89 | 0.53 |
| 5| 2382 | 31.20 | 12.29 | 0.60 |
| 10| 3245 | 42.22 | 18.69 | 0.77 |
| 41| 7775 | 99.37 | 55.24 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 22.50 | 7.29 | 0.41 |
| 2| 828 | 25.20 | 8.71 | 0.45 |
| 3| 948 | 26.56 | 9.77 | 0.48 |
| 5| 1194 | 28.58 | 11.66 | 0.52 |
| 10| 2059 | 39.31 | 17.97 | 0.69 |
| 42| 6854 | 99.72 | 56.13 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 27.51 | 8.47 | 0.46 |
| 2| 812 | 29.26 | 9.62 | 0.49 |
| 3| 961 | 30.98 | 10.76 | 0.52 |
| 5| 1176 | 36.31 | 13.56 | 0.59 |
| 10| 2017 | 45.02 | 19.40 | 0.74 |
| 35| 5819 | 95.45 | 50.22 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.16 | 0.53 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 943 | 37.91 | 12.62 | 0.59 |
| 5| 1203 | 41.86 | 15.04 | 0.65 |
| 10| 2322 | 57.54 | 22.87 | 0.88 |
| 29| 5095 | 99.91 | 47.28 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 27.05 | 9.07 | 0.69 |
| 2| 5901 | 34.91 | 11.70 | 0.78 |
| 3| 6130 | 44.99 | 15.15 | 0.89 |
| 4| 6129 | 48.99 | 16.37 | 0.93 |
| 5| 6352 | 61.42 | 20.59 | 1.07 |
| 6| 6439 | 69.22 | 23.27 | 1.16 |
| 7| 6627 | 78.22 | 26.29 | 1.26 |
| 8| 6920 | 90.61 | 30.50 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 569 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2223 | 7162 | 99.38 | 38.04 | 1.54 |

