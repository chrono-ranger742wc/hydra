--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-27 05:41:38.505624758 UTC |
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
| 1| 5836 | 11.04 | 3.52 | 0.52 |
| 2| 6042 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.78 | 4.68 | 0.58 |
| 5| 6638 | 18.96 | 6.00 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14282 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 737 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 751 | 41.49 | 12.01 | 0.61 |
| 4 | 226 | 858 | 53.35 | 15.22 | 0.73 |
| 5 | 282 | 969 | 56.09 | 16.27 | 0.76 |
| 6 | 338 | 1085 | 73.87 | 21.00 | 0.95 |
| 7 | 396 | 1192 | 80.48 | 22.94 | 1.02 |
| 8 | 450 | 1303 | 89.13 | 25.41 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 2018 | 26.38 | 8.96 | 0.52 |
| 3| 2101 | 28.10 | 10.10 | 0.54 |
| 5| 2394 | 31.08 | 12.26 | 0.60 |
| 10| 3296 | 43.82 | 19.15 | 0.79 |
| 40| 7667 | 98.72 | 54.42 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 599 | 22.84 | 7.37 | 0.41 |
| 2| 828 | 25.37 | 8.75 | 0.45 |
| 3| 922 | 25.14 | 9.33 | 0.46 |
| 5| 1204 | 29.06 | 11.77 | 0.52 |
| 10| 1922 | 38.16 | 17.64 | 0.67 |
| 40| 6611 | 99.68 | 54.77 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 29.17 | 8.91 | 0.48 |
| 2| 870 | 29.86 | 9.81 | 0.50 |
| 3| 968 | 30.98 | 10.76 | 0.52 |
| 5| 1252 | 34.85 | 13.20 | 0.58 |
| 10| 2137 | 46.14 | 19.75 | 0.76 |
| 35| 5702 | 98.98 | 51.15 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 811 | 35.88 | 11.39 | 0.56 |
| 3| 942 | 37.84 | 12.60 | 0.59 |
| 5| 1292 | 43.39 | 15.50 | 0.67 |
| 10| 2009 | 54.25 | 21.87 | 0.83 |
| 28| 4942 | 98.81 | 46.33 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.57 | 0.64 |
| 2| 5952 | 35.99 | 12.08 | 0.79 |
| 3| 6200 | 45.72 | 15.45 | 0.90 |
| 4| 6122 | 50.59 | 16.94 | 0.95 |
| 5| 6498 | 65.29 | 22.01 | 1.12 |
| 6| 6710 | 75.38 | 25.51 | 1.24 |
| 7| 6706 | 80.06 | 26.95 | 1.29 |
| 8| 6811 | 87.79 | 29.50 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 20 | 1139 | 6513 | 60.61 | 22.74 | 1.09 |
| 10 | 30 | 1710 | 6857 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2163 | 7126 | 96.88 | 37.08 | 1.51 |

