--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-09 06:39:51.518976903 UTC |
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
| 2| 6035 | 12.23 | 3.86 | 0.54 |
| 3| 6236 | 14.50 | 4.58 | 0.57 |
| 5| 6640 | 18.71 | 5.91 | 0.64 |
| 10| 7646 | 29.02 | 9.14 | 0.79 |
| 43| 14286 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 42.77 | 12.32 | 0.62 |
| 4 | 226 | 858 | 50.85 | 14.62 | 0.70 |
| 5 | 284 | 969 | 59.27 | 17.03 | 0.79 |
| 6 | 339 | 1081 | 73.19 | 20.75 | 0.94 |
| 7 | 395 | 1192 | 72.14 | 20.94 | 0.94 |
| 8 | 452 | 1303 | 90.25 | 25.78 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1800 | 24.00 | 7.62 | 0.48 |
| 2| 1969 | 26.50 | 8.99 | 0.52 |
| 3| 2175 | 28.73 | 10.26 | 0.55 |
| 5| 2390 | 31.07 | 12.26 | 0.59 |
| 10| 3097 | 40.23 | 18.13 | 0.74 |
| 42| 7513 | 94.07 | 54.41 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 22.81 | 7.37 | 0.42 |
| 2| 829 | 24.90 | 8.63 | 0.45 |
| 3| 928 | 25.02 | 9.30 | 0.46 |
| 5| 1302 | 31.04 | 12.32 | 0.55 |
| 10| 2028 | 41.00 | 18.44 | 0.70 |
| 41| 6642 | 97.93 | 54.95 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 29.13 | 8.90 | 0.48 |
| 2| 824 | 31.66 | 10.29 | 0.52 |
| 3| 980 | 33.36 | 11.43 | 0.55 |
| 5| 1302 | 37.74 | 14.00 | 0.61 |
| 10| 1971 | 44.18 | 19.15 | 0.73 |
| 36| 6107 | 98.54 | 51.82 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 33.83 | 10.15 | 0.53 |
| 2| 811 | 35.81 | 11.37 | 0.56 |
| 3| 1060 | 39.18 | 13.01 | 0.61 |
| 5| 1204 | 42.01 | 15.08 | 0.65 |
| 10| 1859 | 51.85 | 21.14 | 0.80 |
| 29| 4937 | 98.99 | 46.99 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5818 | 26.96 | 9.06 | 0.69 |
| 2| 5918 | 36.07 | 12.12 | 0.79 |
| 3| 6020 | 44.05 | 14.76 | 0.88 |
| 4| 6155 | 50.28 | 16.87 | 0.95 |
| 5| 6217 | 55.73 | 18.64 | 1.01 |
| 6| 6670 | 75.14 | 25.35 | 1.23 |
| 7| 6707 | 79.15 | 26.71 | 1.28 |
| 8| 7055 | 94.70 | 32.08 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6513 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1710 | 6857 | 81.81 | 31.06 | 1.34 |
| 10 | 38 | 2164 | 7126 | 95.11 | 36.47 | 1.50 |

