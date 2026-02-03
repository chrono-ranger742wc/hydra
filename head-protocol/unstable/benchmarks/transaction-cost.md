--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-03 05:43:44.343581128 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.63 | 4.00 | 0.55 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7647 | 28.88 | 9.10 | 0.79 |
| 43| 14279 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 171 | 751 | 43.72 | 12.52 | 0.63 |
| 4 | 226 | 858 | 51.12 | 14.69 | 0.71 |
| 5 | 281 | 969 | 60.82 | 17.37 | 0.81 |
| 6 | 339 | 1081 | 70.54 | 20.21 | 0.91 |
| 7 | 396 | 1192 | 84.71 | 23.92 | 1.06 |
| 8 | 449 | 1307 | 91.85 | 26.01 | 1.14 |
| 10 | 560 | 1525 | 97.15 | 28.13 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1817 | 23.92 | 7.60 | 0.48 |
| 2| 2005 | 26.92 | 9.08 | 0.52 |
| 3| 2088 | 26.94 | 9.77 | 0.53 |
| 5| 2340 | 30.49 | 12.08 | 0.59 |
| 10| 3092 | 39.99 | 18.07 | 0.74 |
| 39| 7552 | 97.63 | 53.41 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 620 | 22.84 | 7.39 | 0.42 |
| 2| 726 | 22.60 | 7.95 | 0.42 |
| 3| 956 | 26.95 | 9.85 | 0.48 |
| 5| 1241 | 29.84 | 12.02 | 0.53 |
| 10| 1932 | 37.46 | 17.45 | 0.66 |
| 40| 6562 | 97.61 | 54.20 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 706 | 27.54 | 8.47 | 0.46 |
| 2| 782 | 30.90 | 10.06 | 0.51 |
| 3| 994 | 31.58 | 10.95 | 0.53 |
| 5| 1295 | 37.69 | 13.98 | 0.61 |
| 10| 2137 | 46.48 | 19.84 | 0.76 |
| 34| 5748 | 95.24 | 49.54 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 33.87 | 10.16 | 0.53 |
| 2| 882 | 36.64 | 11.62 | 0.57 |
| 3| 1068 | 39.18 | 13.01 | 0.61 |
| 5| 1218 | 42.27 | 15.16 | 0.65 |
| 10| 2067 | 54.62 | 21.99 | 0.84 |
| 29| 4847 | 98.41 | 46.79 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5797 | 27.16 | 9.12 | 0.69 |
| 2| 6021 | 36.94 | 12.47 | 0.80 |
| 3| 6084 | 42.57 | 14.28 | 0.86 |
| 4| 6298 | 54.89 | 18.50 | 1.00 |
| 5| 6342 | 62.68 | 21.04 | 1.09 |
| 6| 6628 | 75.52 | 25.53 | 1.24 |
| 7| 6800 | 84.15 | 28.40 | 1.33 |
| 8| 6966 | 94.78 | 31.94 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1136 | 6511 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1705 | 6851 | 79.34 | 30.22 | 1.31 |
| 10 | 39 | 2219 | 7158 | 99.12 | 37.95 | 1.54 |

