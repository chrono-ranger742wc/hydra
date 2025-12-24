--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-24 05:47:08.537300483 UTC |
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
| 2| 6037 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6641 | 19.34 | 6.13 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 112 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 170 | 747 | 39.94 | 11.60 | 0.59 |
| 4 | 227 | 858 | 49.80 | 14.42 | 0.69 |
| 5 | 283 | 969 | 61.35 | 17.53 | 0.82 |
| 6 | 338 | 1085 | 71.01 | 20.20 | 0.92 |
| 7 | 396 | 1192 | 76.14 | 21.81 | 0.98 |
| 8 | 449 | 1303 | 85.87 | 24.73 | 1.08 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 23.92 | 7.60 | 0.48 |
| 2| 1928 | 25.55 | 8.71 | 0.50 |
| 3| 2084 | 27.36 | 9.87 | 0.53 |
| 5| 2363 | 31.03 | 12.25 | 0.59 |
| 10| 3193 | 42.12 | 18.66 | 0.77 |
| 42| 7682 | 98.10 | 55.59 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.84 | 7.40 | 0.42 |
| 2| 816 | 25.57 | 8.80 | 0.46 |
| 3| 925 | 26.86 | 9.83 | 0.48 |
| 5| 1200 | 29.81 | 11.98 | 0.53 |
| 10| 1974 | 38.70 | 17.79 | 0.68 |
| 40| 6734 | 99.16 | 54.61 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 703 | 27.54 | 8.47 | 0.46 |
| 2| 824 | 31.70 | 10.30 | 0.52 |
| 3| 940 | 32.76 | 11.24 | 0.54 |
| 5| 1262 | 37.58 | 13.95 | 0.61 |
| 10| 2095 | 48.20 | 20.27 | 0.78 |
| 38| 5953 | 97.01 | 52.56 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 33.15 | 9.95 | 0.52 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 997 | 38.63 | 12.83 | 0.60 |
| 5| 1332 | 43.13 | 15.44 | 0.67 |
| 10| 2047 | 54.78 | 22.02 | 0.84 |
| 29| 4779 | 96.77 | 46.32 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5845 | 27.05 | 9.08 | 0.69 |
| 2| 5976 | 37.00 | 12.46 | 0.80 |
| 3| 6211 | 46.91 | 15.84 | 0.92 |
| 4| 6320 | 55.27 | 18.63 | 1.01 |
| 5| 6393 | 62.90 | 21.14 | 1.09 |
| 6| 6504 | 69.40 | 23.42 | 1.17 |
| 7| 6796 | 84.33 | 28.40 | 1.34 |
| 8| 6855 | 87.11 | 29.37 | 1.37 |
| 9| 7030 | 97.77 | 33.00 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2218 | 7158 | 98.49 | 37.73 | 1.53 |

