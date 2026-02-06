--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-06 05:52:28.353566609 UTC |
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
| 1| 5837 | 10.40 | 3.30 | 0.51 |
| 2| 6042 | 12.23 | 3.86 | 0.54 |
| 3| 6236 | 14.67 | 4.64 | 0.58 |
| 5| 6646 | 19.26 | 6.10 | 0.64 |
| 10| 7647 | 29.00 | 9.14 | 0.79 |
| 43| 14286 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 171 | 747 | 42.55 | 12.23 | 0.62 |
| 4 | 227 | 858 | 50.94 | 14.64 | 0.71 |
| 5 | 283 | 969 | 55.94 | 16.20 | 0.76 |
| 6 | 337 | 1081 | 66.52 | 19.20 | 0.87 |
| 7 | 395 | 1192 | 78.55 | 22.44 | 1.00 |
| 8 | 452 | 1303 | 91.56 | 25.99 | 1.13 |
| 9 | 505 | 1414 | 96.52 | 27.64 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1786 | 24.37 | 7.71 | 0.48 |
| 2| 1886 | 24.40 | 8.39 | 0.49 |
| 3| 2013 | 26.36 | 9.59 | 0.52 |
| 5| 2352 | 29.97 | 11.95 | 0.58 |
| 10| 3191 | 40.59 | 18.25 | 0.75 |
| 40| 7231 | 92.18 | 52.56 | 1.59 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 598 | 22.80 | 7.36 | 0.41 |
| 2| 747 | 24.08 | 8.41 | 0.44 |
| 3| 918 | 25.52 | 9.47 | 0.47 |
| 5| 1253 | 30.17 | 12.09 | 0.54 |
| 10| 1858 | 36.31 | 17.12 | 0.65 |
| 42| 6574 | 95.33 | 54.89 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 27.51 | 8.47 | 0.46 |
| 2| 840 | 29.19 | 9.60 | 0.49 |
| 3| 1010 | 31.54 | 10.94 | 0.53 |
| 5| 1270 | 34.94 | 13.22 | 0.58 |
| 10| 2033 | 45.13 | 19.42 | 0.74 |
| 38| 6157 | 99.48 | 53.29 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.83 | 10.16 | 0.53 |
| 2| 842 | 35.85 | 11.38 | 0.56 |
| 3| 984 | 38.58 | 12.82 | 0.60 |
| 5| 1303 | 42.49 | 15.24 | 0.66 |
| 10| 1986 | 53.49 | 21.63 | 0.83 |
| 29| 5009 | 99.67 | 47.18 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5796 | 27.00 | 9.08 | 0.69 |
| 2| 5868 | 32.57 | 10.88 | 0.75 |
| 3| 6110 | 44.69 | 15.02 | 0.89 |
| 4| 6297 | 54.69 | 18.45 | 1.00 |
| 5| 6395 | 62.48 | 20.98 | 1.09 |
| 6| 6602 | 73.70 | 24.90 | 1.22 |
| 7| 6613 | 81.15 | 27.25 | 1.29 |
| 8| 6796 | 88.18 | 29.66 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6005 | 28.65 | 10.19 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6854 | 79.34 | 30.22 | 1.31 |
| 10 | 39 | 2221 | 7160 | 98.05 | 37.58 | 1.53 |

