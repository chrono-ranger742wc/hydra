--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-06 05:35:54.184979005 UTC |
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
| 1| 5834 | 10.61 | 3.37 | 0.52 |
| 2| 6035 | 12.46 | 3.94 | 0.54 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 19.17 | 6.07 | 0.64 |
| 10| 7648 | 29.12 | 9.18 | 0.79 |
| 43| 14279 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 41.11 | 11.88 | 0.60 |
| 4 | 227 | 858 | 49.41 | 14.27 | 0.69 |
| 5 | 284 | 969 | 64.48 | 18.25 | 0.85 |
| 6 | 339 | 1085 | 74.37 | 21.16 | 0.95 |
| 7 | 394 | 1192 | 86.33 | 24.34 | 1.08 |
| 8 | 448 | 1303 | 83.26 | 24.06 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1799 | 23.92 | 7.60 | 0.48 |
| 2| 1886 | 24.81 | 8.49 | 0.49 |
| 3| 2057 | 27.02 | 9.79 | 0.53 |
| 5| 2490 | 32.27 | 12.59 | 0.61 |
| 10| 3366 | 46.01 | 19.76 | 0.81 |
| 41| 7656 | 98.28 | 54.92 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.57 | 7.31 | 0.41 |
| 2| 851 | 25.53 | 8.79 | 0.46 |
| 3| 882 | 25.47 | 9.46 | 0.46 |
| 5| 1171 | 28.15 | 11.51 | 0.51 |
| 10| 1943 | 38.19 | 17.67 | 0.67 |
| 39| 6229 | 92.80 | 52.19 | 1.55 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 664 | 29.13 | 8.90 | 0.48 |
| 2| 845 | 31.69 | 10.29 | 0.52 |
| 3| 952 | 30.94 | 10.75 | 0.52 |
| 5| 1308 | 38.45 | 14.21 | 0.62 |
| 10| 2027 | 44.97 | 19.39 | 0.74 |
| 35| 5617 | 93.76 | 49.72 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.87 | 10.16 | 0.53 |
| 2| 810 | 35.85 | 11.38 | 0.56 |
| 3| 1027 | 38.62 | 12.83 | 0.60 |
| 5| 1265 | 42.72 | 15.30 | 0.66 |
| 10| 2027 | 53.79 | 21.74 | 0.83 |
| 29| 4974 | 99.89 | 47.29 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.05 | 9.07 | 0.69 |
| 2| 5945 | 35.96 | 12.06 | 0.79 |
| 3| 6024 | 43.85 | 14.68 | 0.88 |
| 4| 6210 | 50.48 | 16.90 | 0.95 |
| 5| 6519 | 64.65 | 21.82 | 1.12 |
| 6| 6497 | 70.00 | 23.59 | 1.17 |
| 7| 6787 | 82.42 | 27.79 | 1.32 |
| 8| 6957 | 92.66 | 31.26 | 1.43 |
| 9| 6916 | 98.14 | 33.01 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1140 | 6515 | 59.10 | 22.22 | 1.07 |
| 10 | 39 | 2221 | 7160 | 99.12 | 37.95 | 1.54 |

