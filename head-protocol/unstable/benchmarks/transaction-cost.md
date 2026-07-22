--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-22 07:01:59.181729592 UTC |
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
| 1| 5836 | 10.55 | 3.35 | 0.52 |
| 2| 6035 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14285 | 99.32 | 31.06 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 528 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 170 | 747 | 43.73 | 12.51 | 0.63 |
| 4 | 227 | 858 | 49.96 | 14.46 | 0.70 |
| 5 | 284 | 969 | 55.94 | 16.23 | 0.76 |
| 6 | 338 | 1085 | 63.65 | 18.43 | 0.85 |
| 7 | 397 | 1192 | 86.39 | 24.35 | 1.08 |
| 8 | 449 | 1303 | 93.82 | 26.53 | 1.16 |
| 9 | 504 | 1414 | 92.35 | 26.70 | 1.15 |
| 10 | 560 | 1525 | 98.14 | 28.38 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1820 | 24.37 | 7.71 | 0.48 |
| 2| 1886 | 24.80 | 8.49 | 0.49 |
| 3| 2101 | 28.51 | 10.19 | 0.55 |
| 5| 2431 | 32.11 | 12.55 | 0.61 |
| 10| 3004 | 37.59 | 17.40 | 0.71 |
| 43| 7878 | 99.82 | 56.72 | 1.71 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.80 | 7.38 | 0.41 |
| 2| 757 | 24.35 | 8.47 | 0.44 |
| 3| 923 | 25.10 | 9.32 | 0.46 |
| 5| 1236 | 30.82 | 12.28 | 0.54 |
| 10| 2054 | 39.57 | 18.04 | 0.69 |
| 41| 6663 | 96.96 | 54.70 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 703 | 27.47 | 8.46 | 0.46 |
| 2| 836 | 29.15 | 9.59 | 0.49 |
| 3| 985 | 33.51 | 11.47 | 0.55 |
| 5| 1280 | 37.66 | 13.97 | 0.61 |
| 10| 1961 | 46.62 | 19.80 | 0.76 |
| 35| 5745 | 94.93 | 50.05 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 668 | 33.83 | 10.16 | 0.53 |
| 2| 769 | 35.14 | 11.16 | 0.55 |
| 3| 964 | 37.95 | 12.63 | 0.59 |
| 5| 1203 | 41.97 | 15.07 | 0.65 |
| 10| 1973 | 53.42 | 21.61 | 0.82 |
| 29| 4981 | 97.74 | 46.64 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.08 | 9.08 | 0.69 |
| 2| 5967 | 35.72 | 12.00 | 0.79 |
| 3| 6095 | 42.42 | 14.24 | 0.86 |
| 4| 6280 | 55.05 | 18.58 | 1.01 |
| 5| 6319 | 59.52 | 19.95 | 1.05 |
| 6| 6607 | 73.00 | 24.54 | 1.21 |
| 7| 6801 | 81.30 | 27.52 | 1.30 |
| 8| 7030 | 92.63 | 31.32 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.82 | 6.63 | 0.61 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1140 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2221 | 7160 | 98.05 | 37.58 | 1.53 |

