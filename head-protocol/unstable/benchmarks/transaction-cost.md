--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-08 05:07:11.86792833 UTC |
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
| 1| 5834 | 10.55 | 3.35 | 0.52 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6239 | 14.76 | 4.67 | 0.58 |
| 5| 6643 | 18.64 | 5.88 | 0.64 |
| 10| 7651 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 99.42 | 31.09 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 914 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 32.24 | 9.37 | 0.51 |
| 3 | 170 | 751 | 43.84 | 12.56 | 0.63 |
| 4 | 227 | 858 | 51.16 | 14.72 | 0.71 |
| 5 | 284 | 974 | 58.40 | 16.92 | 0.79 |
| 6 | 339 | 1081 | 69.38 | 19.84 | 0.90 |
| 7 | 393 | 1192 | 84.96 | 24.02 | 1.06 |
| 8 | 450 | 1303 | 97.58 | 27.43 | 1.19 |
| 9 | 507 | 1418 | 89.15 | 25.88 | 1.12 |
| 10 | 560 | 1525 | 98.62 | 28.68 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 24.29 | 7.69 | 0.48 |
| 2| 2004 | 26.92 | 9.09 | 0.52 |
| 3| 2068 | 27.24 | 9.84 | 0.53 |
| 5| 2387 | 31.42 | 12.34 | 0.60 |
| 10| 3142 | 41.16 | 18.41 | 0.75 |
| 39| 7461 | 98.33 | 53.59 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 617 | 22.84 | 7.37 | 0.42 |
| 2| 787 | 24.25 | 8.44 | 0.44 |
| 3| 976 | 26.53 | 9.76 | 0.48 |
| 5| 1282 | 30.98 | 12.31 | 0.55 |
| 10| 2041 | 41.78 | 18.67 | 0.71 |
| 41| 6635 | 96.77 | 54.61 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 646 | 29.13 | 8.90 | 0.48 |
| 2| 770 | 28.47 | 9.38 | 0.48 |
| 3| 974 | 30.87 | 10.74 | 0.52 |
| 5| 1236 | 34.30 | 13.02 | 0.58 |
| 10| 2247 | 47.94 | 20.28 | 0.78 |
| 36| 5744 | 99.82 | 52.02 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.87 | 10.16 | 0.53 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 963 | 37.91 | 12.62 | 0.59 |
| 5| 1310 | 43.32 | 15.48 | 0.67 |
| 10| 2173 | 55.43 | 22.24 | 0.85 |
| 29| 4839 | 98.06 | 46.70 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 26.92 | 9.04 | 0.69 |
| 2| 5965 | 35.88 | 12.04 | 0.79 |
| 3| 6109 | 45.89 | 15.49 | 0.90 |
| 4| 6127 | 49.46 | 16.54 | 0.94 |
| 5| 6407 | 62.24 | 20.98 | 1.09 |
| 6| 6592 | 74.31 | 25.01 | 1.22 |
| 7| 6783 | 80.67 | 27.22 | 1.30 |
| 8| 6560 | 77.24 | 25.80 | 1.25 |
| 9| 6938 | 96.29 | 32.37 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.65 | 10.19 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1709 | 6855 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2221 | 7160 | 99.82 | 38.19 | 1.55 |

