--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-08 05:27:49.606446959 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6035 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7644 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10041 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 171 | 751 | 42.61 | 12.28 | 0.62 |
| 4 | 225 | 858 | 51.46 | 14.82 | 0.71 |
| 5 | 285 | 969 | 59.26 | 17.03 | 0.79 |
| 6 | 340 | 1081 | 66.21 | 19.09 | 0.87 |
| 7 | 396 | 1192 | 78.36 | 22.39 | 1.00 |
| 8 | 450 | 1303 | 85.61 | 24.62 | 1.08 |
| 9 | 506 | 1414 | 99.47 | 28.24 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1823 | 23.92 | 7.60 | 0.48 |
| 2| 1924 | 25.84 | 8.78 | 0.51 |
| 3| 2077 | 27.39 | 9.88 | 0.53 |
| 5| 2488 | 33.48 | 12.92 | 0.62 |
| 10| 3217 | 41.48 | 18.51 | 0.76 |
| 43| 7846 | 99.17 | 56.53 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 637 | 22.81 | 7.37 | 0.42 |
| 2| 776 | 24.25 | 8.44 | 0.44 |
| 3| 932 | 26.79 | 9.82 | 0.48 |
| 5| 1223 | 30.02 | 12.05 | 0.53 |
| 10| 2065 | 40.64 | 18.35 | 0.70 |
| 39| 6211 | 91.49 | 51.78 | 1.54 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.13 | 8.90 | 0.48 |
| 2| 775 | 28.55 | 9.40 | 0.48 |
| 3| 1016 | 31.65 | 10.97 | 0.53 |
| 5| 1198 | 36.31 | 13.56 | 0.59 |
| 10| 2116 | 48.94 | 20.49 | 0.79 |
| 36| 6092 | 99.65 | 52.09 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 703 | 33.87 | 10.16 | 0.53 |
| 2| 853 | 36.60 | 11.61 | 0.57 |
| 3| 1005 | 38.59 | 12.82 | 0.60 |
| 5| 1357 | 44.03 | 15.70 | 0.68 |
| 10| 2113 | 55.18 | 22.16 | 0.85 |
| 29| 4843 | 97.79 | 46.65 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5792 | 27.13 | 9.11 | 0.69 |
| 2| 6025 | 36.97 | 12.45 | 0.80 |
| 3| 6104 | 44.83 | 15.08 | 0.89 |
| 4| 6145 | 53.31 | 17.88 | 0.98 |
| 5| 6271 | 58.78 | 19.75 | 1.04 |
| 6| 6559 | 70.35 | 23.71 | 1.18 |
| 7| 6640 | 82.39 | 27.68 | 1.31 |
| 8| 6921 | 93.48 | 31.47 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 565 | 6169 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1136 | 6510 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1709 | 6855 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2218 | 7158 | 98.05 | 37.58 | 1.53 |

