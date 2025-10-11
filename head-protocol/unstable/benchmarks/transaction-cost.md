--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-11 04:38:12.73988059 UTC |
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
| 1| 5834 | 10.38 | 3.29 | 0.51 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6236 | 14.59 | 4.61 | 0.58 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 29.12 | 9.18 | 0.79 |
| 43| 14282 | 99.33 | 31.06 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 41.20 | 11.90 | 0.60 |
| 4 | 226 | 858 | 52.47 | 15.01 | 0.72 |
| 5 | 282 | 969 | 62.98 | 17.92 | 0.83 |
| 6 | 337 | 1081 | 67.72 | 19.48 | 0.89 |
| 7 | 394 | 1192 | 76.62 | 22.06 | 0.98 |
| 8 | 449 | 1303 | 88.60 | 25.49 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1819 | 24.00 | 7.62 | 0.48 |
| 2| 1884 | 24.85 | 8.50 | 0.50 |
| 3| 2157 | 28.34 | 10.15 | 0.55 |
| 5| 2463 | 31.88 | 12.49 | 0.61 |
| 10| 3146 | 40.47 | 18.22 | 0.75 |
| 41| 7766 | 99.05 | 55.18 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 646 | 22.50 | 7.30 | 0.41 |
| 2| 748 | 24.27 | 8.46 | 0.44 |
| 3| 832 | 24.09 | 9.03 | 0.45 |
| 5| 1287 | 30.00 | 12.03 | 0.54 |
| 10| 1963 | 39.62 | 18.08 | 0.69 |
| 41| 6589 | 99.12 | 55.24 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 29.13 | 8.90 | 0.48 |
| 2| 770 | 28.47 | 9.38 | 0.48 |
| 3| 1041 | 34.10 | 11.65 | 0.56 |
| 5| 1226 | 34.33 | 13.03 | 0.58 |
| 10| 1966 | 44.23 | 19.16 | 0.73 |
| 36| 5731 | 94.94 | 50.67 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.79 | 10.15 | 0.53 |
| 2| 823 | 35.85 | 11.38 | 0.56 |
| 3| 895 | 37.24 | 12.41 | 0.58 |
| 5| 1269 | 42.64 | 15.28 | 0.66 |
| 10| 2013 | 53.90 | 21.77 | 0.83 |
| 31| 5012 | 99.81 | 48.48 | 1.53 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.09 | 9.09 | 0.69 |
| 2| 5975 | 35.96 | 12.10 | 0.79 |
| 3| 5944 | 38.09 | 12.67 | 0.81 |
| 4| 6314 | 56.02 | 18.90 | 1.02 |
| 5| 6361 | 60.58 | 20.35 | 1.07 |
| 6| 6366 | 65.00 | 21.77 | 1.11 |
| 7| 6573 | 76.80 | 25.81 | 1.25 |
| 8| 6981 | 95.96 | 32.52 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 30.67 | 10.88 | 0.74 |
| 10 | 10 | 569 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2221 | 7161 | 98.05 | 37.58 | 1.53 |

