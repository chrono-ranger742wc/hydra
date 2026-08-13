--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-13 06:13:38.650134145 UTC |
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
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 18.50 | 5.83 | 0.63 |
| 10| 7647 | 28.81 | 9.07 | 0.78 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10080 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 171 | 751 | 42.57 | 12.27 | 0.62 |
| 4 | 226 | 858 | 53.34 | 15.19 | 0.73 |
| 5 | 284 | 969 | 64.43 | 18.33 | 0.85 |
| 6 | 338 | 1085 | 69.23 | 19.77 | 0.90 |
| 7 | 395 | 1192 | 72.48 | 21.03 | 0.94 |
| 8 | 449 | 1303 | 93.99 | 26.58 | 1.16 |
| 9 | 508 | 1418 | 94.55 | 27.22 | 1.17 |
| 10 | 560 | 1529 | 99.81 | 28.83 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1824 | 24.37 | 7.71 | 0.48 |
| 2| 1886 | 24.40 | 8.40 | 0.49 |
| 3| 2064 | 26.98 | 9.78 | 0.53 |
| 5| 2368 | 31.48 | 12.36 | 0.60 |
| 10| 3219 | 42.10 | 18.66 | 0.77 |
| 40| 7682 | 98.24 | 54.30 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.84 | 7.38 | 0.42 |
| 2| 768 | 24.31 | 8.47 | 0.44 |
| 3| 872 | 25.78 | 9.55 | 0.47 |
| 5| 1140 | 27.99 | 11.46 | 0.51 |
| 10| 2025 | 39.84 | 18.13 | 0.69 |
| 39| 6376 | 96.35 | 53.17 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 664 | 29.13 | 8.90 | 0.48 |
| 2| 801 | 29.22 | 9.61 | 0.49 |
| 3| 948 | 30.90 | 10.74 | 0.52 |
| 5| 1360 | 38.41 | 14.20 | 0.62 |
| 10| 2078 | 44.67 | 19.31 | 0.74 |
| 36| 5989 | 97.99 | 51.62 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.87 | 10.16 | 0.53 |
| 2| 875 | 36.60 | 11.61 | 0.57 |
| 3| 938 | 37.91 | 12.62 | 0.59 |
| 5| 1207 | 41.82 | 15.03 | 0.65 |
| 10| 1972 | 53.35 | 21.59 | 0.82 |
| 29| 4824 | 98.32 | 46.77 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5787 | 27.00 | 9.06 | 0.69 |
| 2| 5940 | 35.88 | 12.05 | 0.79 |
| 3| 6085 | 45.14 | 15.18 | 0.89 |
| 4| 6115 | 46.81 | 15.61 | 0.91 |
| 5| 6381 | 64.23 | 21.66 | 1.11 |
| 6| 6665 | 74.34 | 25.16 | 1.23 |
| 7| 6587 | 77.82 | 26.10 | 1.26 |
| 8| 6898 | 91.44 | 30.83 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 284 | 6003 | 29.72 | 10.56 | 0.73 |
| 10 | 39 | 2222 | 7162 | 98.93 | 37.88 | 1.54 |

