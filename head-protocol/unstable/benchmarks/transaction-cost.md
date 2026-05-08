--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-08 06:20:43.077766414 UTC |
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
| 1| 5834 | 10.38 | 3.29 | 0.51 |
| 2| 6042 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2168 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.33 | 9.64 | 0.52 |
| 3 | 171 | 747 | 40.05 | 11.65 | 0.59 |
| 4 | 226 | 858 | 51.97 | 14.89 | 0.72 |
| 5 | 282 | 969 | 61.09 | 17.50 | 0.81 |
| 6 | 340 | 1085 | 71.31 | 20.34 | 0.92 |
| 7 | 394 | 1192 | 82.33 | 23.34 | 1.04 |
| 8 | 451 | 1303 | 85.09 | 24.39 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1788 | 24.37 | 7.71 | 0.48 |
| 2| 1963 | 26.54 | 9.00 | 0.52 |
| 3| 2162 | 29.17 | 10.39 | 0.56 |
| 5| 2319 | 30.08 | 11.98 | 0.58 |
| 10| 3143 | 40.79 | 18.30 | 0.75 |
| 41| 7864 | 99.45 | 55.31 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.84 | 7.38 | 0.41 |
| 2| 791 | 24.96 | 8.65 | 0.45 |
| 3| 902 | 25.79 | 9.53 | 0.47 |
| 5| 1279 | 32.46 | 12.71 | 0.56 |
| 10| 1912 | 37.47 | 17.45 | 0.66 |
| 40| 6545 | 99.11 | 54.54 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 27.50 | 8.46 | 0.46 |
| 2| 816 | 31.61 | 10.27 | 0.52 |
| 3| 1096 | 32.32 | 11.18 | 0.54 |
| 5| 1374 | 39.13 | 14.42 | 0.63 |
| 10| 2030 | 45.05 | 19.42 | 0.74 |
| 34| 5825 | 95.91 | 49.71 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 704 | 33.83 | 10.15 | 0.53 |
| 2| 839 | 35.92 | 11.40 | 0.56 |
| 3| 1008 | 38.47 | 12.79 | 0.60 |
| 5| 1286 | 42.64 | 15.28 | 0.66 |
| 10| 1986 | 53.15 | 21.54 | 0.82 |
| 29| 4722 | 95.64 | 46.00 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 26.97 | 9.05 | 0.69 |
| 2| 5913 | 32.52 | 10.87 | 0.75 |
| 3| 6213 | 46.64 | 15.79 | 0.91 |
| 4| 6334 | 54.96 | 18.51 | 1.01 |
| 5| 6480 | 66.83 | 22.54 | 1.14 |
| 6| 6544 | 70.87 | 23.83 | 1.18 |
| 7| 6828 | 84.09 | 28.38 | 1.33 |
| 8| 7004 | 93.38 | 31.47 | 1.44 |
| 9| 7055 | 99.28 | 33.50 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.38 | 6.48 | 0.61 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6175 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1138 | 6513 | 59.28 | 22.29 | 1.08 |
| 10 | 30 | 1705 | 6851 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2221 | 7160 | 99.38 | 38.04 | 1.54 |

