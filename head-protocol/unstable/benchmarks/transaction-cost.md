--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-08 05:44:00.105372442 UTC |
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
| 1| 5836 | 10.40 | 3.30 | 0.51 |
| 2| 6038 | 12.61 | 4.00 | 0.55 |
| 3| 6238 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 29.19 | 9.21 | 0.79 |
| 43| 14282 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 924 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10040 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 33.25 | 9.61 | 0.52 |
| 3 | 171 | 751 | 40.16 | 11.69 | 0.59 |
| 4 | 226 | 858 | 53.86 | 15.34 | 0.73 |
| 5 | 284 | 969 | 62.49 | 17.77 | 0.83 |
| 6 | 337 | 1081 | 75.23 | 21.28 | 0.96 |
| 7 | 395 | 1192 | 81.01 | 23.11 | 1.02 |
| 8 | 448 | 1307 | 81.24 | 23.62 | 1.03 |
| 9 | 506 | 1414 | 95.87 | 27.37 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1795 | 24.37 | 7.71 | 0.48 |
| 2| 2002 | 26.50 | 8.99 | 0.52 |
| 3| 2116 | 28.06 | 10.09 | 0.54 |
| 5| 2320 | 30.33 | 12.04 | 0.58 |
| 10| 3177 | 41.59 | 18.53 | 0.76 |
| 40| 7517 | 96.52 | 53.79 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.57 | 7.31 | 0.41 |
| 2| 842 | 25.17 | 8.70 | 0.45 |
| 3| 940 | 26.99 | 9.87 | 0.48 |
| 5| 1253 | 31.22 | 12.38 | 0.55 |
| 10| 2053 | 39.23 | 17.97 | 0.69 |
| 41| 6600 | 97.80 | 54.89 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.13 | 8.90 | 0.48 |
| 2| 852 | 31.62 | 10.27 | 0.52 |
| 3| 1018 | 31.65 | 10.97 | 0.53 |
| 5| 1177 | 36.31 | 13.56 | 0.59 |
| 10| 1944 | 46.61 | 19.80 | 0.76 |
| 35| 5740 | 94.10 | 49.84 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 33.83 | 10.15 | 0.53 |
| 2| 769 | 35.14 | 11.16 | 0.55 |
| 3| 958 | 37.95 | 12.63 | 0.59 |
| 5| 1408 | 43.98 | 15.69 | 0.68 |
| 10| 2030 | 53.95 | 21.78 | 0.83 |
| 29| 4951 | 98.48 | 46.85 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.08 | 9.08 | 0.69 |
| 2| 5949 | 35.76 | 12.03 | 0.79 |
| 3| 6059 | 45.18 | 15.18 | 0.89 |
| 4| 6283 | 56.26 | 18.98 | 1.02 |
| 5| 6404 | 63.59 | 21.40 | 1.10 |
| 6| 6342 | 62.99 | 21.05 | 1.09 |
| 7| 6576 | 77.96 | 26.20 | 1.26 |
| 8| 6925 | 93.40 | 31.48 | 1.44 |
| 9| 7090 | 98.59 | 33.20 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 284 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 568 | 6172 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6513 | 58.21 | 21.92 | 1.07 |
| 10 | 30 | 1711 | 6857 | 78.71 | 30.00 | 1.30 |
| 10 | 38 | 2165 | 7127 | 96.44 | 36.92 | 1.51 |

