--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-21 05:48:14.02952387 UTC |
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
| 1| 5841 | 10.17 | 3.22 | 0.51 |
| 2| 6035 | 12.92 | 4.11 | 0.55 |
| 3| 6239 | 14.90 | 4.72 | 0.58 |
| 5| 6638 | 18.93 | 5.98 | 0.64 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10044 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 640 | 33.32 | 9.64 | 0.52 |
| 3 | 169 | 747 | 40.12 | 11.65 | 0.59 |
| 4 | 227 | 862 | 53.70 | 15.30 | 0.73 |
| 5 | 282 | 969 | 60.96 | 17.41 | 0.81 |
| 6 | 339 | 1085 | 65.75 | 18.97 | 0.87 |
| 7 | 396 | 1192 | 74.30 | 21.46 | 0.96 |
| 8 | 451 | 1303 | 97.89 | 27.41 | 1.20 |
| 9 | 506 | 1418 | 91.83 | 26.52 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 24.37 | 7.71 | 0.48 |
| 2| 1928 | 25.84 | 8.78 | 0.51 |
| 3| 2021 | 25.91 | 9.48 | 0.52 |
| 5| 2343 | 30.26 | 12.02 | 0.58 |
| 10| 3029 | 39.01 | 17.79 | 0.73 |
| 41| 7765 | 98.83 | 55.09 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.57 | 7.32 | 0.41 |
| 2| 767 | 24.35 | 8.48 | 0.44 |
| 3| 934 | 26.63 | 9.78 | 0.48 |
| 5| 1214 | 29.65 | 11.95 | 0.53 |
| 10| 2152 | 41.50 | 18.58 | 0.71 |
| 44| 6818 | 97.26 | 56.77 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 29.17 | 8.91 | 0.48 |
| 2| 807 | 30.98 | 10.08 | 0.51 |
| 3| 1054 | 34.18 | 11.67 | 0.56 |
| 5| 1315 | 35.68 | 13.45 | 0.59 |
| 10| 1841 | 45.45 | 19.43 | 0.74 |
| 38| 6123 | 99.21 | 53.28 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 33.83 | 10.15 | 0.53 |
| 2| 810 | 35.85 | 11.38 | 0.56 |
| 3| 942 | 37.91 | 12.62 | 0.59 |
| 5| 1203 | 41.82 | 15.03 | 0.65 |
| 10| 2018 | 53.91 | 21.77 | 0.83 |
| 29| 4970 | 99.26 | 47.08 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5815 | 26.92 | 9.04 | 0.69 |
| 2| 5992 | 37.04 | 12.48 | 0.80 |
| 3| 6102 | 44.73 | 15.03 | 0.89 |
| 4| 6300 | 56.09 | 18.92 | 1.02 |
| 5| 6469 | 64.68 | 21.81 | 1.11 |
| 6| 6624 | 73.76 | 24.88 | 1.22 |
| 7| 6628 | 79.32 | 26.61 | 1.27 |
| 8| 6876 | 85.70 | 28.79 | 1.35 |
| 9| 7002 | 98.76 | 33.21 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 22.10 | 7.52 | 0.64 |
| 10 | 10 | 568 | 6173 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6855 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2218 | 7157 | 99.38 | 38.04 | 1.54 |

