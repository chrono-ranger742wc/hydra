--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-29 10:59:29.924945333 UTC |
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
| 1| 5837 | 10.85 | 3.45 | 0.52 |
| 2| 6038 | 12.63 | 4.00 | 0.55 |
| 3| 6236 | 14.67 | 4.64 | 0.58 |
| 5| 6638 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10075 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 169 | 747 | 41.01 | 11.85 | 0.60 |
| 4 | 225 | 858 | 51.17 | 14.70 | 0.71 |
| 5 | 281 | 969 | 57.83 | 16.72 | 0.78 |
| 6 | 337 | 1081 | 75.28 | 21.26 | 0.96 |
| 7 | 395 | 1192 | 80.25 | 22.84 | 1.02 |
| 8 | 451 | 1307 | 85.35 | 24.51 | 1.07 |
| 9 | 505 | 1414 | 98.80 | 28.19 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 24.29 | 7.69 | 0.48 |
| 2| 1925 | 25.84 | 8.78 | 0.51 |
| 3| 2134 | 28.43 | 10.17 | 0.55 |
| 5| 2495 | 33.19 | 12.85 | 0.62 |
| 10| 3135 | 40.63 | 18.26 | 0.75 |
| 39| 7442 | 95.61 | 52.83 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 22.81 | 7.37 | 0.42 |
| 2| 752 | 23.58 | 8.24 | 0.43 |
| 3| 853 | 23.99 | 9.01 | 0.45 |
| 5| 1151 | 28.00 | 11.47 | 0.51 |
| 10| 2238 | 44.24 | 19.34 | 0.75 |
| 41| 6438 | 93.76 | 53.77 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 26.83 | 8.26 | 0.45 |
| 2| 875 | 29.90 | 9.82 | 0.50 |
| 3| 1022 | 31.65 | 10.97 | 0.53 |
| 5| 1269 | 34.94 | 13.22 | 0.58 |
| 10| 2041 | 47.77 | 20.14 | 0.77 |
| 36| 6225 | 99.11 | 51.96 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.87 | 10.16 | 0.53 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 1027 | 38.51 | 12.80 | 0.60 |
| 5| 1255 | 42.49 | 15.24 | 0.66 |
| 10| 1914 | 52.79 | 21.41 | 0.82 |
| 29| 4775 | 96.91 | 46.36 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5819 | 27.08 | 9.08 | 0.69 |
| 2| 6017 | 36.68 | 12.37 | 0.80 |
| 3| 6041 | 42.50 | 14.27 | 0.86 |
| 4| 6260 | 55.01 | 18.56 | 1.00 |
| 5| 6555 | 65.96 | 22.34 | 1.13 |
| 6| 6502 | 69.13 | 23.23 | 1.16 |
| 7| 6612 | 82.23 | 27.68 | 1.31 |
| 8| 6505 | 75.68 | 25.29 | 1.23 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 40 | 2278 | 7195 | 99.66 | 38.24 | 1.55 |
| 10 | 38 | 2160 | 7122 | 96.88 | 37.08 | 1.51 |

