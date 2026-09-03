--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-03 09:09:19.779184776 UTC |
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
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.67 | 4.64 | 0.58 |
| 5| 6638 | 18.93 | 5.98 | 0.64 |
| 10| 7651 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 171 | 747 | 42.49 | 12.25 | 0.61 |
| 4 | 227 | 858 | 53.64 | 15.29 | 0.73 |
| 5 | 282 | 969 | 61.05 | 17.49 | 0.81 |
| 6 | 337 | 1081 | 72.18 | 20.59 | 0.93 |
| 7 | 394 | 1192 | 82.36 | 23.35 | 1.04 |
| 8 | 450 | 1303 | 82.63 | 23.85 | 1.05 |
| 9 | 509 | 1414 | 96.71 | 27.69 | 1.19 |
| 10 | 560 | 1525 | 96.88 | 28.12 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1832 | 23.92 | 7.60 | 0.48 |
| 2| 1929 | 25.92 | 8.80 | 0.51 |
| 3| 2104 | 28.09 | 10.09 | 0.54 |
| 5| 2352 | 30.45 | 12.07 | 0.59 |
| 10| 3118 | 40.39 | 18.20 | 0.75 |
| 40| 7710 | 99.58 | 54.63 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.77 | 7.36 | 0.41 |
| 2| 756 | 24.31 | 8.45 | 0.44 |
| 3| 835 | 24.13 | 9.06 | 0.45 |
| 5| 1214 | 29.12 | 11.78 | 0.52 |
| 10| 2028 | 39.62 | 18.05 | 0.69 |
| 40| 6602 | 99.77 | 54.79 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 29.13 | 8.90 | 0.48 |
| 2| 858 | 31.58 | 10.27 | 0.52 |
| 3| 949 | 30.94 | 10.75 | 0.52 |
| 5| 1226 | 36.87 | 13.74 | 0.60 |
| 10| 2200 | 47.00 | 20.01 | 0.77 |
| 34| 5959 | 97.79 | 50.31 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.79 | 10.15 | 0.53 |
| 2| 810 | 35.92 | 11.40 | 0.56 |
| 3| 970 | 37.95 | 12.63 | 0.59 |
| 5| 1203 | 41.89 | 15.05 | 0.65 |
| 10| 1987 | 53.39 | 21.60 | 0.82 |
| 29| 4701 | 96.04 | 46.10 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5811 | 26.96 | 9.05 | 0.69 |
| 2| 5924 | 34.83 | 11.66 | 0.78 |
| 3| 6000 | 44.06 | 14.79 | 0.88 |
| 4| 6239 | 51.25 | 17.26 | 0.96 |
| 5| 6384 | 61.57 | 20.74 | 1.08 |
| 6| 6515 | 69.72 | 23.47 | 1.17 |
| 7| 6758 | 83.95 | 28.33 | 1.33 |
| 8| 6865 | 91.71 | 30.86 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.15 | 7.19 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.53 | 10.50 | 0.73 |
| 10 | 20 | 1139 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1706 | 6852 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2163 | 7125 | 96.00 | 36.77 | 1.50 |

