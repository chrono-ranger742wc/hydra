--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-12 06:18:35.972894831 UTC |
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
| 1| 5837 | 10.59 | 3.36 | 0.52 |
| 2| 6037 | 12.34 | 3.90 | 0.54 |
| 3| 6242 | 14.72 | 4.66 | 0.58 |
| 5| 6638 | 18.83 | 5.95 | 0.64 |
| 10| 7644 | 29.14 | 9.19 | 0.79 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10072 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 42.72 | 12.29 | 0.62 |
| 4 | 227 | 858 | 49.72 | 14.35 | 0.69 |
| 5 | 281 | 974 | 64.57 | 18.30 | 0.85 |
| 6 | 339 | 1081 | 69.53 | 19.88 | 0.90 |
| 7 | 393 | 1196 | 73.08 | 21.22 | 0.95 |
| 8 | 448 | 1303 | 85.30 | 24.54 | 1.07 |
| 9 | 507 | 1414 | 96.52 | 27.69 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1805 | 23.92 | 7.60 | 0.48 |
| 2| 1929 | 25.81 | 8.77 | 0.51 |
| 3| 2153 | 28.38 | 10.16 | 0.55 |
| 5| 2349 | 30.16 | 12.00 | 0.58 |
| 10| 3268 | 42.67 | 18.84 | 0.77 |
| 39| 7509 | 95.95 | 52.98 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.84 | 7.38 | 0.41 |
| 2| 756 | 23.62 | 8.23 | 0.43 |
| 3| 865 | 24.07 | 9.03 | 0.45 |
| 5| 1154 | 28.07 | 11.49 | 0.51 |
| 10| 2005 | 41.45 | 18.56 | 0.71 |
| 41| 6590 | 96.30 | 54.50 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 650 | 29.17 | 8.91 | 0.48 |
| 2| 812 | 29.22 | 9.61 | 0.49 |
| 3| 1028 | 34.11 | 11.65 | 0.56 |
| 5| 1338 | 38.38 | 14.19 | 0.62 |
| 10| 2071 | 48.19 | 20.27 | 0.78 |
| 36| 6018 | 98.65 | 51.81 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 33.83 | 10.15 | 0.53 |
| 2| 901 | 36.52 | 11.59 | 0.57 |
| 3| 1051 | 39.26 | 13.03 | 0.61 |
| 5| 1270 | 42.53 | 15.25 | 0.66 |
| 10| 2022 | 53.94 | 21.78 | 0.83 |
| 28| 4914 | 97.99 | 46.10 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5825 | 27.12 | 9.10 | 0.69 |
| 2| 5945 | 35.96 | 12.07 | 0.79 |
| 3| 6045 | 45.11 | 15.14 | 0.89 |
| 4| 6385 | 55.39 | 18.75 | 1.01 |
| 5| 6307 | 56.97 | 19.09 | 1.03 |
| 6| 6661 | 74.04 | 24.95 | 1.22 |
| 7| 6623 | 76.72 | 25.79 | 1.25 |
| 8| 6933 | 94.37 | 31.83 | 1.45 |
| 9| 6916 | 97.65 | 32.88 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.49 | 6.17 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 10 | 569 | 6173 | 38.81 | 14.21 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2223 | 7163 | 98.05 | 37.58 | 1.53 |

