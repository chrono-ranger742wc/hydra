--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-15 05:51:24.679272433 UTC |
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
| 1| 5841 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.63 | 4.00 | 0.55 |
| 3| 6243 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10077 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 528 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 170 | 747 | 42.45 | 12.24 | 0.61 |
| 4 | 227 | 858 | 53.73 | 15.34 | 0.73 |
| 5 | 281 | 969 | 64.89 | 18.42 | 0.85 |
| 6 | 337 | 1081 | 71.85 | 20.44 | 0.93 |
| 7 | 394 | 1192 | 84.62 | 23.93 | 1.06 |
| 8 | 451 | 1303 | 82.67 | 23.82 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1803 | 24.00 | 7.62 | 0.48 |
| 2| 1938 | 25.47 | 8.69 | 0.50 |
| 3| 2113 | 27.93 | 10.05 | 0.54 |
| 5| 2455 | 32.03 | 12.53 | 0.61 |
| 10| 3129 | 41.46 | 18.48 | 0.76 |
| 40| 7658 | 99.70 | 54.66 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 615 | 22.84 | 7.37 | 0.41 |
| 2| 745 | 23.62 | 8.24 | 0.43 |
| 3| 907 | 25.14 | 9.33 | 0.46 |
| 5| 1386 | 33.64 | 13.04 | 0.58 |
| 10| 1981 | 38.84 | 17.83 | 0.68 |
| 40| 6319 | 92.35 | 52.73 | 1.55 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 699 | 27.54 | 8.47 | 0.46 |
| 2| 888 | 29.94 | 9.83 | 0.50 |
| 3| 945 | 32.68 | 11.22 | 0.54 |
| 5| 1305 | 34.94 | 13.22 | 0.59 |
| 10| 2084 | 48.74 | 20.44 | 0.78 |
| 34| 5729 | 94.98 | 49.44 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.87 | 10.16 | 0.53 |
| 2| 811 | 35.92 | 11.40 | 0.56 |
| 3| 964 | 37.91 | 12.62 | 0.59 |
| 5| 1199 | 41.78 | 15.02 | 0.65 |
| 10| 2084 | 54.92 | 22.06 | 0.84 |
| 29| 4856 | 96.56 | 46.29 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5809 | 27.05 | 9.07 | 0.69 |
| 2| 6016 | 37.09 | 12.51 | 0.80 |
| 3| 6069 | 44.91 | 15.09 | 0.89 |
| 4| 6301 | 54.71 | 18.47 | 1.00 |
| 5| 6445 | 64.37 | 21.65 | 1.11 |
| 6| 6686 | 74.34 | 25.18 | 1.23 |
| 7| 6867 | 82.53 | 27.82 | 1.32 |
| 8| 6720 | 85.29 | 28.62 | 1.34 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 285 | 6005 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2220 | 7159 | 98.93 | 37.88 | 1.54 |

