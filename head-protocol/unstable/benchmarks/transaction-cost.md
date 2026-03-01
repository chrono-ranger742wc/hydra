--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-01 05:43:50.624651729 UTC |
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
| 1| 5837 | 10.38 | 3.29 | 0.51 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6643 | 18.84 | 5.95 | 0.64 |
| 10| 7650 | 29.00 | 9.14 | 0.79 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10046 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 41.24 | 11.91 | 0.60 |
| 4 | 228 | 858 | 48.12 | 13.94 | 0.68 |
| 5 | 283 | 969 | 56.31 | 16.35 | 0.77 |
| 6 | 338 | 1081 | 75.22 | 21.28 | 0.96 |
| 7 | 395 | 1192 | 84.93 | 24.05 | 1.06 |
| 8 | 450 | 1303 | 93.79 | 26.62 | 1.16 |
| 9 | 505 | 1414 | 93.82 | 26.93 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1811 | 24.00 | 7.62 | 0.48 |
| 2| 1925 | 25.76 | 8.76 | 0.51 |
| 3| 2114 | 28.23 | 10.12 | 0.54 |
| 5| 2373 | 31.25 | 12.30 | 0.60 |
| 10| 3223 | 42.15 | 18.67 | 0.77 |
| 41| 7778 | 97.95 | 54.89 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 22.81 | 7.37 | 0.42 |
| 2| 767 | 23.65 | 8.25 | 0.43 |
| 3| 996 | 26.96 | 9.86 | 0.48 |
| 5| 1324 | 32.42 | 12.71 | 0.56 |
| 10| 1936 | 38.22 | 17.68 | 0.67 |
| 40| 6672 | 99.46 | 54.68 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 641 | 29.17 | 8.91 | 0.48 |
| 2| 774 | 30.98 | 10.08 | 0.51 |
| 3| 946 | 32.68 | 11.22 | 0.54 |
| 5| 1230 | 34.33 | 13.03 | 0.58 |
| 10| 2129 | 46.26 | 19.78 | 0.76 |
| 36| 5777 | 94.63 | 50.61 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 704 | 33.87 | 10.16 | 0.53 |
| 2| 855 | 36.64 | 11.62 | 0.57 |
| 3| 1052 | 39.30 | 13.04 | 0.61 |
| 5| 1249 | 42.57 | 15.26 | 0.66 |
| 10| 2076 | 54.92 | 22.06 | 0.84 |
| 30| 4945 | 99.79 | 47.84 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.08 | 9.08 | 0.69 |
| 2| 6014 | 37.05 | 12.48 | 0.80 |
| 3| 6025 | 43.77 | 14.66 | 0.87 |
| 4| 6308 | 55.02 | 18.51 | 1.01 |
| 5| 6232 | 58.17 | 19.52 | 1.04 |
| 6| 6499 | 69.60 | 23.39 | 1.17 |
| 7| 6836 | 81.95 | 27.69 | 1.31 |
| 8| 6899 | 92.68 | 31.31 | 1.43 |
| 9| 6787 | 89.16 | 29.79 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 22.10 | 7.52 | 0.64 |
| 10 | 10 | 569 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6854 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2220 | 7160 | 98.49 | 37.73 | 1.53 |

