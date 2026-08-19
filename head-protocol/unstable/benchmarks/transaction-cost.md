--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-19 05:07:51.737240388 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6039 | 12.42 | 3.93 | 0.54 |
| 3| 6236 | 14.50 | 4.58 | 0.57 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2165 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 40.00 | 11.63 | 0.59 |
| 4 | 225 | 858 | 49.68 | 14.37 | 0.69 |
| 5 | 282 | 969 | 57.60 | 16.66 | 0.78 |
| 6 | 339 | 1081 | 73.16 | 20.71 | 0.94 |
| 7 | 395 | 1192 | 76.23 | 21.96 | 0.98 |
| 8 | 449 | 1307 | 99.18 | 27.87 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1819 | 24.00 | 7.62 | 0.48 |
| 2| 1929 | 25.84 | 8.78 | 0.51 |
| 3| 2112 | 28.31 | 10.14 | 0.55 |
| 5| 2393 | 30.99 | 12.24 | 0.59 |
| 10| 3097 | 39.92 | 18.05 | 0.74 |
| 40| 7685 | 98.09 | 54.26 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 22.84 | 7.39 | 0.42 |
| 2| 766 | 24.35 | 8.47 | 0.44 |
| 3| 899 | 25.14 | 9.33 | 0.46 |
| 5| 1379 | 33.35 | 12.99 | 0.57 |
| 10| 2099 | 41.63 | 18.63 | 0.71 |
| 41| 6767 | 98.90 | 55.23 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 658 | 29.17 | 8.91 | 0.48 |
| 2| 867 | 29.86 | 9.81 | 0.50 |
| 3| 971 | 30.90 | 10.74 | 0.52 |
| 5| 1164 | 33.62 | 12.82 | 0.57 |
| 10| 1960 | 46.92 | 19.87 | 0.76 |
| 39| 6178 | 99.84 | 54.08 | 1.62 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 817 | 35.88 | 11.39 | 0.56 |
| 3| 941 | 37.88 | 12.61 | 0.59 |
| 5| 1293 | 42.68 | 15.29 | 0.66 |
| 10| 1914 | 52.71 | 21.39 | 0.81 |
| 28| 4716 | 94.72 | 45.11 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 26.96 | 9.06 | 0.69 |
| 2| 5994 | 36.93 | 12.45 | 0.80 |
| 3| 6102 | 45.04 | 15.13 | 0.89 |
| 4| 6179 | 50.71 | 16.99 | 0.95 |
| 5| 6456 | 64.97 | 21.94 | 1.12 |
| 6| 6606 | 73.60 | 24.82 | 1.21 |
| 7| 6902 | 85.72 | 29.00 | 1.36 |
| 8| 6933 | 93.46 | 31.61 | 1.44 |
| 9| 6868 | 93.57 | 31.40 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.49 | 6.17 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6174 | 40.39 | 14.75 | 0.85 |
| 10 | 30 | 1708 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 38 | 2161 | 7124 | 96.00 | 36.77 | 1.50 |

