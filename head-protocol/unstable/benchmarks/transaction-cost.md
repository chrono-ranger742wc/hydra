--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-16 06:26:19.332239077 UTC |
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
| 1| 5836 | 10.93 | 3.49 | 0.52 |
| 2| 6035 | 12.67 | 4.01 | 0.55 |
| 3| 6243 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 19.08 | 6.04 | 0.64 |
| 10| 7644 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10048 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 170 | 747 | 40.20 | 11.68 | 0.59 |
| 4 | 227 | 858 | 53.82 | 15.31 | 0.73 |
| 5 | 283 | 969 | 59.76 | 17.21 | 0.80 |
| 6 | 337 | 1081 | 72.73 | 20.61 | 0.93 |
| 7 | 394 | 1192 | 74.50 | 21.47 | 0.96 |
| 8 | 448 | 1303 | 96.82 | 27.30 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1749 | 23.30 | 7.41 | 0.47 |
| 2| 1938 | 25.55 | 8.71 | 0.50 |
| 3| 2059 | 27.47 | 9.90 | 0.53 |
| 5| 2390 | 31.29 | 12.31 | 0.60 |
| 10| 3078 | 39.55 | 17.96 | 0.73 |
| 38| 7295 | 94.07 | 51.79 | 1.60 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 22.81 | 7.37 | 0.42 |
| 2| 792 | 24.32 | 8.46 | 0.44 |
| 3| 929 | 26.60 | 9.76 | 0.48 |
| 5| 1208 | 29.08 | 11.77 | 0.52 |
| 10| 2029 | 40.46 | 18.29 | 0.70 |
| 42| 6761 | 98.83 | 55.83 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 27.54 | 8.47 | 0.46 |
| 2| 792 | 30.98 | 10.08 | 0.51 |
| 3| 910 | 30.19 | 10.53 | 0.51 |
| 5| 1315 | 35.72 | 13.46 | 0.59 |
| 10| 2025 | 44.48 | 19.24 | 0.74 |
| 35| 5933 | 96.38 | 50.52 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 810 | 35.85 | 11.38 | 0.56 |
| 3| 988 | 38.51 | 12.80 | 0.60 |
| 5| 1373 | 43.54 | 15.56 | 0.67 |
| 10| 2081 | 54.85 | 22.04 | 0.84 |
| 30| 4985 | 98.76 | 47.58 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5833 | 26.96 | 9.06 | 0.69 |
| 2| 5971 | 36.97 | 12.46 | 0.80 |
| 3| 6097 | 44.72 | 15.04 | 0.89 |
| 4| 6121 | 49.21 | 16.42 | 0.94 |
| 5| 6523 | 66.45 | 22.50 | 1.14 |
| 6| 6425 | 64.75 | 21.62 | 1.11 |
| 7| 6817 | 85.84 | 28.98 | 1.35 |
| 8| 6693 | 87.46 | 29.34 | 1.36 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6005 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6174 | 40.13 | 14.67 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2223 | 7162 | 99.82 | 38.19 | 1.55 |

