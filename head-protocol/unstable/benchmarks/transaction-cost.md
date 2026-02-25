--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-25 05:48:55.652656279 UTC |
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
| 1| 5840 | 10.36 | 3.28 | 0.51 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6243 | 14.79 | 4.69 | 0.58 |
| 5| 6638 | 18.60 | 5.87 | 0.63 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10074 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.40 | 9.67 | 0.52 |
| 3 | 171 | 747 | 41.46 | 11.98 | 0.60 |
| 4 | 226 | 858 | 47.72 | 13.85 | 0.67 |
| 5 | 282 | 974 | 61.42 | 17.58 | 0.82 |
| 6 | 339 | 1081 | 64.18 | 18.64 | 0.85 |
| 7 | 396 | 1192 | 75.15 | 21.71 | 0.97 |
| 8 | 450 | 1303 | 83.03 | 23.95 | 1.05 |
| 9 | 505 | 1414 | 90.47 | 26.25 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 24.37 | 7.71 | 0.48 |
| 2| 2016 | 26.58 | 9.01 | 0.52 |
| 3| 2151 | 29.54 | 10.48 | 0.56 |
| 5| 2410 | 31.97 | 12.51 | 0.60 |
| 10| 3250 | 42.97 | 18.91 | 0.78 |
| 40| 7695 | 99.40 | 54.59 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 22.54 | 7.31 | 0.41 |
| 2| 799 | 24.28 | 8.45 | 0.44 |
| 3| 865 | 24.07 | 9.03 | 0.45 |
| 5| 1247 | 30.07 | 12.05 | 0.53 |
| 10| 2071 | 40.13 | 18.22 | 0.70 |
| 43| 6853 | 99.42 | 56.68 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 29.17 | 8.91 | 0.48 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 933 | 32.80 | 11.25 | 0.54 |
| 5| 1369 | 36.20 | 13.61 | 0.60 |
| 10| 1956 | 46.88 | 19.86 | 0.76 |
| 35| 5919 | 96.19 | 50.51 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 33.87 | 10.16 | 0.53 |
| 2| 768 | 35.17 | 11.17 | 0.55 |
| 3| 904 | 37.20 | 12.40 | 0.58 |
| 5| 1309 | 43.13 | 15.44 | 0.67 |
| 10| 1972 | 53.46 | 21.62 | 0.82 |
| 28| 4548 | 93.90 | 44.83 | 1.43 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5827 | 27.05 | 9.07 | 0.69 |
| 2| 6030 | 37.16 | 12.52 | 0.81 |
| 3| 6070 | 42.45 | 14.25 | 0.86 |
| 4| 6229 | 51.06 | 17.17 | 0.96 |
| 5| 6400 | 62.94 | 21.23 | 1.09 |
| 6| 6602 | 74.75 | 25.19 | 1.23 |
| 7| 6586 | 79.03 | 26.58 | 1.27 |
| 8| 6803 | 88.31 | 29.64 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 5 | 285 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 569 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2218 | 7157 | 98.68 | 37.80 | 1.53 |

