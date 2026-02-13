--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-13 05:56:28.83209789 UTC |
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
| 1| 5836 | 10.66 | 3.39 | 0.52 |
| 2| 6035 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10047 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 747 | 43.91 | 12.57 | 0.63 |
| 4 | 226 | 862 | 53.74 | 15.29 | 0.73 |
| 5 | 281 | 969 | 61.59 | 17.68 | 0.82 |
| 6 | 338 | 1081 | 68.02 | 19.52 | 0.89 |
| 7 | 395 | 1196 | 75.14 | 21.71 | 0.97 |
| 8 | 451 | 1303 | 91.63 | 26.01 | 1.14 |
| 10 | 560 | 1525 | 98.03 | 28.41 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1790 | 23.92 | 7.60 | 0.48 |
| 2| 1996 | 26.42 | 8.96 | 0.52 |
| 3| 2057 | 26.94 | 9.77 | 0.53 |
| 5| 2389 | 31.44 | 12.35 | 0.60 |
| 10| 3106 | 40.41 | 18.19 | 0.74 |
| 40| 7708 | 99.12 | 54.53 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 613 | 22.80 | 7.38 | 0.41 |
| 2| 775 | 24.28 | 8.45 | 0.44 |
| 3| 857 | 24.11 | 9.04 | 0.45 |
| 5| 1346 | 32.14 | 12.64 | 0.56 |
| 10| 1838 | 36.42 | 17.17 | 0.65 |
| 43| 6695 | 95.99 | 55.73 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 27.47 | 8.46 | 0.46 |
| 2| 886 | 29.86 | 9.81 | 0.50 |
| 3| 1009 | 31.69 | 10.98 | 0.53 |
| 5| 1240 | 37.06 | 13.78 | 0.60 |
| 10| 2071 | 48.27 | 20.29 | 0.78 |
| 35| 5834 | 95.75 | 50.31 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 671 | 33.83 | 10.16 | 0.53 |
| 2| 761 | 35.21 | 11.18 | 0.55 |
| 3| 982 | 38.51 | 12.80 | 0.60 |
| 5| 1322 | 43.17 | 15.45 | 0.67 |
| 10| 2086 | 55.41 | 22.22 | 0.85 |
| 29| 5000 | 99.45 | 47.11 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5791 | 27.00 | 9.06 | 0.69 |
| 2| 6062 | 36.97 | 12.46 | 0.81 |
| 3| 6072 | 44.56 | 15.00 | 0.89 |
| 4| 6269 | 53.54 | 18.00 | 0.99 |
| 5| 6473 | 65.50 | 22.17 | 1.12 |
| 6| 6510 | 69.54 | 23.33 | 1.17 |
| 7| 6714 | 77.73 | 26.16 | 1.26 |
| 8| 6772 | 90.64 | 30.47 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 57 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1136 | 6510 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1709 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2164 | 7126 | 97.07 | 37.14 | 1.52 |

