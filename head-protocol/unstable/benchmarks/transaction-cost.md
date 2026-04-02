--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-02 06:05:49.892849233 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 13.08 | 4.16 | 0.55 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.84 | 5.95 | 0.64 |
| 10| 7644 | 29.40 | 9.28 | 0.79 |
| 43| 14279 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 640 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 39.90 | 11.59 | 0.59 |
| 4 | 226 | 858 | 51.01 | 14.64 | 0.71 |
| 5 | 281 | 969 | 57.87 | 16.73 | 0.78 |
| 6 | 338 | 1081 | 75.10 | 21.18 | 0.96 |
| 7 | 395 | 1192 | 82.66 | 23.46 | 1.04 |
| 8 | 450 | 1307 | 94.03 | 26.53 | 1.16 |
| 9 | 504 | 1414 | 92.64 | 26.59 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1829 | 23.92 | 7.60 | 0.48 |
| 2| 1992 | 26.92 | 9.08 | 0.52 |
| 3| 2069 | 27.02 | 9.79 | 0.53 |
| 5| 2395 | 31.05 | 12.25 | 0.59 |
| 10| 3222 | 42.06 | 18.65 | 0.77 |
| 40| 7445 | 95.61 | 53.51 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.57 | 7.33 | 0.41 |
| 2| 705 | 22.58 | 7.94 | 0.42 |
| 3| 885 | 25.16 | 9.34 | 0.46 |
| 5| 1286 | 30.94 | 12.31 | 0.55 |
| 10| 1963 | 39.71 | 18.09 | 0.69 |
| 41| 6571 | 95.90 | 54.37 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 654 | 29.13 | 8.90 | 0.48 |
| 2| 770 | 28.51 | 9.39 | 0.48 |
| 3| 948 | 30.90 | 10.74 | 0.52 |
| 5| 1278 | 35.01 | 13.24 | 0.58 |
| 10| 1901 | 46.01 | 19.61 | 0.75 |
| 36| 5662 | 93.30 | 50.21 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.87 | 10.16 | 0.53 |
| 2| 824 | 35.88 | 11.39 | 0.56 |
| 3| 939 | 37.91 | 12.62 | 0.59 |
| 5| 1312 | 43.39 | 15.50 | 0.67 |
| 10| 2134 | 55.14 | 22.13 | 0.85 |
| 29| 4881 | 98.49 | 46.85 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 23.01 | 7.58 | 0.64 |
| 2| 5942 | 35.96 | 12.08 | 0.79 |
| 3| 6110 | 45.74 | 15.41 | 0.90 |
| 4| 6314 | 55.67 | 18.79 | 1.01 |
| 5| 6287 | 62.46 | 20.92 | 1.08 |
| 6| 6600 | 70.62 | 23.71 | 1.18 |
| 7| 6481 | 69.33 | 23.20 | 1.16 |
| 8| 6903 | 92.29 | 31.06 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.41 | 7.28 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1707 | 6854 | 82.70 | 31.37 | 1.35 |
| 10 | 39 | 2218 | 7157 | 97.61 | 37.43 | 1.52 |

