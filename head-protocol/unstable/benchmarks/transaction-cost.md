--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-31 05:49:32.299777783 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6035 | 12.73 | 4.04 | 0.55 |
| 3| 6238 | 14.47 | 4.57 | 0.57 |
| 5| 6638 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10078 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 168 | 747 | 42.85 | 12.34 | 0.62 |
| 4 | 226 | 858 | 49.56 | 14.34 | 0.69 |
| 5 | 281 | 974 | 58.02 | 16.77 | 0.78 |
| 6 | 338 | 1081 | 65.85 | 19.03 | 0.87 |
| 7 | 392 | 1192 | 73.85 | 21.31 | 0.95 |
| 8 | 451 | 1303 | 91.43 | 25.86 | 1.13 |
| 9 | 506 | 1414 | 93.56 | 26.82 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.29 | 7.69 | 0.48 |
| 2| 1935 | 25.92 | 8.80 | 0.51 |
| 3| 2130 | 28.23 | 10.12 | 0.55 |
| 5| 2375 | 31.42 | 12.34 | 0.60 |
| 10| 3229 | 42.73 | 18.87 | 0.77 |
| 41| 7789 | 98.58 | 55.04 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 615 | 22.80 | 7.37 | 0.41 |
| 2| 722 | 22.52 | 7.93 | 0.42 |
| 3| 985 | 26.02 | 9.58 | 0.47 |
| 5| 1195 | 28.39 | 11.61 | 0.52 |
| 10| 1960 | 38.89 | 17.84 | 0.68 |
| 40| 6526 | 97.10 | 54.09 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 27.47 | 8.46 | 0.46 |
| 2| 838 | 29.22 | 9.61 | 0.49 |
| 3| 1029 | 34.22 | 11.68 | 0.56 |
| 5| 1230 | 37.09 | 13.79 | 0.60 |
| 10| 2116 | 46.14 | 19.75 | 0.76 |
| 37| 5873 | 95.47 | 51.51 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.83 | 10.16 | 0.53 |
| 2| 806 | 35.92 | 11.40 | 0.56 |
| 3| 993 | 38.51 | 12.80 | 0.60 |
| 5| 1270 | 42.68 | 15.29 | 0.66 |
| 10| 2176 | 55.30 | 22.19 | 0.85 |
| 30| 4915 | 99.86 | 47.87 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5831 | 27.00 | 9.07 | 0.69 |
| 2| 5895 | 34.95 | 11.69 | 0.78 |
| 3| 6041 | 41.51 | 13.90 | 0.85 |
| 4| 6324 | 55.03 | 18.55 | 1.01 |
| 5| 6403 | 64.00 | 21.56 | 1.10 |
| 6| 6598 | 72.43 | 24.39 | 1.20 |
| 7| 6894 | 84.17 | 28.39 | 1.34 |
| 8| 6731 | 87.62 | 29.37 | 1.37 |
| 9| 6818 | 90.34 | 30.32 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 284 | 6003 | 28.02 | 9.98 | 0.71 |
| 10 | 20 | 1137 | 6512 | 60.17 | 22.59 | 1.09 |
| 10 | 40 | 2278 | 7194 | 99.66 | 38.24 | 1.55 |

