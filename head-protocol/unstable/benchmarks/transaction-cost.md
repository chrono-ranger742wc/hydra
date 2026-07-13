--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-13 07:24:54.245605983 UTC |
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
| 1| 5837 | 10.78 | 3.43 | 0.52 |
| 2| 6042 | 12.67 | 4.01 | 0.55 |
| 3| 6236 | 14.47 | 4.57 | 0.57 |
| 5| 6641 | 18.81 | 5.94 | 0.64 |
| 10| 7647 | 29.11 | 9.17 | 0.79 |
| 43| 14281 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 171 | 747 | 43.83 | 12.55 | 0.63 |
| 4 | 225 | 858 | 49.50 | 14.30 | 0.69 |
| 5 | 283 | 974 | 56.50 | 16.43 | 0.77 |
| 6 | 341 | 1081 | 66.18 | 19.04 | 0.87 |
| 7 | 393 | 1192 | 79.06 | 22.65 | 1.00 |
| 8 | 451 | 1303 | 83.04 | 23.96 | 1.05 |
| 9 | 504 | 1414 | 91.09 | 26.28 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1806 | 24.00 | 7.62 | 0.48 |
| 2| 1955 | 25.39 | 8.68 | 0.50 |
| 3| 2109 | 28.06 | 10.09 | 0.54 |
| 5| 2378 | 31.21 | 12.29 | 0.60 |
| 10| 3084 | 39.71 | 18.00 | 0.74 |
| 42| 7823 | 99.88 | 56.08 | 1.71 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 657 | 22.81 | 7.37 | 0.42 |
| 2| 764 | 23.66 | 8.26 | 0.43 |
| 3| 894 | 25.83 | 9.54 | 0.47 |
| 5| 1142 | 28.14 | 11.51 | 0.51 |
| 10| 1961 | 37.85 | 17.56 | 0.67 |
| 41| 6658 | 98.65 | 55.15 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.17 | 8.91 | 0.48 |
| 2| 820 | 29.26 | 9.62 | 0.49 |
| 3| 980 | 30.94 | 10.75 | 0.52 |
| 5| 1178 | 36.35 | 13.57 | 0.59 |
| 10| 2002 | 44.41 | 19.22 | 0.74 |
| 33| 5567 | 92.04 | 47.95 | 1.48 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 33.83 | 10.15 | 0.53 |
| 2| 772 | 35.21 | 11.18 | 0.55 |
| 3| 1022 | 38.62 | 12.83 | 0.60 |
| 5| 1203 | 41.93 | 15.06 | 0.65 |
| 10| 2015 | 53.94 | 21.78 | 0.83 |
| 29| 4996 | 99.48 | 47.19 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5792 | 27.13 | 9.11 | 0.69 |
| 2| 5859 | 32.61 | 10.88 | 0.75 |
| 3| 6016 | 43.64 | 14.65 | 0.87 |
| 4| 6200 | 50.23 | 16.83 | 0.95 |
| 5| 6409 | 61.92 | 20.86 | 1.08 |
| 6| 6613 | 71.35 | 24.04 | 1.19 |
| 7| 6830 | 85.19 | 28.90 | 1.35 |
| 8| 6826 | 86.90 | 29.18 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 569 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6514 | 59.28 | 22.29 | 1.08 |
| 10 | 30 | 1706 | 6853 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2220 | 7159 | 98.93 | 37.88 | 1.54 |

