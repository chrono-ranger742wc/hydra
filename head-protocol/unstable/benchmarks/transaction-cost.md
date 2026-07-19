--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-19 07:04:47.598439256 UTC |
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
| 1| 5837 | 10.40 | 3.30 | 0.51 |
| 2| 6035 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 19.00 | 6.01 | 0.64 |
| 10| 7646 | 29.00 | 9.14 | 0.79 |
| 43| 14282 | 99.32 | 31.06 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10051 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 41.34 | 11.97 | 0.60 |
| 4 | 225 | 858 | 49.72 | 14.35 | 0.69 |
| 5 | 283 | 969 | 64.17 | 18.17 | 0.84 |
| 6 | 337 | 1085 | 64.52 | 18.68 | 0.85 |
| 7 | 393 | 1192 | 87.31 | 24.62 | 1.09 |
| 8 | 449 | 1303 | 80.08 | 23.14 | 1.02 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1812 | 24.00 | 7.62 | 0.48 |
| 2| 1933 | 25.84 | 8.78 | 0.51 |
| 3| 2066 | 27.35 | 9.87 | 0.53 |
| 5| 2454 | 32.11 | 12.55 | 0.61 |
| 10| 3084 | 39.79 | 18.02 | 0.74 |
| 39| 7466 | 95.35 | 52.82 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.80 | 7.37 | 0.42 |
| 2| 703 | 22.62 | 7.96 | 0.42 |
| 3| 895 | 25.10 | 9.32 | 0.46 |
| 5| 1327 | 32.35 | 12.70 | 0.56 |
| 10| 2001 | 39.57 | 18.03 | 0.69 |
| 42| 6725 | 98.22 | 55.68 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 27.51 | 8.47 | 0.46 |
| 2| 740 | 30.23 | 9.85 | 0.50 |
| 3| 964 | 30.87 | 10.74 | 0.52 |
| 5| 1176 | 36.43 | 13.59 | 0.59 |
| 10| 1982 | 44.63 | 19.28 | 0.74 |
| 35| 5717 | 94.11 | 49.86 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.83 | 10.16 | 0.53 |
| 2| 856 | 36.60 | 11.61 | 0.57 |
| 3| 895 | 37.13 | 12.38 | 0.58 |
| 5| 1292 | 42.64 | 15.28 | 0.66 |
| 10| 2064 | 54.80 | 22.03 | 0.84 |
| 29| 5042 | 99.61 | 47.17 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 26.92 | 9.04 | 0.69 |
| 2| 5987 | 36.84 | 12.42 | 0.80 |
| 3| 6124 | 45.98 | 15.50 | 0.90 |
| 4| 6259 | 53.85 | 18.09 | 0.99 |
| 5| 6372 | 60.31 | 20.26 | 1.06 |
| 6| 6462 | 65.93 | 22.08 | 1.13 |
| 7| 6605 | 77.93 | 26.17 | 1.26 |
| 8| 6865 | 91.68 | 30.86 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1141 | 6515 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2278 | 7195 | 99.22 | 38.09 | 1.54 |
| 10 | 39 | 2223 | 7162 | 97.61 | 37.43 | 1.52 |

