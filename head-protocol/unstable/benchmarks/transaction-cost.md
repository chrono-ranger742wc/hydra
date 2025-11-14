--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-14 05:34:30.939469676 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6239 | 14.48 | 4.58 | 0.57 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 29.11 | 9.17 | 0.79 |
| 43| 14279 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10072 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 58 | 526 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 169 | 747 | 41.40 | 11.95 | 0.60 |
| 4 | 227 | 858 | 47.91 | 13.89 | 0.68 |
| 5 | 283 | 969 | 59.21 | 16.98 | 0.79 |
| 6 | 339 | 1081 | 71.63 | 20.39 | 0.92 |
| 7 | 393 | 1192 | 72.41 | 21.01 | 0.94 |
| 8 | 450 | 1303 | 93.39 | 26.33 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.00 | 7.62 | 0.48 |
| 2| 1929 | 25.85 | 8.78 | 0.51 |
| 3| 2129 | 28.35 | 10.15 | 0.55 |
| 5| 2492 | 33.11 | 12.83 | 0.62 |
| 10| 3129 | 39.88 | 18.04 | 0.74 |
| 38| 7432 | 97.13 | 52.63 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 22.50 | 7.29 | 0.41 |
| 2| 752 | 24.27 | 8.44 | 0.44 |
| 3| 912 | 25.10 | 9.32 | 0.46 |
| 5| 1285 | 31.14 | 12.36 | 0.55 |
| 10| 2111 | 43.73 | 19.17 | 0.73 |
| 40| 6718 | 99.74 | 54.79 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 691 | 27.51 | 8.47 | 0.46 |
| 2| 774 | 28.55 | 9.40 | 0.48 |
| 3| 995 | 33.44 | 11.45 | 0.55 |
| 5| 1434 | 37.10 | 13.88 | 0.61 |
| 10| 2098 | 45.65 | 19.59 | 0.75 |
| 34| 5645 | 99.58 | 50.66 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.79 | 10.15 | 0.53 |
| 2| 764 | 35.14 | 11.16 | 0.55 |
| 3| 1044 | 39.26 | 13.03 | 0.61 |
| 5| 1203 | 41.97 | 15.07 | 0.65 |
| 10| 2084 | 54.73 | 22.01 | 0.84 |
| 30| 4939 | 99.78 | 47.82 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 26.97 | 9.07 | 0.69 |
| 2| 6034 | 36.89 | 12.44 | 0.80 |
| 3| 6117 | 42.14 | 14.16 | 0.86 |
| 4| 6352 | 56.08 | 18.89 | 1.02 |
| 5| 6405 | 64.09 | 21.53 | 1.11 |
| 6| 6458 | 66.03 | 22.11 | 1.13 |
| 7| 6489 | 74.10 | 24.84 | 1.21 |
| 8| 6794 | 90.13 | 30.22 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 57 | 5868 | 20.52 | 6.98 | 0.62 |
| 10 | 5 | 285 | 6004 | 27.58 | 9.82 | 0.71 |
| 10 | 10 | 571 | 6175 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1140 | 6515 | 58.21 | 21.92 | 1.07 |
| 10 | 30 | 1706 | 6852 | 79.15 | 30.16 | 1.31 |
| 10 | 40 | 2276 | 7192 | 99.22 | 38.09 | 1.54 |

