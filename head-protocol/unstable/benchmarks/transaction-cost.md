--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-31 05:34:51.738663217 UTC |
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
| 2| 6035 | 12.91 | 4.10 | 0.55 |
| 3| 6238 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.79 | 5.94 | 0.64 |
| 10| 7644 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 916 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 170 | 747 | 40.27 | 11.70 | 0.59 |
| 4 | 227 | 858 | 48.38 | 14.06 | 0.68 |
| 5 | 284 | 969 | 56.23 | 16.27 | 0.76 |
| 6 | 337 | 1081 | 71.15 | 20.23 | 0.92 |
| 7 | 394 | 1196 | 76.14 | 21.90 | 0.98 |
| 8 | 450 | 1303 | 98.19 | 27.53 | 1.20 |
| 9 | 505 | 1414 | 93.78 | 26.93 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.37 | 7.71 | 0.48 |
| 2| 1928 | 25.47 | 8.70 | 0.50 |
| 3| 2126 | 28.39 | 10.16 | 0.55 |
| 5| 2471 | 32.33 | 12.60 | 0.61 |
| 10| 3156 | 40.97 | 18.34 | 0.75 |
| 38| 7626 | 99.90 | 53.40 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 644 | 22.54 | 7.30 | 0.41 |
| 2| 762 | 24.32 | 8.46 | 0.44 |
| 3| 1033 | 28.10 | 10.19 | 0.50 |
| 5| 1195 | 28.77 | 11.71 | 0.52 |
| 10| 1961 | 37.55 | 17.47 | 0.67 |
| 39| 6199 | 91.54 | 51.83 | 1.54 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.17 | 8.91 | 0.48 |
| 2| 865 | 31.66 | 10.28 | 0.52 |
| 3| 1007 | 31.65 | 10.97 | 0.53 |
| 5| 1374 | 36.43 | 13.67 | 0.60 |
| 10| 2008 | 47.47 | 20.05 | 0.77 |
| 35| 5976 | 97.02 | 50.70 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.15 | 0.53 |
| 2| 896 | 36.52 | 11.59 | 0.57 |
| 3| 1102 | 39.14 | 13.00 | 0.61 |
| 5| 1283 | 42.64 | 15.28 | 0.66 |
| 10| 2054 | 54.13 | 21.84 | 0.84 |
| 29| 4909 | 98.58 | 46.87 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5795 | 27.13 | 9.10 | 0.69 |
| 2| 5989 | 36.77 | 12.41 | 0.80 |
| 3| 6084 | 42.64 | 14.30 | 0.87 |
| 4| 6301 | 55.19 | 18.58 | 1.01 |
| 5| 6415 | 63.55 | 21.41 | 1.10 |
| 6| 6575 | 70.05 | 23.58 | 1.18 |
| 7| 6551 | 79.28 | 26.60 | 1.27 |
| 8| 6778 | 87.70 | 29.42 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 27.58 | 9.82 | 0.71 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1710 | 6857 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2219 | 7158 | 98.05 | 37.58 | 1.53 |

