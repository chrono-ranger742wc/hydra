--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-10 05:43:17.780529366 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.98 | 4.75 | 0.58 |
| 5| 6640 | 18.79 | 5.94 | 0.64 |
| 10| 7648 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 563 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 924 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10072 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 171 | 747 | 41.12 | 11.90 | 0.60 |
| 4 | 226 | 858 | 53.72 | 15.31 | 0.73 |
| 5 | 280 | 969 | 59.17 | 16.97 | 0.79 |
| 6 | 341 | 1081 | 75.56 | 21.33 | 0.96 |
| 7 | 394 | 1192 | 80.53 | 22.99 | 1.02 |
| 8 | 452 | 1307 | 94.54 | 26.76 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1812 | 24.37 | 7.71 | 0.48 |
| 2| 1998 | 26.84 | 9.06 | 0.52 |
| 3| 2076 | 26.98 | 9.78 | 0.53 |
| 5| 2478 | 32.70 | 12.71 | 0.62 |
| 10| 3120 | 39.63 | 17.98 | 0.74 |
| 39| 7415 | 94.69 | 52.60 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 22.81 | 7.37 | 0.42 |
| 2| 748 | 23.61 | 8.25 | 0.43 |
| 3| 892 | 25.85 | 9.56 | 0.47 |
| 5| 1297 | 32.33 | 12.68 | 0.56 |
| 10| 1936 | 38.45 | 17.72 | 0.67 |
| 41| 6684 | 97.50 | 54.85 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 29.17 | 8.91 | 0.48 |
| 2| 814 | 30.90 | 10.06 | 0.51 |
| 3| 914 | 32.76 | 11.24 | 0.54 |
| 5| 1231 | 36.94 | 13.75 | 0.60 |
| 10| 2068 | 45.64 | 19.59 | 0.75 |
| 37| 5950 | 97.94 | 52.19 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 625 | 33.15 | 9.95 | 0.52 |
| 2| 856 | 36.64 | 11.62 | 0.57 |
| 3| 1002 | 38.59 | 12.82 | 0.60 |
| 5| 1245 | 42.68 | 15.29 | 0.66 |
| 10| 1952 | 52.79 | 21.41 | 0.82 |
| 29| 4896 | 97.92 | 46.69 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5821 | 27.12 | 9.10 | 0.69 |
| 2| 5949 | 35.93 | 12.07 | 0.79 |
| 3| 6167 | 46.00 | 15.49 | 0.90 |
| 4| 6141 | 50.45 | 16.92 | 0.95 |
| 5| 6217 | 58.24 | 19.44 | 1.03 |
| 6| 6571 | 71.13 | 23.88 | 1.19 |
| 7| 6797 | 82.17 | 27.77 | 1.31 |
| 8| 6956 | 94.31 | 31.81 | 1.45 |
| 9| 6817 | 93.51 | 31.40 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 20 | 1137 | 6511 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1708 | 6855 | 80.92 | 30.76 | 1.33 |
| 10 | 38 | 2161 | 7123 | 96.00 | 36.77 | 1.50 |

