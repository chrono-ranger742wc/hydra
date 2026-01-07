--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-07 05:07:57.903500712 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6035 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 19.10 | 6.05 | 0.64 |
| 10| 7646 | 28.90 | 9.10 | 0.79 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1273 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 169 | 747 | 41.39 | 11.97 | 0.60 |
| 4 | 227 | 858 | 47.52 | 13.80 | 0.67 |
| 5 | 283 | 969 | 57.68 | 16.65 | 0.78 |
| 6 | 340 | 1081 | 67.57 | 19.41 | 0.88 |
| 7 | 393 | 1192 | 82.29 | 23.37 | 1.04 |
| 8 | 448 | 1303 | 84.90 | 24.39 | 1.07 |
| 10 | 560 | 1525 | 98.52 | 28.33 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1746 | 23.30 | 7.41 | 0.47 |
| 2| 1973 | 26.79 | 9.05 | 0.52 |
| 3| 2074 | 26.94 | 9.77 | 0.53 |
| 5| 2381 | 31.44 | 12.35 | 0.60 |
| 10| 3332 | 44.29 | 19.27 | 0.79 |
| 41| 7561 | 97.18 | 54.62 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 22.81 | 7.37 | 0.42 |
| 2| 849 | 25.47 | 8.78 | 0.46 |
| 3| 923 | 26.20 | 9.63 | 0.47 |
| 5| 1203 | 29.07 | 11.76 | 0.52 |
| 10| 2025 | 38.65 | 17.78 | 0.68 |
| 40| 6600 | 99.64 | 54.69 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 598 | 28.46 | 8.69 | 0.47 |
| 2| 808 | 30.98 | 10.08 | 0.51 |
| 3| 1061 | 32.24 | 11.16 | 0.54 |
| 5| 1436 | 37.14 | 13.89 | 0.61 |
| 10| 1976 | 46.69 | 19.82 | 0.76 |
| 34| 5709 | 94.46 | 49.29 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.87 | 10.16 | 0.53 |
| 2| 830 | 35.92 | 11.40 | 0.56 |
| 3| 946 | 37.95 | 12.63 | 0.59 |
| 5| 1293 | 42.61 | 15.27 | 0.66 |
| 10| 2100 | 55.36 | 22.21 | 0.85 |
| 29| 4717 | 95.93 | 46.10 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5790 | 27.13 | 9.11 | 0.69 |
| 2| 6015 | 36.98 | 12.45 | 0.80 |
| 3| 6136 | 45.61 | 15.39 | 0.90 |
| 4| 6375 | 55.38 | 18.73 | 1.01 |
| 5| 6440 | 64.70 | 21.88 | 1.11 |
| 6| 6617 | 72.05 | 24.24 | 1.20 |
| 7| 6708 | 82.69 | 27.81 | 1.31 |
| 8| 6752 | 84.50 | 28.36 | 1.33 |
| 9| 6823 | 90.33 | 30.28 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.07 | 6.71 | 0.62 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1138 | 6512 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1708 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 40 | 2279 | 7195 | 99.66 | 38.24 | 1.55 |
| 10 | 38 | 2162 | 7124 | 98.21 | 37.53 | 1.53 |

