--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-27 08:28:27.510363596 UTC |
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
| 1| 5838 | 10.35 | 3.28 | 0.51 |
| 2| 6037 | 12.54 | 3.97 | 0.55 |
| 3| 6239 | 14.60 | 4.62 | 0.58 |
| 5| 6641 | 18.72 | 5.91 | 0.64 |
| 10| 7646 | 29.09 | 9.17 | 0.79 |
| 43| 14279 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 170 | 751 | 41.01 | 11.85 | 0.60 |
| 4 | 227 | 858 | 48.20 | 14.02 | 0.68 |
| 5 | 281 | 969 | 59.52 | 17.06 | 0.80 |
| 6 | 336 | 1081 | 73.41 | 20.81 | 0.94 |
| 7 | 395 | 1196 | 84.49 | 23.86 | 1.06 |
| 8 | 451 | 1303 | 97.63 | 27.39 | 1.19 |
| 9 | 505 | 1414 | 98.95 | 28.27 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1821 | 24.37 | 7.71 | 0.48 |
| 2| 1930 | 25.55 | 8.71 | 0.50 |
| 3| 2110 | 28.38 | 10.16 | 0.55 |
| 5| 2342 | 29.92 | 11.94 | 0.58 |
| 10| 3086 | 39.07 | 17.82 | 0.73 |
| 41| 7706 | 97.84 | 54.84 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 634 | 22.84 | 7.38 | 0.42 |
| 2| 804 | 25.57 | 8.80 | 0.46 |
| 3| 911 | 25.79 | 9.54 | 0.47 |
| 5| 1167 | 28.05 | 11.48 | 0.51 |
| 10| 2035 | 39.59 | 18.06 | 0.69 |
| 40| 6425 | 95.05 | 53.49 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 27.54 | 8.47 | 0.46 |
| 2| 793 | 30.95 | 10.07 | 0.51 |
| 3| 903 | 30.15 | 10.52 | 0.51 |
| 5| 1272 | 34.55 | 13.11 | 0.58 |
| 10| 1982 | 46.84 | 19.85 | 0.76 |
| 35| 5912 | 97.35 | 50.82 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 33.87 | 10.16 | 0.53 |
| 2| 837 | 35.85 | 11.38 | 0.56 |
| 3| 969 | 37.91 | 12.62 | 0.59 |
| 5| 1251 | 42.65 | 15.28 | 0.66 |
| 10| 2041 | 54.17 | 21.84 | 0.84 |
| 29| 4894 | 98.72 | 46.89 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5822 | 27.12 | 9.10 | 0.69 |
| 2| 5965 | 35.92 | 12.06 | 0.79 |
| 3| 6242 | 46.94 | 15.85 | 0.92 |
| 4| 6212 | 53.87 | 18.12 | 0.99 |
| 5| 6412 | 63.56 | 21.40 | 1.10 |
| 6| 6600 | 75.16 | 25.40 | 1.23 |
| 7| 6821 | 82.69 | 27.90 | 1.32 |
| 8| 6857 | 89.06 | 29.95 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.98 | 10.65 | 0.73 |
| 10 | 10 | 570 | 6174 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1136 | 6510 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2221 | 7161 | 98.05 | 37.58 | 1.53 |

