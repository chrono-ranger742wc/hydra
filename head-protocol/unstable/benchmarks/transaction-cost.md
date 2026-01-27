--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-27 05:14:11.29484063 UTC |
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
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6240 | 14.50 | 4.58 | 0.58 |
| 5| 6641 | 18.90 | 5.97 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14286 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10047 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 169 | 747 | 42.73 | 12.29 | 0.62 |
| 4 | 227 | 862 | 53.77 | 15.32 | 0.73 |
| 5 | 281 | 969 | 61.47 | 17.59 | 0.82 |
| 6 | 338 | 1081 | 73.84 | 20.96 | 0.95 |
| 7 | 395 | 1192 | 84.54 | 23.83 | 1.06 |
| 8 | 452 | 1303 | 89.61 | 25.67 | 1.12 |
| 9 | 504 | 1414 | 96.97 | 27.75 | 1.20 |
| 10 | 560 | 1525 | 96.92 | 28.07 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1783 | 24.29 | 7.69 | 0.48 |
| 2| 1974 | 26.55 | 9.00 | 0.52 |
| 3| 2101 | 27.86 | 10.03 | 0.54 |
| 5| 2432 | 31.71 | 12.43 | 0.60 |
| 10| 3147 | 41.00 | 18.35 | 0.75 |
| 43| 7931 | 99.97 | 56.74 | 1.72 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 611 | 22.84 | 7.38 | 0.41 |
| 2| 801 | 24.25 | 8.44 | 0.44 |
| 3| 1018 | 28.00 | 10.15 | 0.49 |
| 5| 1282 | 31.27 | 12.39 | 0.55 |
| 10| 1977 | 39.78 | 18.10 | 0.69 |
| 42| 6752 | 99.76 | 56.09 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 29.17 | 8.91 | 0.48 |
| 2| 782 | 30.87 | 10.05 | 0.51 |
| 3| 946 | 32.69 | 11.22 | 0.54 |
| 5| 1334 | 38.40 | 14.20 | 0.62 |
| 10| 2004 | 44.11 | 19.13 | 0.73 |
| 36| 6103 | 98.29 | 51.75 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 705 | 33.87 | 10.16 | 0.53 |
| 2| 844 | 36.60 | 11.61 | 0.57 |
| 3| 1049 | 38.62 | 12.83 | 0.60 |
| 5| 1270 | 42.57 | 15.26 | 0.66 |
| 10| 1962 | 53.39 | 21.60 | 0.82 |
| 28| 4673 | 95.44 | 45.29 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5791 | 27.13 | 9.10 | 0.69 |
| 2| 5955 | 35.92 | 12.05 | 0.79 |
| 3| 6123 | 44.98 | 15.10 | 0.89 |
| 4| 6120 | 52.86 | 17.72 | 0.97 |
| 5| 6451 | 65.24 | 22.01 | 1.12 |
| 6| 6511 | 67.09 | 22.56 | 1.14 |
| 7| 6861 | 85.15 | 28.78 | 1.35 |
| 8| 6847 | 90.23 | 30.40 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 284 | 6003 | 29.53 | 10.50 | 0.73 |
| 10 | 20 | 1140 | 6515 | 58.21 | 21.92 | 1.07 |
| 10 | 39 | 2222 | 7162 | 99.38 | 38.04 | 1.54 |

