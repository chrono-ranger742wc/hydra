--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-22 06:24:13.295865259 UTC |
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
| 1| 5834 | 10.19 | 3.22 | 0.51 |
| 2| 6039 | 12.61 | 4.00 | 0.55 |
| 3| 6236 | 14.72 | 4.66 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.81 | 9.07 | 0.78 |
| 43| 14279 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2182 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 170 | 747 | 41.51 | 12.00 | 0.60 |
| 4 | 227 | 858 | 52.44 | 15.00 | 0.72 |
| 5 | 281 | 969 | 59.51 | 17.09 | 0.80 |
| 6 | 338 | 1081 | 74.85 | 21.15 | 0.96 |
| 7 | 397 | 1192 | 80.32 | 22.86 | 1.02 |
| 8 | 449 | 1303 | 80.60 | 23.37 | 1.03 |
| 9 | 504 | 1418 | 88.50 | 25.60 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1783 | 24.29 | 7.69 | 0.48 |
| 2| 1966 | 26.92 | 9.08 | 0.52 |
| 3| 2127 | 27.94 | 10.05 | 0.54 |
| 5| 2455 | 31.87 | 12.49 | 0.61 |
| 10| 3248 | 43.15 | 18.97 | 0.78 |
| 39| 7635 | 99.68 | 54.02 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 619 | 22.84 | 7.38 | 0.42 |
| 2| 778 | 23.63 | 8.24 | 0.43 |
| 3| 945 | 26.12 | 9.62 | 0.47 |
| 5| 1167 | 28.47 | 11.63 | 0.52 |
| 10| 1926 | 37.65 | 17.50 | 0.67 |
| 41| 6664 | 97.80 | 54.89 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 27.54 | 8.47 | 0.46 |
| 2| 815 | 30.87 | 10.05 | 0.51 |
| 3| 955 | 30.90 | 10.74 | 0.52 |
| 5| 1172 | 36.43 | 13.59 | 0.59 |
| 10| 1950 | 44.30 | 19.18 | 0.73 |
| 36| 5972 | 99.20 | 51.96 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 33.87 | 10.16 | 0.53 |
| 2| 815 | 35.88 | 11.39 | 0.56 |
| 3| 942 | 37.88 | 12.61 | 0.59 |
| 5| 1158 | 41.22 | 14.85 | 0.64 |
| 10| 2125 | 54.92 | 22.06 | 0.85 |
| 28| 4878 | 98.67 | 46.27 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 23.01 | 7.58 | 0.64 |
| 2| 5917 | 34.83 | 11.66 | 0.78 |
| 3| 6162 | 46.04 | 15.50 | 0.91 |
| 4| 6262 | 55.16 | 18.57 | 1.01 |
| 5| 6359 | 59.91 | 20.18 | 1.06 |
| 6| 6565 | 72.60 | 24.44 | 1.20 |
| 7| 6635 | 82.39 | 27.71 | 1.31 |
| 8| 6828 | 89.42 | 30.05 | 1.39 |
| 9| 6911 | 95.56 | 32.04 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1138 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1704 | 6851 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2164 | 7126 | 96.88 | 37.08 | 1.51 |

