--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-16 06:14:06.844432864 UTC |
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
| 1| 5840 | 10.40 | 3.30 | 0.52 |
| 2| 6037 | 12.92 | 4.11 | 0.55 |
| 3| 6239 | 14.98 | 4.75 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2181 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 640 | 33.25 | 9.61 | 0.52 |
| 3 | 171 | 747 | 43.81 | 12.53 | 0.63 |
| 4 | 227 | 858 | 50.69 | 14.58 | 0.70 |
| 5 | 282 | 969 | 58.09 | 16.84 | 0.78 |
| 6 | 341 | 1081 | 76.28 | 21.65 | 0.97 |
| 7 | 396 | 1192 | 82.31 | 23.38 | 1.04 |
| 8 | 450 | 1303 | 97.65 | 27.61 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1810 | 24.29 | 7.69 | 0.48 |
| 2| 1929 | 25.88 | 8.79 | 0.51 |
| 3| 2017 | 25.87 | 9.47 | 0.52 |
| 5| 2410 | 31.88 | 12.49 | 0.60 |
| 10| 3288 | 43.29 | 19.02 | 0.78 |
| 39| 7525 | 96.18 | 53.08 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 634 | 22.54 | 7.30 | 0.41 |
| 2| 769 | 23.62 | 8.24 | 0.43 |
| 3| 924 | 24.99 | 9.29 | 0.46 |
| 5| 1291 | 31.25 | 12.39 | 0.55 |
| 10| 2007 | 39.88 | 18.12 | 0.69 |
| 41| 6582 | 97.23 | 54.75 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 703 | 27.54 | 8.47 | 0.46 |
| 2| 878 | 29.90 | 9.82 | 0.50 |
| 3| 953 | 30.90 | 10.74 | 0.52 |
| 5| 1135 | 35.53 | 13.33 | 0.58 |
| 10| 2030 | 44.71 | 19.32 | 0.74 |
| 36| 5945 | 97.42 | 51.46 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 700 | 33.87 | 10.16 | 0.53 |
| 2| 764 | 35.17 | 11.17 | 0.55 |
| 3| 938 | 37.84 | 12.60 | 0.59 |
| 5| 1256 | 42.49 | 15.24 | 0.66 |
| 10| 1986 | 53.46 | 21.62 | 0.83 |
| 29| 4981 | 99.50 | 47.14 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5793 | 27.00 | 9.06 | 0.69 |
| 2| 6022 | 37.05 | 12.49 | 0.80 |
| 3| 6115 | 44.52 | 14.99 | 0.89 |
| 4| 6291 | 55.90 | 18.89 | 1.01 |
| 5| 6462 | 62.75 | 21.23 | 1.09 |
| 6| 6438 | 64.24 | 21.62 | 1.11 |
| 7| 6639 | 78.71 | 26.44 | 1.27 |
| 8| 6849 | 90.53 | 30.62 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.21 | 10.04 | 0.71 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6514 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1710 | 6856 | 80.48 | 30.61 | 1.32 |
| 10 | 40 | 2278 | 7194 | 99.66 | 38.24 | 1.55 |

