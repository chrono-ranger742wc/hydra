--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-07 05:31:51.856505589 UTC |
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
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6645 | 18.62 | 5.87 | 0.64 |
| 10| 7650 | 29.09 | 9.17 | 0.79 |
| 43| 14282 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1278 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.33 | 9.64 | 0.52 |
| 3 | 171 | 747 | 42.73 | 12.29 | 0.62 |
| 4 | 228 | 862 | 53.99 | 15.42 | 0.74 |
| 5 | 282 | 969 | 59.00 | 16.93 | 0.79 |
| 6 | 340 | 1081 | 71.82 | 20.47 | 0.93 |
| 7 | 394 | 1192 | 73.36 | 21.37 | 0.95 |
| 8 | 449 | 1307 | 87.15 | 24.89 | 1.09 |
| 9 | 505 | 1418 | 88.32 | 25.56 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1809 | 24.37 | 7.71 | 0.48 |
| 2| 1941 | 25.92 | 8.80 | 0.51 |
| 3| 2060 | 26.94 | 9.77 | 0.53 |
| 5| 2284 | 28.81 | 11.63 | 0.57 |
| 10| 3194 | 41.51 | 18.51 | 0.76 |
| 41| 7783 | 98.68 | 55.11 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.81 | 7.37 | 0.42 |
| 2| 768 | 23.59 | 8.23 | 0.43 |
| 3| 876 | 25.16 | 9.35 | 0.46 |
| 5| 1277 | 31.24 | 12.38 | 0.55 |
| 10| 1965 | 39.60 | 18.07 | 0.69 |
| 41| 6705 | 98.33 | 55.05 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 661 | 29.17 | 8.91 | 0.48 |
| 2| 812 | 30.98 | 10.08 | 0.51 |
| 3| 949 | 30.90 | 10.74 | 0.52 |
| 5| 1172 | 33.51 | 12.79 | 0.56 |
| 10| 2021 | 48.19 | 20.27 | 0.77 |
| 36| 6130 | 98.73 | 51.83 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 707 | 33.87 | 10.16 | 0.53 |
| 2| 819 | 35.92 | 11.40 | 0.56 |
| 3| 953 | 37.95 | 12.63 | 0.59 |
| 5| 1333 | 44.04 | 15.70 | 0.68 |
| 10| 1982 | 53.54 | 21.64 | 0.83 |
| 28| 4653 | 93.92 | 44.87 | 1.44 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5802 | 27.09 | 9.09 | 0.69 |
| 2| 5961 | 35.95 | 12.07 | 0.79 |
| 3| 6114 | 45.82 | 15.46 | 0.90 |
| 4| 6380 | 56.22 | 19.01 | 1.02 |
| 5| 6592 | 66.99 | 22.65 | 1.14 |
| 6| 6738 | 75.25 | 25.43 | 1.24 |
| 7| 6828 | 87.26 | 29.59 | 1.37 |
| 8| 6915 | 93.50 | 31.51 | 1.44 |
| 9| 6992 | 99.75 | 33.56 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 10 | 568 | 6173 | 39.25 | 14.36 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2220 | 7160 | 99.38 | 38.04 | 1.54 |

