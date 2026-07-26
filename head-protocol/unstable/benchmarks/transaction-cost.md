--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-26 07:09:46.926667745 UTC |
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
| 1| 5838 | 10.17 | 3.22 | 0.51 |
| 2| 6042 | 12.84 | 4.08 | 0.55 |
| 3| 6238 | 14.67 | 4.64 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14286 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 169 | 751 | 42.50 | 12.22 | 0.61 |
| 4 | 227 | 858 | 47.80 | 13.87 | 0.67 |
| 5 | 282 | 969 | 59.90 | 17.28 | 0.80 |
| 6 | 336 | 1081 | 64.46 | 18.67 | 0.85 |
| 7 | 394 | 1192 | 74.35 | 21.43 | 0.96 |
| 8 | 451 | 1303 | 96.71 | 27.28 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1801 | 24.29 | 7.69 | 0.48 |
| 2| 1982 | 26.83 | 9.06 | 0.52 |
| 3| 2063 | 27.32 | 9.86 | 0.53 |
| 5| 2432 | 32.56 | 12.66 | 0.61 |
| 10| 3125 | 41.35 | 18.44 | 0.75 |
| 43| 7840 | 98.36 | 56.31 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.80 | 7.37 | 0.42 |
| 2| 749 | 23.54 | 8.23 | 0.43 |
| 3| 914 | 25.06 | 9.31 | 0.46 |
| 5| 1157 | 28.04 | 11.48 | 0.51 |
| 10| 2059 | 40.51 | 18.32 | 0.70 |
| 40| 6661 | 99.01 | 54.58 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.13 | 8.90 | 0.48 |
| 2| 741 | 30.20 | 9.84 | 0.50 |
| 3| 945 | 32.75 | 11.24 | 0.54 |
| 5| 1228 | 36.99 | 13.77 | 0.60 |
| 10| 2088 | 45.64 | 19.59 | 0.75 |
| 37| 6018 | 98.27 | 52.35 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 33.12 | 9.94 | 0.52 |
| 2| 815 | 35.81 | 11.37 | 0.56 |
| 3| 1006 | 38.55 | 12.81 | 0.60 |
| 5| 1336 | 43.28 | 15.47 | 0.67 |
| 10| 1950 | 53.23 | 21.56 | 0.82 |
| 29| 5087 | 99.51 | 47.18 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5806 | 27.16 | 9.12 | 0.69 |
| 2| 5963 | 35.88 | 12.05 | 0.79 |
| 3| 6089 | 44.65 | 15.00 | 0.89 |
| 4| 6197 | 52.81 | 17.69 | 0.98 |
| 5| 6474 | 63.32 | 21.39 | 1.10 |
| 6| 6618 | 73.75 | 24.90 | 1.22 |
| 7| 6572 | 76.24 | 25.58 | 1.24 |
| 8| 6913 | 95.23 | 32.16 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.52 | 6.98 | 0.62 |
| 10 | 20 | 1137 | 6511 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1709 | 6856 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2217 | 7156 | 98.93 | 37.88 | 1.54 |

