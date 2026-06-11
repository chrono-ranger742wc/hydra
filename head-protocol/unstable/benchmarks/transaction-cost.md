--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-11 09:21:18.203803993 UTC |
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
| 1| 5837 | 10.36 | 3.28 | 0.51 |
| 2| 6038 | 13.08 | 4.16 | 0.55 |
| 3| 6238 | 14.86 | 4.71 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7644 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.33 | 9.64 | 0.52 |
| 3 | 170 | 747 | 42.45 | 12.22 | 0.61 |
| 4 | 227 | 862 | 49.58 | 14.32 | 0.69 |
| 5 | 283 | 969 | 64.11 | 18.19 | 0.84 |
| 6 | 340 | 1081 | 65.76 | 18.98 | 0.87 |
| 7 | 397 | 1192 | 85.06 | 24.08 | 1.06 |
| 8 | 449 | 1303 | 96.19 | 27.05 | 1.18 |
| 9 | 505 | 1414 | 91.73 | 26.49 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1821 | 23.92 | 7.60 | 0.48 |
| 2| 1885 | 24.47 | 8.41 | 0.49 |
| 3| 2185 | 29.05 | 10.36 | 0.56 |
| 5| 2386 | 31.42 | 12.34 | 0.60 |
| 10| 3126 | 40.71 | 18.28 | 0.75 |
| 39| 7675 | 99.44 | 53.94 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 22.81 | 7.37 | 0.42 |
| 2| 758 | 24.00 | 8.37 | 0.44 |
| 3| 942 | 26.98 | 9.87 | 0.48 |
| 5| 1190 | 28.12 | 11.50 | 0.51 |
| 10| 2026 | 40.12 | 18.22 | 0.69 |
| 41| 6552 | 98.64 | 55.16 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 29.13 | 8.90 | 0.48 |
| 2| 816 | 29.19 | 9.60 | 0.49 |
| 3| 969 | 33.47 | 11.46 | 0.55 |
| 5| 1312 | 35.64 | 13.44 | 0.59 |
| 10| 1981 | 46.77 | 19.84 | 0.76 |
| 36| 5885 | 96.52 | 51.16 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.87 | 10.16 | 0.53 |
| 2| 769 | 35.14 | 11.16 | 0.55 |
| 3| 1041 | 39.34 | 13.05 | 0.61 |
| 5| 1252 | 42.53 | 15.25 | 0.66 |
| 10| 2051 | 54.23 | 21.87 | 0.84 |
| 29| 4839 | 97.79 | 46.62 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 27.08 | 9.08 | 0.69 |
| 2| 5990 | 37.05 | 12.49 | 0.80 |
| 3| 6090 | 44.60 | 15.02 | 0.89 |
| 4| 6263 | 54.66 | 18.42 | 1.00 |
| 5| 6520 | 66.42 | 22.41 | 1.14 |
| 6| 6632 | 74.27 | 25.02 | 1.22 |
| 7| 6752 | 83.75 | 28.25 | 1.33 |
| 8| 7092 | 95.15 | 32.22 | 1.46 |
| 9| 6908 | 98.92 | 33.26 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 568 | 6172 | 37.74 | 13.85 | 0.83 |
| 10 | 20 | 1139 | 6513 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1705 | 6852 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2223 | 7163 | 98.49 | 37.73 | 1.53 |

