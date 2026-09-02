--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-02 08:59:37.922843631 UTC |
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
| 2| 6035 | 12.91 | 4.10 | 0.55 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6638 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14279 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 171 | 751 | 40.09 | 11.66 | 0.59 |
| 4 | 226 | 858 | 51.03 | 14.67 | 0.71 |
| 5 | 283 | 969 | 59.31 | 17.04 | 0.79 |
| 6 | 339 | 1081 | 70.91 | 20.37 | 0.92 |
| 7 | 394 | 1192 | 74.46 | 21.46 | 0.96 |
| 8 | 448 | 1303 | 84.82 | 24.33 | 1.07 |
| 9 | 506 | 1418 | 91.76 | 26.50 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1788 | 24.37 | 7.71 | 0.48 |
| 2| 1884 | 24.40 | 8.40 | 0.49 |
| 3| 2186 | 29.17 | 10.39 | 0.56 |
| 5| 2320 | 30.26 | 12.02 | 0.58 |
| 10| 3143 | 41.00 | 18.35 | 0.75 |
| 41| 7643 | 98.58 | 55.04 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 611 | 22.57 | 7.30 | 0.41 |
| 2| 743 | 23.62 | 8.23 | 0.43 |
| 3| 903 | 25.01 | 9.31 | 0.46 |
| 5| 1282 | 31.14 | 12.36 | 0.55 |
| 10| 1926 | 37.72 | 17.51 | 0.67 |
| 40| 6478 | 99.99 | 54.77 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 27.54 | 8.47 | 0.46 |
| 2| 820 | 29.22 | 9.61 | 0.49 |
| 3| 872 | 31.97 | 11.00 | 0.53 |
| 5| 1308 | 37.77 | 14.00 | 0.61 |
| 10| 2130 | 45.38 | 19.52 | 0.75 |
| 36| 6013 | 97.54 | 51.53 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 33.87 | 10.16 | 0.53 |
| 2| 862 | 36.56 | 11.60 | 0.57 |
| 3| 945 | 37.91 | 12.62 | 0.59 |
| 5| 1311 | 43.57 | 15.57 | 0.67 |
| 10| 2046 | 54.20 | 21.84 | 0.84 |
| 29| 5031 | 99.41 | 47.14 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5818 | 27.09 | 9.09 | 0.69 |
| 2| 5926 | 35.96 | 12.09 | 0.79 |
| 3| 6030 | 43.71 | 14.67 | 0.87 |
| 4| 6271 | 56.25 | 18.95 | 1.02 |
| 5| 6499 | 64.87 | 21.88 | 1.12 |
| 6| 6534 | 74.21 | 25.01 | 1.22 |
| 7| 6797 | 83.07 | 28.01 | 1.32 |
| 8| 6986 | 94.69 | 31.95 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 20 | 1139 | 6513 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1705 | 6851 | 80.92 | 30.76 | 1.33 |
| 10 | 38 | 2165 | 7127 | 97.51 | 37.29 | 1.52 |

