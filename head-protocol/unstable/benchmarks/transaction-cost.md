--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-10 08:09:28.989921228 UTC |
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
| 1| 5836 | 10.57 | 3.36 | 0.52 |
| 2| 6041 | 12.44 | 3.94 | 0.54 |
| 3| 6238 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 18.60 | 5.87 | 0.64 |
| 10| 7644 | 28.81 | 9.07 | 0.78 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10039 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 639 | 32.24 | 9.37 | 0.51 |
| 3 | 171 | 747 | 43.64 | 12.50 | 0.63 |
| 4 | 225 | 858 | 54.16 | 15.47 | 0.74 |
| 5 | 284 | 974 | 57.92 | 16.74 | 0.78 |
| 6 | 338 | 1081 | 71.43 | 20.30 | 0.92 |
| 7 | 392 | 1192 | 75.28 | 21.79 | 0.97 |
| 8 | 451 | 1303 | 83.67 | 24.26 | 1.06 |
| 9 | 504 | 1414 | 98.89 | 28.20 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 24.29 | 7.69 | 0.48 |
| 2| 1924 | 25.81 | 8.77 | 0.51 |
| 3| 2104 | 28.51 | 10.19 | 0.55 |
| 5| 2448 | 33.10 | 12.83 | 0.62 |
| 10| 2998 | 37.48 | 17.38 | 0.71 |
| 41| 7736 | 97.53 | 54.74 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 22.77 | 7.36 | 0.42 |
| 2| 807 | 25.17 | 8.70 | 0.45 |
| 3| 907 | 25.09 | 9.33 | 0.46 |
| 5| 1141 | 28.14 | 11.50 | 0.51 |
| 10| 1898 | 37.34 | 17.41 | 0.66 |
| 41| 6600 | 96.96 | 54.70 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 658 | 29.09 | 8.89 | 0.48 |
| 2| 778 | 28.51 | 9.39 | 0.48 |
| 3| 998 | 31.65 | 10.97 | 0.53 |
| 5| 1134 | 35.53 | 13.33 | 0.58 |
| 10| 2041 | 44.59 | 19.27 | 0.74 |
| 37| 5949 | 97.18 | 51.98 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.79 | 10.15 | 0.53 |
| 2| 869 | 36.64 | 11.62 | 0.57 |
| 3| 896 | 37.24 | 12.41 | 0.58 |
| 5| 1286 | 42.60 | 15.27 | 0.66 |
| 10| 2103 | 54.88 | 22.05 | 0.85 |
| 28| 5099 | 99.65 | 46.61 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5808 | 26.92 | 9.04 | 0.69 |
| 2| 5826 | 31.52 | 10.49 | 0.74 |
| 3| 6148 | 45.76 | 15.43 | 0.90 |
| 4| 6312 | 54.73 | 18.49 | 1.00 |
| 5| 6593 | 66.21 | 22.41 | 1.14 |
| 6| 6561 | 72.86 | 24.53 | 1.20 |
| 7| 6712 | 84.04 | 28.38 | 1.33 |
| 8| 6800 | 88.89 | 29.92 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.41 | 7.28 | 0.63 |
| 10 | 5 | 284 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 569 | 6173 | 40.32 | 14.73 | 0.85 |
| 10 | 20 | 1136 | 6511 | 60.61 | 22.74 | 1.09 |
| 10 | 30 | 1707 | 6854 | 79.15 | 30.16 | 1.31 |
| 10 | 38 | 2162 | 7124 | 96.88 | 37.08 | 1.51 |

