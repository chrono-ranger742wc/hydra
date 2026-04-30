--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-30 06:49:57.959470154 UTC |
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
| 1| 5837 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.63 | 4.00 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 19.08 | 6.04 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14285 | 99.02 | 30.95 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 170 | 747 | 40.12 | 11.65 | 0.59 |
| 4 | 226 | 858 | 50.71 | 14.56 | 0.70 |
| 5 | 283 | 969 | 61.45 | 17.56 | 0.82 |
| 6 | 338 | 1081 | 72.53 | 20.72 | 0.93 |
| 7 | 396 | 1192 | 72.86 | 21.20 | 0.94 |
| 8 | 450 | 1303 | 96.35 | 27.24 | 1.18 |
| 10 | 560 | 1525 | 99.25 | 28.57 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.29 | 7.69 | 0.48 |
| 2| 1936 | 25.47 | 8.70 | 0.50 |
| 3| 2013 | 26.28 | 9.57 | 0.52 |
| 5| 2418 | 31.00 | 12.24 | 0.60 |
| 10| 3147 | 40.78 | 18.30 | 0.75 |
| 41| 7651 | 97.80 | 54.82 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 22.81 | 7.37 | 0.42 |
| 2| 698 | 22.55 | 7.93 | 0.42 |
| 3| 924 | 25.45 | 9.45 | 0.46 |
| 5| 1184 | 29.10 | 11.79 | 0.52 |
| 10| 2092 | 42.17 | 18.76 | 0.72 |
| 42| 6856 | 99.12 | 55.93 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.17 | 8.91 | 0.48 |
| 2| 794 | 30.91 | 10.06 | 0.51 |
| 3| 949 | 30.98 | 10.76 | 0.52 |
| 5| 1169 | 33.70 | 12.84 | 0.57 |
| 10| 2068 | 45.64 | 19.59 | 0.75 |
| 36| 5918 | 97.12 | 51.35 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 873 | 36.48 | 11.58 | 0.57 |
| 3| 1053 | 39.23 | 13.02 | 0.61 |
| 5| 1227 | 41.82 | 15.03 | 0.65 |
| 10| 1993 | 53.12 | 21.53 | 0.82 |
| 29| 4965 | 99.26 | 47.08 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 26.96 | 9.05 | 0.69 |
| 2| 6003 | 37.05 | 12.47 | 0.80 |
| 3| 6115 | 42.49 | 14.25 | 0.87 |
| 4| 6264 | 54.77 | 18.46 | 1.00 |
| 5| 6337 | 62.86 | 21.13 | 1.09 |
| 6| 6637 | 74.60 | 25.21 | 1.23 |
| 7| 6547 | 78.51 | 26.37 | 1.26 |
| 8| 6868 | 92.97 | 31.40 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6174 | 40.13 | 14.67 | 0.85 |
| 10 | 20 | 1138 | 6513 | 61.31 | 22.98 | 1.10 |
| 10 | 30 | 1705 | 6852 | 80.48 | 30.61 | 1.32 |
| 10 | 35 | 1991 | 7022 | 89.59 | 34.26 | 1.43 |

