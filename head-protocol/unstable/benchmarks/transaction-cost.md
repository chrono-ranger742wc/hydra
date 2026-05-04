--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-04 07:03:49.66768613 UTC |
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
| 2| 6038 | 12.75 | 4.04 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 29.19 | 9.21 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 170 | 747 | 42.51 | 12.22 | 0.61 |
| 4 | 227 | 858 | 47.57 | 13.81 | 0.67 |
| 5 | 283 | 974 | 55.85 | 16.18 | 0.76 |
| 6 | 336 | 1081 | 71.93 | 20.50 | 0.93 |
| 7 | 393 | 1196 | 81.64 | 23.31 | 1.03 |
| 8 | 452 | 1303 | 87.45 | 25.06 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1752 | 22.93 | 7.32 | 0.47 |
| 2| 2009 | 26.96 | 9.09 | 0.52 |
| 3| 2126 | 28.31 | 10.14 | 0.55 |
| 5| 2436 | 32.60 | 12.67 | 0.61 |
| 10| 3038 | 38.80 | 17.74 | 0.73 |
| 40| 7453 | 96.76 | 53.83 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.81 | 7.37 | 0.42 |
| 2| 824 | 25.16 | 8.71 | 0.45 |
| 3| 857 | 24.11 | 9.04 | 0.45 |
| 5| 1166 | 28.04 | 11.48 | 0.51 |
| 10| 2070 | 40.75 | 18.37 | 0.70 |
| 42| 6699 | 99.16 | 55.93 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 29.13 | 8.90 | 0.48 |
| 2| 816 | 29.22 | 9.61 | 0.49 |
| 3| 977 | 33.32 | 11.42 | 0.54 |
| 5| 1384 | 36.55 | 13.70 | 0.61 |
| 10| 1922 | 46.84 | 19.85 | 0.76 |
| 36| 5913 | 96.77 | 51.22 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 33.15 | 9.95 | 0.52 |
| 2| 761 | 35.21 | 11.18 | 0.55 |
| 3| 1022 | 38.62 | 12.83 | 0.60 |
| 5| 1247 | 42.53 | 15.25 | 0.66 |
| 10| 2090 | 55.64 | 22.28 | 0.85 |
| 31| 4890 | 98.77 | 48.15 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5828 | 27.12 | 9.10 | 0.69 |
| 2| 5987 | 36.92 | 12.46 | 0.80 |
| 3| 6018 | 41.37 | 13.84 | 0.85 |
| 4| 6238 | 53.93 | 18.08 | 0.99 |
| 5| 6303 | 57.03 | 19.09 | 1.03 |
| 6| 6466 | 67.25 | 22.62 | 1.14 |
| 7| 6779 | 82.44 | 27.91 | 1.32 |
| 8| 6743 | 81.91 | 27.52 | 1.31 |
| 9| 6981 | 98.70 | 33.24 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 568 | 6172 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1709 | 6855 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2218 | 7157 | 97.61 | 37.43 | 1.52 |

