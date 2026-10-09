--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-09 11:41:08.37602093 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6236 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 19.08 | 6.04 | 0.64 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14286 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 40.28 | 11.70 | 0.59 |
| 4 | 227 | 858 | 52.32 | 14.95 | 0.72 |
| 5 | 282 | 969 | 61.03 | 17.45 | 0.81 |
| 6 | 341 | 1081 | 63.91 | 18.53 | 0.85 |
| 7 | 393 | 1192 | 76.71 | 22.08 | 0.98 |
| 8 | 449 | 1303 | 86.72 | 24.78 | 1.09 |
| 9 | 505 | 1414 | 95.93 | 27.44 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1812 | 24.00 | 7.62 | 0.48 |
| 2| 1956 | 25.85 | 8.78 | 0.51 |
| 3| 2059 | 26.94 | 9.77 | 0.53 |
| 5| 2383 | 30.89 | 12.21 | 0.59 |
| 10| 3171 | 40.44 | 18.21 | 0.75 |
| 37| 7178 | 91.61 | 50.45 | 1.57 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 22.54 | 7.30 | 0.41 |
| 2| 824 | 25.13 | 8.69 | 0.45 |
| 3| 904 | 25.10 | 9.32 | 0.46 |
| 5| 1255 | 30.22 | 12.08 | 0.54 |
| 10| 1889 | 36.56 | 17.19 | 0.65 |
| 39| 6470 | 97.45 | 53.51 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 27.54 | 8.47 | 0.46 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 1030 | 34.06 | 11.64 | 0.55 |
| 5| 1291 | 35.72 | 13.46 | 0.59 |
| 10| 2191 | 49.34 | 20.63 | 0.79 |
| 36| 6093 | 97.47 | 51.49 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.83 | 10.15 | 0.53 |
| 2| 891 | 36.64 | 11.62 | 0.57 |
| 3| 938 | 37.91 | 12.62 | 0.59 |
| 5| 1296 | 42.53 | 15.25 | 0.66 |
| 10| 2257 | 56.59 | 22.59 | 0.87 |
| 29| 4732 | 97.24 | 46.44 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5839 | 27.08 | 9.09 | 0.69 |
| 2| 5899 | 34.94 | 11.68 | 0.78 |
| 3| 6205 | 46.92 | 15.85 | 0.92 |
| 4| 6353 | 55.64 | 18.79 | 1.01 |
| 5| 6441 | 63.95 | 21.51 | 1.11 |
| 6| 6494 | 69.42 | 23.33 | 1.17 |
| 7| 6773 | 80.76 | 27.30 | 1.30 |
| 8| 6812 | 88.53 | 29.77 | 1.38 |
| 9| 7006 | 98.92 | 33.33 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 5 | 284 | 6004 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 568 | 6172 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1140 | 6515 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6853 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2221 | 7160 | 98.05 | 37.58 | 1.53 |

