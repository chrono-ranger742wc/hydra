--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-17 05:14:17.091265577 UTC |
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
| 1| 5836 | 11.04 | 3.52 | 0.52 |
| 2| 6038 | 12.82 | 4.07 | 0.55 |
| 3| 6243 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.88 | 5.97 | 0.64 |
| 10| 7650 | 29.11 | 9.17 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10047 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 42.25 | 12.15 | 0.61 |
| 4 | 225 | 858 | 52.31 | 14.97 | 0.72 |
| 5 | 281 | 974 | 61.13 | 17.51 | 0.81 |
| 6 | 339 | 1081 | 64.34 | 18.60 | 0.85 |
| 7 | 394 | 1192 | 84.70 | 23.91 | 1.06 |
| 8 | 450 | 1303 | 97.58 | 27.38 | 1.19 |
| 9 | 504 | 1414 | 95.98 | 27.50 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1796 | 23.92 | 7.60 | 0.48 |
| 2| 1882 | 24.80 | 8.49 | 0.49 |
| 3| 2168 | 29.13 | 10.38 | 0.56 |
| 5| 2279 | 29.37 | 11.77 | 0.57 |
| 10| 3192 | 40.70 | 18.28 | 0.75 |
| 41| 7797 | 99.11 | 55.21 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.50 | 7.29 | 0.41 |
| 2| 810 | 25.14 | 8.69 | 0.45 |
| 3| 932 | 25.07 | 9.31 | 0.46 |
| 5| 1148 | 28.03 | 11.49 | 0.51 |
| 10| 2186 | 44.23 | 19.34 | 0.74 |
| 43| 6657 | 97.72 | 56.19 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 29.09 | 8.89 | 0.48 |
| 2| 877 | 29.86 | 9.81 | 0.50 |
| 3| 988 | 33.43 | 11.44 | 0.55 |
| 5| 1323 | 35.56 | 13.42 | 0.59 |
| 10| 2151 | 46.68 | 19.93 | 0.77 |
| 35| 5669 | 94.41 | 49.88 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.16 | 0.53 |
| 2| 799 | 35.85 | 11.38 | 0.56 |
| 3| 1046 | 38.66 | 12.84 | 0.60 |
| 5| 1253 | 42.68 | 15.29 | 0.66 |
| 10| 2000 | 53.23 | 21.56 | 0.82 |
| 29| 4938 | 98.76 | 46.90 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 27.12 | 9.10 | 0.69 |
| 2| 6032 | 36.97 | 12.45 | 0.80 |
| 3| 6117 | 44.61 | 14.99 | 0.89 |
| 4| 6290 | 55.07 | 18.53 | 1.01 |
| 5| 6379 | 60.49 | 20.34 | 1.07 |
| 6| 6537 | 72.29 | 24.35 | 1.20 |
| 7| 6749 | 83.53 | 28.10 | 1.32 |
| 8| 6776 | 84.79 | 28.49 | 1.34 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 568 | 6172 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1708 | 6855 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2275 | 7191 | 99.22 | 38.09 | 1.54 |
| 10 | 39 | 2218 | 7157 | 98.93 | 37.88 | 1.54 |

