--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-21 05:31:22.293507627 UTC |
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
| 1| 5836 | 10.47 | 3.32 | 0.52 |
| 2| 6039 | 12.53 | 3.97 | 0.55 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7644 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10042 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 171 | 747 | 43.71 | 12.51 | 0.63 |
| 4 | 227 | 858 | 53.86 | 15.37 | 0.73 |
| 5 | 282 | 969 | 56.07 | 16.23 | 0.76 |
| 6 | 339 | 1081 | 75.74 | 21.45 | 0.96 |
| 7 | 395 | 1192 | 72.70 | 21.12 | 0.94 |
| 8 | 448 | 1303 | 86.85 | 24.81 | 1.09 |
| 9 | 505 | 1414 | 99.41 | 28.39 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1790 | 23.92 | 7.60 | 0.48 |
| 2| 1965 | 26.76 | 9.04 | 0.52 |
| 3| 2184 | 29.54 | 10.48 | 0.56 |
| 5| 2322 | 30.45 | 12.07 | 0.59 |
| 10| 3051 | 38.92 | 17.77 | 0.73 |
| 39| 7591 | 98.53 | 53.67 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 617 | 22.57 | 7.32 | 0.41 |
| 2| 781 | 24.05 | 8.39 | 0.44 |
| 3| 899 | 25.14 | 9.33 | 0.46 |
| 5| 1170 | 27.99 | 11.47 | 0.51 |
| 10| 2052 | 41.72 | 18.64 | 0.71 |
| 41| 6417 | 93.86 | 53.81 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 664 | 29.17 | 8.91 | 0.48 |
| 2| 820 | 29.15 | 9.59 | 0.49 |
| 3| 948 | 30.94 | 10.75 | 0.52 |
| 5| 1274 | 34.97 | 13.23 | 0.58 |
| 10| 1881 | 45.64 | 19.50 | 0.74 |
| 36| 6126 | 98.85 | 51.91 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 33.87 | 10.16 | 0.53 |
| 2| 772 | 35.14 | 11.16 | 0.55 |
| 3| 999 | 38.62 | 12.83 | 0.60 |
| 5| 1312 | 43.32 | 15.49 | 0.67 |
| 10| 1926 | 52.49 | 21.34 | 0.81 |
| 29| 4922 | 98.79 | 46.94 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 26.92 | 9.04 | 0.69 |
| 2| 5944 | 35.96 | 12.08 | 0.79 |
| 3| 6106 | 45.74 | 15.42 | 0.90 |
| 4| 6315 | 56.11 | 18.99 | 1.02 |
| 5| 6562 | 65.75 | 22.23 | 1.13 |
| 6| 6557 | 74.57 | 25.15 | 1.22 |
| 7| 6530 | 78.31 | 26.27 | 1.26 |
| 8| 6924 | 91.96 | 31.06 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 19.45 | 6.61 | 0.61 |
| 10 | 5 | 284 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 570 | 6175 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1138 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1706 | 6852 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2218 | 7157 | 97.16 | 37.28 | 1.52 |

