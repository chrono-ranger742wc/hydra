--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-04 10:58:43.268915424 UTC |
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
| 1| 5837 | 10.61 | 3.37 | 0.52 |
| 2| 6038 | 12.42 | 3.93 | 0.54 |
| 3| 6239 | 14.88 | 4.72 | 0.58 |
| 5| 6641 | 19.10 | 6.05 | 0.64 |
| 10| 7651 | 29.02 | 9.14 | 0.79 |
| 43| 14279 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10082 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 171 | 747 | 42.23 | 12.15 | 0.61 |
| 4 | 228 | 858 | 51.20 | 14.73 | 0.71 |
| 5 | 282 | 974 | 63.85 | 18.09 | 0.84 |
| 6 | 339 | 1081 | 66.36 | 19.20 | 0.87 |
| 7 | 394 | 1196 | 84.65 | 23.90 | 1.06 |
| 8 | 450 | 1307 | 85.26 | 24.49 | 1.07 |
| 9 | 505 | 1418 | 98.27 | 28.00 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1787 | 24.00 | 7.62 | 0.48 |
| 2| 1990 | 26.54 | 8.99 | 0.52 |
| 3| 2143 | 28.47 | 10.18 | 0.55 |
| 5| 2321 | 29.96 | 11.95 | 0.58 |
| 10| 3118 | 41.01 | 18.35 | 0.75 |
| 39| 7437 | 95.29 | 52.81 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 665 | 22.54 | 7.31 | 0.41 |
| 2| 747 | 24.27 | 8.46 | 0.44 |
| 3| 943 | 26.87 | 9.84 | 0.48 |
| 5| 1238 | 29.04 | 11.76 | 0.52 |
| 10| 1933 | 37.66 | 17.50 | 0.67 |
| 40| 6174 | 91.00 | 52.35 | 1.53 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 27.50 | 8.46 | 0.46 |
| 2| 812 | 29.26 | 9.62 | 0.49 |
| 3| 977 | 33.47 | 11.45 | 0.55 |
| 5| 1283 | 35.01 | 13.24 | 0.59 |
| 10| 2097 | 48.16 | 20.26 | 0.78 |
| 36| 5649 | 92.93 | 50.11 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 862 | 36.52 | 11.59 | 0.57 |
| 3| 1030 | 39.22 | 13.02 | 0.61 |
| 5| 1287 | 42.72 | 15.30 | 0.66 |
| 10| 2184 | 56.05 | 22.42 | 0.86 |
| 29| 4934 | 99.66 | 47.20 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5846 | 27.00 | 9.07 | 0.69 |
| 2| 5960 | 35.87 | 12.06 | 0.79 |
| 3| 6087 | 42.50 | 14.25 | 0.86 |
| 4| 6183 | 54.15 | 18.18 | 0.99 |
| 5| 6314 | 56.59 | 18.97 | 1.02 |
| 6| 6674 | 75.07 | 25.29 | 1.23 |
| 7| 6671 | 79.75 | 26.79 | 1.28 |
| 8| 7105 | 95.26 | 32.25 | 1.46 |
| 9| 6969 | 99.08 | 33.39 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.85 | 7.43 | 0.64 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 568 | 6172 | 39.25 | 14.36 | 0.84 |
| 10 | 30 | 1708 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2212 | 7152 | 98.68 | 37.80 | 1.53 |

