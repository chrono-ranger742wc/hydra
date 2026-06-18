--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-18 09:19:07.853636605 UTC |
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
| 1| 5834 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 19.17 | 6.07 | 0.64 |
| 10| 7647 | 29.19 | 9.21 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10076 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 171 | 747 | 43.78 | 12.57 | 0.63 |
| 4 | 227 | 858 | 52.49 | 15.04 | 0.72 |
| 5 | 281 | 969 | 55.90 | 16.19 | 0.76 |
| 6 | 337 | 1081 | 67.42 | 19.34 | 0.88 |
| 7 | 394 | 1192 | 84.54 | 23.87 | 1.06 |
| 8 | 450 | 1303 | 98.91 | 27.76 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.37 | 7.71 | 0.48 |
| 2| 1957 | 25.55 | 8.72 | 0.51 |
| 3| 2065 | 27.02 | 9.79 | 0.53 |
| 5| 2364 | 31.40 | 12.34 | 0.60 |
| 10| 3179 | 41.93 | 18.62 | 0.76 |
| 40| 7543 | 94.37 | 53.22 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 602 | 22.57 | 7.30 | 0.41 |
| 2| 727 | 22.60 | 7.95 | 0.42 |
| 3| 903 | 25.14 | 9.33 | 0.46 |
| 5| 1172 | 28.01 | 11.47 | 0.51 |
| 10| 2061 | 41.02 | 18.44 | 0.71 |
| 43| 6878 | 99.38 | 56.72 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.54 | 8.47 | 0.46 |
| 2| 813 | 29.26 | 9.62 | 0.49 |
| 3| 1016 | 31.58 | 10.95 | 0.53 |
| 5| 1253 | 34.89 | 13.21 | 0.58 |
| 10| 2033 | 48.08 | 20.24 | 0.77 |
| 35| 5813 | 94.86 | 50.08 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 705 | 33.87 | 10.16 | 0.53 |
| 2| 872 | 36.60 | 11.61 | 0.57 |
| 3| 899 | 37.13 | 12.38 | 0.58 |
| 5| 1304 | 43.16 | 15.45 | 0.67 |
| 10| 2028 | 53.83 | 21.75 | 0.83 |
| 29| 4929 | 98.25 | 46.77 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5791 | 27.13 | 9.09 | 0.69 |
| 2| 5993 | 36.85 | 12.42 | 0.80 |
| 3| 6116 | 44.89 | 15.12 | 0.89 |
| 4| 6271 | 52.53 | 17.70 | 0.98 |
| 5| 6228 | 58.37 | 19.47 | 1.04 |
| 6| 6509 | 72.51 | 24.44 | 1.20 |
| 7| 6568 | 77.14 | 25.89 | 1.25 |
| 8| 6967 | 92.95 | 31.47 | 1.43 |
| 10| 6895 | 98.83 | 33.10 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6175 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2214 | 7154 | 98.49 | 37.73 | 1.53 |

