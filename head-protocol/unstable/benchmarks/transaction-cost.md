--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-26 05:44:53.496553077 UTC |
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
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6236 | 14.50 | 4.58 | 0.57 |
| 5| 6641 | 19.02 | 6.02 | 0.64 |
| 10| 7647 | 29.02 | 9.14 | 0.79 |
| 43| 14282 | 98.85 | 30.89 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 170 | 747 | 42.33 | 12.19 | 0.61 |
| 4 | 228 | 858 | 53.82 | 15.33 | 0.73 |
| 5 | 284 | 974 | 60.07 | 17.29 | 0.80 |
| 6 | 339 | 1081 | 71.78 | 20.46 | 0.93 |
| 7 | 394 | 1192 | 84.09 | 23.80 | 1.05 |
| 8 | 450 | 1303 | 83.84 | 24.30 | 1.06 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 23.92 | 7.60 | 0.48 |
| 2| 1928 | 25.39 | 8.68 | 0.50 |
| 3| 2057 | 27.35 | 9.87 | 0.53 |
| 5| 2337 | 29.84 | 11.92 | 0.58 |
| 10| 3066 | 39.59 | 17.97 | 0.73 |
| 40| 7830 | 99.53 | 54.67 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 22.84 | 7.39 | 0.42 |
| 2| 772 | 24.05 | 8.39 | 0.44 |
| 3| 902 | 25.14 | 9.33 | 0.46 |
| 5| 1165 | 27.93 | 11.45 | 0.51 |
| 10| 2018 | 39.57 | 18.04 | 0.69 |
| 41| 6534 | 98.04 | 54.97 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 27.50 | 8.46 | 0.46 |
| 2| 776 | 30.98 | 10.08 | 0.51 |
| 3| 944 | 30.90 | 10.74 | 0.52 |
| 5| 1392 | 36.32 | 13.64 | 0.60 |
| 10| 2058 | 45.09 | 19.41 | 0.75 |
| 35| 5821 | 94.91 | 50.08 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.87 | 10.16 | 0.53 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 987 | 38.55 | 12.81 | 0.60 |
| 5| 1266 | 42.65 | 15.28 | 0.66 |
| 10| 1817 | 51.25 | 20.95 | 0.80 |
| 30| 5010 | 99.68 | 47.85 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 27.08 | 9.08 | 0.69 |
| 2| 5953 | 35.85 | 12.03 | 0.79 |
| 3| 6070 | 44.57 | 15.03 | 0.89 |
| 4| 6364 | 56.14 | 18.96 | 1.02 |
| 5| 6464 | 63.98 | 21.61 | 1.11 |
| 6| 6579 | 74.62 | 25.16 | 1.22 |
| 7| 6702 | 83.41 | 28.14 | 1.32 |
| 8| 6740 | 86.57 | 29.12 | 1.36 |
| 9| 6900 | 99.36 | 33.38 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 57 | 5868 | 21.15 | 7.19 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2163 | 7126 | 96.88 | 37.08 | 1.51 |

