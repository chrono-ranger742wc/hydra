--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-07 05:41:57.823160069 UTC |
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
| 1| 5834 | 10.48 | 3.33 | 0.52 |
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6638 | 18.84 | 5.95 | 0.64 |
| 10| 7644 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 735 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 33.40 | 9.68 | 0.52 |
| 3 | 171 | 747 | 41.39 | 11.97 | 0.60 |
| 4 | 227 | 858 | 52.43 | 15.00 | 0.72 |
| 5 | 282 | 969 | 62.39 | 17.81 | 0.83 |
| 6 | 338 | 1081 | 71.98 | 20.51 | 0.93 |
| 7 | 392 | 1196 | 86.75 | 24.44 | 1.08 |
| 8 | 449 | 1303 | 89.14 | 25.36 | 1.11 |
| 9 | 504 | 1418 | 91.43 | 26.26 | 1.14 |
| 10 | 560 | 1525 | 97.36 | 28.30 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1796 | 24.00 | 7.62 | 0.48 |
| 2| 1928 | 25.39 | 8.68 | 0.50 |
| 3| 2119 | 28.31 | 10.14 | 0.55 |
| 5| 2476 | 33.41 | 12.90 | 0.62 |
| 10| 3230 | 42.77 | 18.86 | 0.77 |
| 40| 7523 | 93.56 | 52.98 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 625 | 22.84 | 7.40 | 0.42 |
| 2| 845 | 25.14 | 8.70 | 0.45 |
| 3| 960 | 26.65 | 9.78 | 0.48 |
| 5| 1278 | 31.43 | 12.46 | 0.55 |
| 10| 1961 | 38.56 | 17.75 | 0.68 |
| 41| 6751 | 99.30 | 55.31 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 27.50 | 8.46 | 0.46 |
| 2| 842 | 31.62 | 10.28 | 0.52 |
| 3| 948 | 30.98 | 10.76 | 0.52 |
| 5| 1201 | 36.38 | 13.58 | 0.59 |
| 10| 2031 | 48.07 | 20.23 | 0.77 |
| 36| 6050 | 99.42 | 52.04 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 662 | 33.83 | 10.15 | 0.53 |
| 2| 857 | 36.48 | 11.58 | 0.57 |
| 3| 950 | 37.91 | 12.62 | 0.59 |
| 5| 1232 | 42.01 | 15.08 | 0.65 |
| 10| 2163 | 56.09 | 22.43 | 0.86 |
| 30| 4818 | 97.53 | 47.20 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 27.05 | 9.07 | 0.69 |
| 2| 5897 | 34.95 | 11.71 | 0.78 |
| 3| 6173 | 46.73 | 15.82 | 0.91 |
| 4| 6177 | 52.36 | 17.60 | 0.97 |
| 5| 6453 | 63.49 | 21.45 | 1.10 |
| 6| 6761 | 76.35 | 25.85 | 1.25 |
| 7| 6647 | 78.59 | 26.43 | 1.27 |
| 8| 6898 | 90.12 | 30.31 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 56 | 5867 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 568 | 6172 | 40.32 | 14.73 | 0.85 |
| 10 | 20 | 1140 | 6514 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1706 | 6852 | 80.67 | 30.67 | 1.32 |
| 10 | 40 | 2277 | 7193 | 99.22 | 38.09 | 1.54 |
| 10 | 39 | 2221 | 7160 | 99.38 | 38.04 | 1.54 |

