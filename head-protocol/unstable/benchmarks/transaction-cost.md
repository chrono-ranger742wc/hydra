--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-26 05:32:49.65517138 UTC |
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
| 1| 5838 | 10.47 | 3.32 | 0.52 |
| 2| 6038 | 12.72 | 4.03 | 0.55 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 29.49 | 9.31 | 0.79 |
| 43| 14279 | 99.32 | 31.06 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 556 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1271 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 171 | 747 | 43.75 | 12.55 | 0.63 |
| 4 | 228 | 858 | 52.40 | 15.02 | 0.72 |
| 5 | 284 | 974 | 56.92 | 16.46 | 0.77 |
| 6 | 340 | 1081 | 64.05 | 18.53 | 0.85 |
| 7 | 396 | 1192 | 84.26 | 23.80 | 1.06 |
| 8 | 449 | 1303 | 90.87 | 25.72 | 1.13 |
| 10 | 560 | 1525 | 99.37 | 28.54 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1800 | 24.00 | 7.62 | 0.48 |
| 2| 1968 | 26.91 | 9.08 | 0.52 |
| 3| 2017 | 26.24 | 9.56 | 0.52 |
| 5| 2389 | 31.01 | 12.24 | 0.59 |
| 10| 3349 | 44.34 | 19.28 | 0.79 |
| 42| 7740 | 98.13 | 55.59 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.81 | 7.37 | 0.42 |
| 2| 805 | 25.16 | 8.71 | 0.45 |
| 3| 858 | 23.99 | 9.01 | 0.45 |
| 5| 1210 | 29.94 | 12.03 | 0.53 |
| 10| 1896 | 38.10 | 17.64 | 0.67 |
| 41| 6643 | 98.10 | 55.01 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 29.17 | 8.91 | 0.48 |
| 2| 803 | 30.90 | 10.06 | 0.51 |
| 3| 956 | 33.31 | 11.41 | 0.54 |
| 5| 1234 | 36.95 | 13.76 | 0.60 |
| 10| 1965 | 46.62 | 19.80 | 0.76 |
| 36| 6084 | 98.54 | 51.78 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 33.87 | 10.16 | 0.53 |
| 2| 873 | 36.60 | 11.61 | 0.57 |
| 3| 942 | 37.80 | 12.59 | 0.59 |
| 5| 1289 | 43.24 | 15.46 | 0.67 |
| 10| 2105 | 55.13 | 22.15 | 0.85 |
| 29| 4838 | 97.26 | 46.47 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5793 | 27.04 | 9.08 | 0.69 |
| 2| 6040 | 36.96 | 12.46 | 0.80 |
| 3| 6121 | 45.08 | 15.17 | 0.89 |
| 4| 6375 | 57.37 | 19.38 | 1.03 |
| 5| 6372 | 64.29 | 21.62 | 1.11 |
| 6| 6564 | 70.29 | 23.62 | 1.18 |
| 7| 6529 | 77.92 | 26.13 | 1.26 |
| 8| 6918 | 92.25 | 31.01 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.07 | 6.71 | 0.62 |
| 10 | 10 | 570 | 6175 | 38.62 | 14.15 | 0.84 |
| 10 | 30 | 1710 | 6857 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2220 | 7160 | 98.05 | 37.58 | 1.53 |

