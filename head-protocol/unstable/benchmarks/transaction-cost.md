--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-18 05:36:18.046803837 UTC |
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
| 1| 5838 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6238 | 14.84 | 4.71 | 0.58 |
| 5| 6638 | 18.81 | 5.94 | 0.64 |
| 10| 7644 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 170 | 747 | 41.12 | 11.88 | 0.60 |
| 4 | 226 | 858 | 49.43 | 14.26 | 0.69 |
| 5 | 283 | 969 | 56.05 | 16.26 | 0.76 |
| 6 | 340 | 1081 | 73.34 | 20.76 | 0.94 |
| 7 | 393 | 1192 | 81.08 | 23.09 | 1.02 |
| 8 | 451 | 1303 | 94.26 | 26.64 | 1.16 |
| 9 | 505 | 1418 | 94.51 | 27.21 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1749 | 23.30 | 7.41 | 0.47 |
| 2| 1926 | 25.84 | 8.78 | 0.51 |
| 3| 2114 | 28.43 | 10.17 | 0.55 |
| 5| 2330 | 30.04 | 11.97 | 0.58 |
| 10| 3140 | 41.53 | 18.50 | 0.76 |
| 38| 7292 | 95.40 | 52.19 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 606 | 22.84 | 7.37 | 0.41 |
| 2| 838 | 25.37 | 8.76 | 0.46 |
| 3| 967 | 28.07 | 10.16 | 0.49 |
| 5| 1332 | 31.23 | 12.37 | 0.55 |
| 10| 2018 | 38.77 | 17.81 | 0.68 |
| 41| 6673 | 98.28 | 55.09 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 29.13 | 8.90 | 0.48 |
| 2| 851 | 31.65 | 10.28 | 0.52 |
| 3| 996 | 33.43 | 11.44 | 0.55 |
| 5| 1311 | 37.74 | 14.00 | 0.61 |
| 10| 1938 | 46.92 | 19.87 | 0.76 |
| 36| 5891 | 95.23 | 50.82 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 33.87 | 10.16 | 0.53 |
| 2| 824 | 35.92 | 11.40 | 0.56 |
| 3| 896 | 37.24 | 12.41 | 0.58 |
| 5| 1256 | 42.65 | 15.28 | 0.66 |
| 10| 2062 | 54.81 | 22.03 | 0.84 |
| 29| 4913 | 97.83 | 46.63 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5795 | 27.13 | 9.10 | 0.69 |
| 2| 5945 | 35.76 | 12.03 | 0.79 |
| 3| 6055 | 44.73 | 15.04 | 0.89 |
| 4| 6216 | 50.26 | 16.83 | 0.95 |
| 5| 6331 | 59.45 | 19.93 | 1.05 |
| 6| 6535 | 68.25 | 22.89 | 1.15 |
| 7| 6808 | 84.49 | 28.54 | 1.34 |
| 8| 6817 | 91.63 | 30.83 | 1.41 |
| 9| 6871 | 96.69 | 32.52 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 10 | 568 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1708 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 38 | 2160 | 7122 | 97.51 | 37.29 | 1.52 |

