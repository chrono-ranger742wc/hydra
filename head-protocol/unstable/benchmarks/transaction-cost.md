--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-18 05:51:03.367889444 UTC |
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
| 1| 5841 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.63 | 4.00 | 0.55 |
| 3| 6243 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 29.19 | 9.21 | 0.79 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 170 | 747 | 42.44 | 12.22 | 0.61 |
| 4 | 226 | 862 | 50.90 | 14.61 | 0.70 |
| 5 | 282 | 969 | 63.97 | 18.12 | 0.84 |
| 6 | 336 | 1081 | 73.78 | 20.97 | 0.95 |
| 7 | 393 | 1192 | 77.44 | 22.31 | 0.99 |
| 8 | 450 | 1303 | 82.98 | 23.94 | 1.05 |
| 9 | 506 | 1414 | 97.69 | 27.74 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1994 | 26.55 | 9.00 | 0.52 |
| 3| 2133 | 27.94 | 10.05 | 0.54 |
| 5| 2427 | 32.57 | 12.66 | 0.61 |
| 10| 3038 | 38.44 | 17.65 | 0.72 |
| 40| 7585 | 98.07 | 54.22 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 634 | 22.80 | 7.39 | 0.42 |
| 2| 776 | 23.51 | 8.21 | 0.43 |
| 3| 979 | 26.93 | 9.85 | 0.48 |
| 5| 1243 | 31.29 | 12.39 | 0.55 |
| 10| 1956 | 38.46 | 17.72 | 0.67 |
| 41| 6395 | 93.57 | 53.75 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 27.51 | 8.47 | 0.46 |
| 2| 827 | 29.15 | 9.59 | 0.49 |
| 3| 940 | 32.68 | 11.22 | 0.54 |
| 5| 1288 | 37.66 | 13.98 | 0.61 |
| 10| 2090 | 48.12 | 20.25 | 0.78 |
| 35| 5787 | 99.90 | 51.38 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.79 | 10.15 | 0.53 |
| 2| 769 | 35.14 | 11.16 | 0.55 |
| 3| 1011 | 38.59 | 12.82 | 0.60 |
| 5| 1209 | 41.82 | 15.03 | 0.65 |
| 10| 2012 | 54.09 | 21.82 | 0.83 |
| 28| 4523 | 93.36 | 44.68 | 1.43 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5818 | 27.00 | 9.07 | 0.69 |
| 2| 5961 | 35.88 | 12.07 | 0.79 |
| 3| 6192 | 45.72 | 15.43 | 0.90 |
| 4| 6218 | 51.22 | 17.23 | 0.96 |
| 5| 6418 | 60.40 | 20.25 | 1.07 |
| 6| 6388 | 65.58 | 21.95 | 1.12 |
| 7| 6496 | 73.78 | 24.68 | 1.21 |
| 8| 6794 | 85.72 | 28.90 | 1.35 |
| 9| 6759 | 89.32 | 29.86 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 56 | 5868 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 285 | 6004 | 27.14 | 9.67 | 0.70 |
| 10 | 10 | 570 | 6175 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1137 | 6511 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6853 | 79.60 | 30.31 | 1.31 |
| 10 | 37 | 2109 | 7094 | 95.28 | 36.42 | 1.49 |

