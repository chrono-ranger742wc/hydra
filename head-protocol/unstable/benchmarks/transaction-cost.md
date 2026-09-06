--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-06 08:55:48.312864579 UTC |
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
| 3| 6236 | 14.50 | 4.58 | 0.57 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 29.40 | 9.28 | 0.79 |
| 43| 14282 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10064 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 170 | 747 | 42.62 | 12.26 | 0.62 |
| 4 | 227 | 858 | 54.02 | 15.41 | 0.74 |
| 5 | 282 | 969 | 64.61 | 18.31 | 0.85 |
| 6 | 337 | 1081 | 72.29 | 20.66 | 0.93 |
| 7 | 397 | 1192 | 86.22 | 24.35 | 1.07 |
| 8 | 449 | 1303 | 87.75 | 25.18 | 1.10 |
| 9 | 505 | 1414 | 88.50 | 25.60 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 24.29 | 7.69 | 0.48 |
| 2| 1928 | 25.84 | 8.78 | 0.51 |
| 3| 2156 | 28.46 | 10.18 | 0.55 |
| 5| 2367 | 31.37 | 12.33 | 0.60 |
| 10| 3133 | 40.50 | 18.23 | 0.75 |
| 40| 7644 | 99.08 | 54.51 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 622 | 22.84 | 7.39 | 0.42 |
| 2| 780 | 24.32 | 8.46 | 0.44 |
| 3| 915 | 25.06 | 9.31 | 0.46 |
| 5| 1358 | 31.85 | 12.56 | 0.56 |
| 10| 2180 | 44.43 | 19.38 | 0.74 |
| 40| 6557 | 95.74 | 53.71 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 29.17 | 8.91 | 0.48 |
| 2| 786 | 30.87 | 10.05 | 0.51 |
| 3| 975 | 30.98 | 10.76 | 0.52 |
| 5| 1198 | 36.20 | 13.53 | 0.59 |
| 10| 2135 | 49.54 | 20.68 | 0.79 |
| 35| 5960 | 96.65 | 50.63 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 33.87 | 10.16 | 0.53 |
| 2| 852 | 36.56 | 11.60 | 0.57 |
| 3| 899 | 37.20 | 12.40 | 0.58 |
| 5| 1306 | 43.25 | 15.47 | 0.67 |
| 10| 2068 | 54.88 | 22.05 | 0.84 |
| 29| 4934 | 98.49 | 46.83 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5833 | 27.05 | 9.08 | 0.69 |
| 2| 5992 | 36.92 | 12.45 | 0.80 |
| 3| 6003 | 44.00 | 14.72 | 0.88 |
| 4| 6216 | 54.08 | 18.17 | 0.99 |
| 5| 6486 | 66.58 | 22.45 | 1.14 |
| 6| 6707 | 76.09 | 25.72 | 1.25 |
| 7| 6611 | 79.56 | 26.73 | 1.28 |
| 8| 6867 | 89.59 | 30.19 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 284 | 6003 | 29.79 | 10.58 | 0.73 |
| 10 | 39 | 2217 | 7156 | 99.38 | 38.04 | 1.54 |

