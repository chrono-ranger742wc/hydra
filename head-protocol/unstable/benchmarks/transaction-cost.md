--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-13 05:36:53.32255065 UTC |
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
| 1| 5834 | 10.47 | 3.32 | 0.52 |
| 2| 6037 | 12.80 | 4.07 | 0.55 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10054 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 169 | 747 | 40.20 | 11.72 | 0.59 |
| 4 | 227 | 858 | 48.11 | 13.97 | 0.68 |
| 5 | 283 | 969 | 60.93 | 17.43 | 0.81 |
| 6 | 337 | 1085 | 71.41 | 20.33 | 0.92 |
| 7 | 393 | 1192 | 86.63 | 24.41 | 1.08 |
| 8 | 452 | 1303 | 94.60 | 26.77 | 1.16 |
| 9 | 504 | 1414 | 94.62 | 27.14 | 1.17 |
| 10 | 560 | 1525 | 97.12 | 28.18 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1803 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.77 | 8.48 | 0.49 |
| 3| 2142 | 28.42 | 10.17 | 0.55 |
| 5| 2430 | 32.19 | 12.57 | 0.61 |
| 10| 3062 | 38.96 | 17.78 | 0.73 |
| 38| 7168 | 91.34 | 51.02 | 1.57 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 618 | 22.84 | 7.38 | 0.42 |
| 2| 778 | 23.63 | 8.24 | 0.43 |
| 3| 945 | 26.84 | 9.83 | 0.48 |
| 5| 1283 | 30.11 | 12.06 | 0.54 |
| 10| 1954 | 38.72 | 17.81 | 0.68 |
| 41| 6684 | 99.76 | 55.45 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 29.13 | 8.90 | 0.48 |
| 2| 816 | 29.18 | 9.60 | 0.49 |
| 3| 925 | 32.68 | 11.22 | 0.54 |
| 5| 1309 | 38.42 | 14.20 | 0.62 |
| 10| 1941 | 46.98 | 19.91 | 0.76 |
| 36| 6177 | 99.20 | 52.02 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.83 | 10.15 | 0.53 |
| 2| 892 | 36.56 | 11.60 | 0.57 |
| 3| 942 | 37.84 | 12.60 | 0.59 |
| 5| 1429 | 44.78 | 15.93 | 0.69 |
| 10| 1997 | 53.34 | 21.59 | 0.82 |
| 29| 4946 | 97.25 | 46.50 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5832 | 27.05 | 9.08 | 0.69 |
| 2| 5846 | 31.44 | 10.45 | 0.74 |
| 3| 6072 | 44.87 | 15.14 | 0.89 |
| 4| 6309 | 55.68 | 18.81 | 1.01 |
| 5| 6304 | 62.38 | 20.89 | 1.08 |
| 6| 6675 | 75.20 | 25.39 | 1.23 |
| 7| 6798 | 85.85 | 28.98 | 1.35 |
| 8| 6871 | 93.03 | 31.36 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 20.26 | 6.78 | 0.62 |
| 10 | 1 | 57 | 5868 | 21.41 | 7.28 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1707 | 6853 | 81.37 | 30.91 | 1.33 |
| 10 | 39 | 2218 | 7157 | 98.49 | 37.73 | 1.53 |

