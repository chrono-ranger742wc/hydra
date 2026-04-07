--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-07 06:10:54.697087479 UTC |
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
| 1| 5837 | 10.55 | 3.35 | 0.52 |
| 2| 6035 | 12.34 | 3.90 | 0.54 |
| 3| 6239 | 14.69 | 4.65 | 0.58 |
| 5| 6646 | 19.17 | 6.07 | 0.64 |
| 10| 7644 | 28.81 | 9.07 | 0.78 |
| 43| 14279 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.24 | 9.37 | 0.51 |
| 3 | 169 | 747 | 42.66 | 12.27 | 0.62 |
| 4 | 227 | 858 | 53.95 | 15.39 | 0.73 |
| 5 | 282 | 969 | 64.32 | 18.24 | 0.84 |
| 6 | 338 | 1081 | 64.32 | 18.64 | 0.85 |
| 7 | 394 | 1192 | 79.38 | 22.77 | 1.01 |
| 8 | 452 | 1303 | 84.85 | 24.34 | 1.07 |
| 9 | 504 | 1414 | 97.91 | 27.80 | 1.20 |
| 10 | 560 | 1525 | 97.29 | 28.16 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.29 | 7.69 | 0.48 |
| 2| 1936 | 25.85 | 8.78 | 0.51 |
| 3| 2074 | 26.98 | 9.78 | 0.53 |
| 5| 2436 | 32.52 | 12.65 | 0.61 |
| 10| 3008 | 37.79 | 17.46 | 0.71 |
| 41| 7843 | 99.76 | 55.35 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 22.80 | 7.38 | 0.42 |
| 2| 750 | 24.35 | 8.47 | 0.44 |
| 3| 1061 | 28.21 | 10.21 | 0.50 |
| 5| 1210 | 29.86 | 12.00 | 0.53 |
| 10| 2031 | 40.55 | 18.33 | 0.70 |
| 42| 6772 | 99.59 | 56.05 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.42 | 8.68 | 0.47 |
| 2| 782 | 30.94 | 10.07 | 0.51 |
| 3| 960 | 33.43 | 11.44 | 0.55 |
| 5| 1181 | 36.39 | 13.58 | 0.59 |
| 10| 1913 | 43.28 | 18.89 | 0.72 |
| 34| 5605 | 97.68 | 50.11 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 33.83 | 10.16 | 0.53 |
| 2| 824 | 35.89 | 11.39 | 0.56 |
| 3| 1060 | 39.38 | 13.06 | 0.61 |
| 5| 1165 | 41.29 | 14.86 | 0.64 |
| 10| 1891 | 51.78 | 21.12 | 0.80 |
| 29| 4886 | 98.19 | 46.78 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 27.13 | 9.10 | 0.69 |
| 2| 5893 | 34.87 | 11.66 | 0.78 |
| 3| 6122 | 45.98 | 15.50 | 0.90 |
| 4| 6276 | 55.11 | 18.56 | 1.01 |
| 5| 6459 | 65.31 | 21.98 | 1.12 |
| 6| 6568 | 72.95 | 24.54 | 1.21 |
| 7| 6497 | 71.16 | 23.82 | 1.18 |
| 8| 7048 | 96.11 | 32.43 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 56 | 5867 | 20.78 | 7.06 | 0.63 |
| 10 | 10 | 568 | 6172 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1137 | 6511 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6853 | 81.48 | 30.96 | 1.33 |
| 10 | 39 | 2220 | 7159 | 99.82 | 38.19 | 1.55 |

