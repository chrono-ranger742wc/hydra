--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-17 05:45:05.414516187 UTC |
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
| 1| 5836 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 15.22 | 4.84 | 0.58 |
| 5| 6638 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 29.12 | 9.18 | 0.79 |
| 43| 14281 | 99.42 | 31.09 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 913 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10060 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 42.33 | 12.19 | 0.61 |
| 4 | 227 | 858 | 52.10 | 14.90 | 0.72 |
| 5 | 281 | 969 | 59.07 | 16.95 | 0.79 |
| 6 | 338 | 1081 | 66.59 | 19.22 | 0.87 |
| 7 | 393 | 1192 | 82.34 | 23.34 | 1.04 |
| 8 | 449 | 1303 | 88.78 | 25.22 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1787 | 24.00 | 7.62 | 0.48 |
| 2| 1886 | 24.77 | 8.48 | 0.49 |
| 3| 2119 | 28.47 | 10.18 | 0.55 |
| 5| 2367 | 31.19 | 12.29 | 0.60 |
| 10| 3181 | 40.70 | 18.28 | 0.75 |
| 40| 7758 | 98.83 | 54.46 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 641 | 22.54 | 7.30 | 0.41 |
| 2| 779 | 23.59 | 8.23 | 0.43 |
| 3| 967 | 27.08 | 9.89 | 0.48 |
| 5| 1204 | 30.01 | 12.03 | 0.53 |
| 10| 1864 | 36.69 | 17.23 | 0.65 |
| 42| 6644 | 97.34 | 55.43 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.50 | 8.46 | 0.46 |
| 2| 774 | 30.87 | 10.05 | 0.51 |
| 3| 907 | 30.19 | 10.53 | 0.51 |
| 5| 1219 | 34.22 | 13.00 | 0.57 |
| 10| 2051 | 44.87 | 19.36 | 0.74 |
| 37| 5926 | 97.51 | 52.11 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 666 | 33.87 | 10.16 | 0.53 |
| 2| 816 | 35.88 | 11.39 | 0.56 |
| 3| 983 | 38.63 | 12.83 | 0.60 |
| 5| 1295 | 42.57 | 15.26 | 0.66 |
| 10| 2077 | 54.92 | 22.06 | 0.84 |
| 29| 4951 | 99.36 | 47.12 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5794 | 27.09 | 9.09 | 0.69 |
| 2| 5994 | 35.88 | 12.05 | 0.79 |
| 3| 5948 | 40.43 | 13.49 | 0.84 |
| 4| 6373 | 55.49 | 18.74 | 1.01 |
| 5| 6381 | 60.32 | 20.23 | 1.06 |
| 6| 6350 | 68.05 | 22.75 | 1.14 |
| 7| 6776 | 83.51 | 28.21 | 1.33 |
| 8| 7028 | 95.51 | 32.22 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6005 | 27.58 | 9.82 | 0.71 |
| 10 | 10 | 570 | 6175 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1138 | 6513 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1708 | 6855 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2219 | 7159 | 98.93 | 37.88 | 1.54 |

