--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-16 09:59:27.846422762 UTC |
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
| 1| 5841 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6239 | 14.88 | 4.72 | 0.58 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7647 | 28.80 | 9.07 | 0.78 |
| 43| 14286 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 528 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 44.01 | 12.62 | 0.63 |
| 4 | 226 | 858 | 52.34 | 14.98 | 0.72 |
| 5 | 280 | 969 | 59.41 | 17.06 | 0.80 |
| 6 | 341 | 1081 | 69.66 | 19.87 | 0.90 |
| 7 | 393 | 1192 | 74.16 | 21.34 | 0.96 |
| 8 | 450 | 1303 | 96.86 | 27.36 | 1.19 |
| 9 | 505 | 1414 | 96.40 | 27.66 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.37 | 7.71 | 0.48 |
| 2| 1972 | 26.55 | 9.00 | 0.52 |
| 3| 2066 | 26.95 | 9.77 | 0.53 |
| 5| 2349 | 29.96 | 11.95 | 0.58 |
| 10| 3167 | 40.96 | 18.34 | 0.75 |
| 41| 7720 | 98.51 | 55.02 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 605 | 22.84 | 7.39 | 0.41 |
| 2| 775 | 24.04 | 8.41 | 0.44 |
| 3| 838 | 24.09 | 9.05 | 0.45 |
| 5| 1155 | 28.04 | 11.48 | 0.51 |
| 10| 2102 | 41.44 | 18.57 | 0.71 |
| 40| 6373 | 98.63 | 54.38 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 29.17 | 8.91 | 0.48 |
| 2| 885 | 29.97 | 9.84 | 0.50 |
| 3| 1010 | 33.39 | 11.44 | 0.55 |
| 5| 1236 | 36.99 | 13.77 | 0.60 |
| 10| 1940 | 46.61 | 19.79 | 0.75 |
| 37| 5958 | 96.27 | 51.75 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 33.87 | 10.16 | 0.53 |
| 2| 807 | 35.92 | 11.40 | 0.56 |
| 3| 1002 | 38.55 | 12.81 | 0.60 |
| 5| 1325 | 43.35 | 15.49 | 0.67 |
| 10| 1859 | 51.85 | 21.14 | 0.80 |
| 28| 4759 | 96.70 | 45.70 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.13 | 9.09 | 0.69 |
| 2| 5967 | 35.84 | 12.03 | 0.79 |
| 3| 6141 | 46.02 | 15.52 | 0.90 |
| 4| 6226 | 53.98 | 18.13 | 0.99 |
| 5| 6438 | 63.77 | 21.48 | 1.10 |
| 6| 6521 | 69.09 | 23.22 | 1.16 |
| 7| 6800 | 82.92 | 27.90 | 1.32 |
| 8| 6927 | 94.70 | 31.94 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 568 | 6172 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1138 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1707 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2163 | 7125 | 96.00 | 36.77 | 1.50 |

