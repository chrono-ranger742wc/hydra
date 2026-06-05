--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-05 08:40:52.940464662 UTC |
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
| 2| 6041 | 13.08 | 4.16 | 0.55 |
| 3| 6238 | 14.29 | 4.51 | 0.57 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 29.49 | 9.31 | 0.79 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 751 | 41.24 | 11.91 | 0.60 |
| 4 | 227 | 858 | 53.79 | 15.30 | 0.73 |
| 5 | 283 | 969 | 62.93 | 17.91 | 0.83 |
| 6 | 338 | 1085 | 68.29 | 19.70 | 0.89 |
| 7 | 397 | 1192 | 72.47 | 21.02 | 0.94 |
| 8 | 452 | 1303 | 98.73 | 27.71 | 1.20 |
| 9 | 506 | 1414 | 91.54 | 26.39 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 22.92 | 7.32 | 0.47 |
| 2| 2007 | 26.87 | 9.07 | 0.52 |
| 3| 2017 | 26.02 | 9.51 | 0.52 |
| 5| 2277 | 28.89 | 11.65 | 0.57 |
| 10| 3119 | 40.75 | 18.29 | 0.75 |
| 38| 7613 | 98.61 | 53.05 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 22.81 | 7.37 | 0.42 |
| 2| 781 | 24.31 | 8.46 | 0.44 |
| 3| 1013 | 28.32 | 10.23 | 0.50 |
| 5| 1199 | 29.62 | 11.94 | 0.53 |
| 10| 2042 | 40.79 | 18.38 | 0.70 |
| 42| 6703 | 98.67 | 55.79 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 29.13 | 8.90 | 0.48 |
| 2| 782 | 30.90 | 10.06 | 0.51 |
| 3| 1045 | 34.11 | 11.65 | 0.56 |
| 5| 1222 | 37.02 | 13.77 | 0.60 |
| 10| 1946 | 43.70 | 18.99 | 0.73 |
| 35| 5828 | 95.31 | 50.16 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.87 | 10.16 | 0.53 |
| 2| 773 | 35.17 | 11.17 | 0.55 |
| 3| 941 | 37.91 | 12.62 | 0.59 |
| 5| 1256 | 42.65 | 15.28 | 0.66 |
| 10| 1960 | 52.89 | 21.46 | 0.82 |
| 29| 4898 | 98.45 | 46.84 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5790 | 27.00 | 9.07 | 0.69 |
| 2| 5918 | 35.96 | 12.09 | 0.79 |
| 3| 6111 | 44.91 | 15.08 | 0.89 |
| 4| 6260 | 55.92 | 18.87 | 1.01 |
| 5| 6420 | 61.18 | 20.63 | 1.08 |
| 6| 6601 | 74.83 | 25.27 | 1.23 |
| 7| 6941 | 87.07 | 29.46 | 1.37 |
| 8| 6925 | 93.31 | 31.48 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 567 | 6171 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1136 | 6511 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1708 | 6854 | 79.60 | 30.31 | 1.31 |
| 10 | 39 | 2213 | 7152 | 99.38 | 38.03 | 1.54 |

