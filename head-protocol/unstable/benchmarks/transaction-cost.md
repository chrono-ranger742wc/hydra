--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-09-30 04:39:05.780347516 UTC |
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
| 1| 5834 | 10.76 | 3.42 | 0.52 |
| 2| 6041 | 12.65 | 4.01 | 0.55 |
| 3| 6236 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 29.49 | 9.31 | 0.79 |
| 43| 14282 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 640 | 32.23 | 9.37 | 0.51 |
| 3 | 170 | 747 | 40.37 | 11.74 | 0.59 |
| 4 | 227 | 858 | 50.85 | 14.60 | 0.70 |
| 5 | 281 | 974 | 56.23 | 16.33 | 0.77 |
| 6 | 337 | 1081 | 75.27 | 21.29 | 0.96 |
| 7 | 398 | 1192 | 86.38 | 24.27 | 1.08 |
| 8 | 448 | 1303 | 82.44 | 23.90 | 1.05 |
| 9 | 506 | 1414 | 89.21 | 25.94 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1790 | 24.00 | 7.62 | 0.48 |
| 2| 1935 | 25.88 | 8.79 | 0.51 |
| 3| 2087 | 27.39 | 9.88 | 0.53 |
| 5| 2332 | 29.81 | 11.91 | 0.58 |
| 10| 3298 | 43.00 | 18.91 | 0.78 |
| 41| 7485 | 95.63 | 54.16 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 22.50 | 7.30 | 0.41 |
| 2| 814 | 25.05 | 8.66 | 0.45 |
| 3| 874 | 25.09 | 9.32 | 0.46 |
| 5| 1336 | 32.45 | 12.72 | 0.56 |
| 10| 1957 | 37.62 | 17.49 | 0.67 |
| 41| 6452 | 93.61 | 53.75 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 27.47 | 8.46 | 0.46 |
| 2| 814 | 29.22 | 9.61 | 0.49 |
| 3| 914 | 32.64 | 11.21 | 0.54 |
| 5| 1265 | 35.04 | 13.25 | 0.58 |
| 10| 1958 | 46.91 | 19.89 | 0.76 |
| 35| 5960 | 95.84 | 50.37 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.79 | 10.15 | 0.53 |
| 2| 895 | 36.56 | 11.60 | 0.57 |
| 3| 985 | 38.63 | 12.83 | 0.60 |
| 5| 1355 | 44.07 | 15.71 | 0.68 |
| 10| 1942 | 52.86 | 21.43 | 0.82 |
| 29| 5010 | 99.15 | 47.03 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5799 | 27.00 | 9.06 | 0.69 |
| 2| 6036 | 36.93 | 12.45 | 0.80 |
| 3| 6013 | 41.55 | 13.92 | 0.85 |
| 4| 6164 | 50.26 | 16.82 | 0.95 |
| 5| 6396 | 60.43 | 20.34 | 1.07 |
| 6| 6616 | 71.13 | 24.07 | 1.19 |
| 7| 6646 | 79.54 | 26.72 | 1.28 |
| 8| 6836 | 93.60 | 31.50 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 39 | 2218 | 7158 | 98.93 | 37.88 | 1.54 |

