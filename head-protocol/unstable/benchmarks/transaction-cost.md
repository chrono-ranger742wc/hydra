--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-23 08:23:18.8138927 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6035 | 12.92 | 4.11 | 0.55 |
| 3| 6242 | 14.60 | 4.62 | 0.58 |
| 5| 6640 | 18.81 | 5.94 | 0.64 |
| 10| 7644 | 29.12 | 9.18 | 0.79 |
| 43| 14279 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 169 | 747 | 41.19 | 11.92 | 0.60 |
| 4 | 226 | 858 | 53.98 | 15.42 | 0.74 |
| 5 | 283 | 969 | 59.41 | 17.07 | 0.80 |
| 6 | 340 | 1081 | 69.02 | 19.83 | 0.90 |
| 7 | 393 | 1192 | 78.43 | 22.41 | 1.00 |
| 8 | 448 | 1303 | 83.36 | 24.08 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.37 | 7.71 | 0.48 |
| 2| 1920 | 25.47 | 8.70 | 0.50 |
| 3| 2103 | 27.98 | 10.06 | 0.54 |
| 5| 2383 | 31.66 | 12.42 | 0.60 |
| 10| 3028 | 38.84 | 17.75 | 0.73 |
| 41| 7755 | 99.84 | 55.35 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.57 | 7.32 | 0.41 |
| 2| 767 | 23.62 | 8.24 | 0.43 |
| 3| 904 | 25.74 | 9.53 | 0.47 |
| 5| 1185 | 28.77 | 11.71 | 0.52 |
| 10| 2066 | 40.50 | 18.30 | 0.70 |
| 38| 5993 | 89.42 | 50.57 | 1.50 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 641 | 29.17 | 8.91 | 0.48 |
| 2| 887 | 29.86 | 9.81 | 0.50 |
| 3| 920 | 32.72 | 11.23 | 0.54 |
| 5| 1177 | 36.31 | 13.56 | 0.59 |
| 10| 2009 | 47.29 | 20.00 | 0.76 |
| 35| 5889 | 97.10 | 50.72 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.15 | 0.53 |
| 2| 806 | 35.81 | 11.37 | 0.56 |
| 3| 1023 | 38.66 | 12.84 | 0.60 |
| 5| 1229 | 41.89 | 15.05 | 0.65 |
| 10| 2019 | 53.87 | 21.76 | 0.83 |
| 30| 4936 | 98.91 | 47.60 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5838 | 27.08 | 9.09 | 0.69 |
| 2| 5871 | 34.92 | 11.69 | 0.78 |
| 3| 6182 | 45.72 | 15.43 | 0.90 |
| 4| 6240 | 54.42 | 18.30 | 1.00 |
| 5| 6411 | 64.02 | 21.53 | 1.10 |
| 6| 6508 | 73.58 | 24.75 | 1.21 |
| 7| 6696 | 82.62 | 27.90 | 1.31 |
| 8| 7052 | 94.91 | 32.09 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 20 | 1136 | 6511 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1708 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2220 | 7160 | 99.12 | 37.95 | 1.54 |

