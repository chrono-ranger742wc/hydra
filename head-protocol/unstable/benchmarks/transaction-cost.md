--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-13 07:11:26.096356235 UTC |
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
| 1| 5834 | 10.74 | 3.42 | 0.52 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6239 | 14.50 | 4.58 | 0.58 |
| 5| 6645 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14279 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 635 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 751 | 42.68 | 12.30 | 0.62 |
| 4 | 227 | 858 | 53.64 | 15.27 | 0.73 |
| 5 | 283 | 969 | 64.09 | 18.15 | 0.84 |
| 6 | 339 | 1085 | 71.72 | 20.48 | 0.93 |
| 7 | 394 | 1192 | 87.14 | 24.58 | 1.08 |
| 8 | 450 | 1303 | 82.59 | 23.80 | 1.05 |
| 9 | 505 | 1414 | 91.51 | 26.38 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 23.92 | 7.60 | 0.48 |
| 2| 1979 | 26.55 | 9.00 | 0.52 |
| 3| 2017 | 25.91 | 9.48 | 0.52 |
| 5| 2452 | 32.64 | 12.68 | 0.61 |
| 10| 3111 | 40.20 | 18.12 | 0.74 |
| 42| 7880 | 99.25 | 55.91 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 22.77 | 7.36 | 0.42 |
| 2| 741 | 23.58 | 8.24 | 0.43 |
| 3| 1014 | 28.21 | 10.20 | 0.50 |
| 5| 1308 | 31.85 | 12.57 | 0.56 |
| 10| 2163 | 42.34 | 18.83 | 0.72 |
| 40| 6387 | 96.40 | 53.85 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 27.51 | 8.47 | 0.46 |
| 2| 843 | 29.22 | 9.61 | 0.49 |
| 3| 945 | 32.76 | 11.24 | 0.54 |
| 5| 1168 | 33.51 | 12.79 | 0.56 |
| 10| 1989 | 44.04 | 19.11 | 0.73 |
| 37| 6085 | 98.65 | 52.46 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 690 | 33.83 | 10.16 | 0.53 |
| 2| 849 | 36.64 | 11.62 | 0.57 |
| 3| 983 | 38.55 | 12.81 | 0.60 |
| 5| 1341 | 43.31 | 15.48 | 0.67 |
| 10| 2043 | 54.66 | 22.00 | 0.84 |
| 30| 4881 | 98.40 | 47.43 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5847 | 26.96 | 9.06 | 0.69 |
| 2| 6025 | 36.93 | 12.44 | 0.80 |
| 3| 6137 | 46.01 | 15.55 | 0.90 |
| 4| 6268 | 53.61 | 18.00 | 0.99 |
| 5| 6528 | 64.38 | 21.76 | 1.11 |
| 6| 6565 | 71.12 | 23.94 | 1.19 |
| 7| 6681 | 78.74 | 26.49 | 1.27 |
| 8| 6875 | 89.62 | 30.20 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 22.04 | 7.50 | 0.64 |
| 10 | 5 | 283 | 6002 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6175 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1139 | 6513 | 60.61 | 22.74 | 1.09 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2217 | 7156 | 98.93 | 37.88 | 1.54 |

