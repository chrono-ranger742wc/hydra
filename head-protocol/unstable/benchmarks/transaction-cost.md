--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-18 05:07:25.814647835 UTC |
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
| 1| 5837 | 10.86 | 3.46 | 0.52 |
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.72 | 4.66 | 0.58 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 42.55 | 12.23 | 0.62 |
| 4 | 228 | 858 | 52.44 | 14.98 | 0.72 |
| 5 | 283 | 969 | 59.75 | 17.21 | 0.80 |
| 6 | 339 | 1081 | 66.31 | 19.11 | 0.87 |
| 7 | 396 | 1192 | 86.56 | 24.40 | 1.08 |
| 8 | 449 | 1303 | 93.42 | 26.39 | 1.15 |
| 9 | 506 | 1414 | 98.96 | 28.17 | 1.22 |
| 10 | 561 | 1525 | 96.52 | 27.92 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1814 | 23.92 | 7.60 | 0.48 |
| 2| 1935 | 25.92 | 8.80 | 0.51 |
| 3| 2110 | 28.09 | 10.09 | 0.54 |
| 5| 2321 | 30.38 | 12.05 | 0.58 |
| 10| 3068 | 40.11 | 18.10 | 0.74 |
| 43| 7954 | 99.28 | 56.61 | 1.71 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.50 | 7.29 | 0.41 |
| 2| 816 | 25.33 | 8.74 | 0.45 |
| 3| 903 | 25.10 | 9.32 | 0.46 |
| 5| 1149 | 28.18 | 11.51 | 0.51 |
| 10| 2072 | 40.44 | 18.28 | 0.70 |
| 42| 6665 | 99.95 | 56.15 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 664 | 29.09 | 8.89 | 0.48 |
| 2| 788 | 30.98 | 10.08 | 0.51 |
| 3| 915 | 32.69 | 11.22 | 0.54 |
| 5| 1383 | 35.72 | 13.46 | 0.60 |
| 10| 2126 | 45.79 | 19.64 | 0.76 |
| 36| 5859 | 95.11 | 50.75 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.12 | 9.94 | 0.52 |
| 2| 857 | 36.60 | 11.61 | 0.57 |
| 3| 946 | 37.91 | 12.62 | 0.59 |
| 5| 1344 | 43.13 | 15.44 | 0.67 |
| 10| 2095 | 54.92 | 22.08 | 0.85 |
| 30| 4822 | 97.23 | 47.08 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5789 | 27.00 | 9.08 | 0.69 |
| 2| 5971 | 35.99 | 12.08 | 0.79 |
| 3| 6032 | 41.41 | 13.86 | 0.85 |
| 4| 6087 | 46.90 | 15.64 | 0.91 |
| 5| 6413 | 64.13 | 21.62 | 1.11 |
| 6| 6581 | 74.54 | 25.07 | 1.22 |
| 7| 6729 | 83.79 | 28.19 | 1.33 |
| 8| 6871 | 92.27 | 31.07 | 1.42 |
| 9| 7145 | 98.11 | 33.06 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 570 | 6175 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2219 | 7158 | 98.49 | 37.73 | 1.53 |

