--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-03 05:41:12.057024358 UTC |
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
| 1| 5836 | 10.36 | 3.28 | 0.51 |
| 2| 6035 | 12.75 | 4.04 | 0.55 |
| 3| 6242 | 14.38 | 4.54 | 0.57 |
| 5| 6643 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14279 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.38 | 9.91 | 0.53 |
| 3 | 170 | 747 | 40.05 | 11.65 | 0.59 |
| 4 | 227 | 858 | 54.09 | 15.42 | 0.74 |
| 5 | 284 | 969 | 64.11 | 18.16 | 0.84 |
| 6 | 338 | 1081 | 70.20 | 20.08 | 0.91 |
| 7 | 392 | 1192 | 86.90 | 24.44 | 1.08 |
| 8 | 449 | 1303 | 80.88 | 23.53 | 1.03 |
| 9 | 506 | 1414 | 96.13 | 27.43 | 1.19 |
| 10 | 561 | 1525 | 98.03 | 28.47 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1806 | 24.00 | 7.62 | 0.48 |
| 2| 1952 | 25.39 | 8.68 | 0.50 |
| 3| 2129 | 28.10 | 10.09 | 0.54 |
| 5| 2352 | 30.34 | 12.04 | 0.59 |
| 10| 3148 | 41.19 | 18.40 | 0.75 |
| 43| 7833 | 99.58 | 56.63 | 1.71 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 22.81 | 7.37 | 0.42 |
| 2| 703 | 22.55 | 7.95 | 0.42 |
| 3| 925 | 26.71 | 9.80 | 0.48 |
| 5| 1186 | 27.97 | 11.46 | 0.51 |
| 10| 1994 | 41.18 | 18.47 | 0.70 |
| 41| 6578 | 98.05 | 55.00 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 657 | 29.17 | 8.91 | 0.48 |
| 2| 887 | 29.90 | 9.82 | 0.50 |
| 3| 944 | 32.68 | 11.22 | 0.54 |
| 5| 1268 | 34.89 | 13.21 | 0.58 |
| 10| 2068 | 48.14 | 20.25 | 0.78 |
| 37| 5925 | 97.28 | 52.03 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 33.83 | 10.15 | 0.53 |
| 2| 872 | 36.52 | 11.59 | 0.57 |
| 3| 903 | 37.24 | 12.41 | 0.58 |
| 5| 1291 | 43.36 | 15.49 | 0.67 |
| 10| 2003 | 54.10 | 21.82 | 0.83 |
| 30| 4923 | 99.08 | 47.62 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5950 | 36.07 | 12.11 | 0.79 |
| 3| 6041 | 41.48 | 13.87 | 0.85 |
| 4| 6299 | 55.88 | 18.87 | 1.01 |
| 5| 6274 | 58.32 | 19.48 | 1.04 |
| 6| 6645 | 75.48 | 25.49 | 1.24 |
| 7| 6811 | 81.69 | 27.58 | 1.31 |
| 8| 6753 | 84.45 | 28.42 | 1.33 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1707 | 6854 | 79.60 | 30.31 | 1.31 |
| 10 | 40 | 2277 | 7193 | 98.77 | 37.94 | 1.54 |
| 10 | 39 | 2219 | 7158 | 98.93 | 37.88 | 1.54 |

