--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-10 05:36:48.455039156 UTC |
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
| 2| 6042 | 12.65 | 4.01 | 0.55 |
| 3| 6239 | 14.72 | 4.66 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10038 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 170 | 747 | 42.72 | 12.29 | 0.62 |
| 4 | 228 | 862 | 48.13 | 13.97 | 0.68 |
| 5 | 282 | 969 | 57.62 | 16.63 | 0.78 |
| 6 | 337 | 1081 | 71.27 | 20.33 | 0.92 |
| 7 | 393 | 1192 | 83.97 | 23.69 | 1.05 |
| 8 | 448 | 1303 | 80.55 | 23.31 | 1.03 |
| 9 | 505 | 1414 | 98.83 | 28.25 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1752 | 22.92 | 7.32 | 0.47 |
| 2| 1936 | 25.88 | 8.79 | 0.51 |
| 3| 2059 | 26.94 | 9.77 | 0.53 |
| 5| 2443 | 31.88 | 12.49 | 0.61 |
| 10| 3311 | 44.26 | 19.26 | 0.79 |
| 40| 7713 | 99.19 | 54.54 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 642 | 22.57 | 7.32 | 0.41 |
| 2| 773 | 23.62 | 8.25 | 0.43 |
| 3| 959 | 26.17 | 9.62 | 0.47 |
| 5| 1203 | 29.11 | 11.78 | 0.52 |
| 10| 1985 | 39.14 | 17.91 | 0.68 |
| 42| 6668 | 98.74 | 55.83 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 27.54 | 8.47 | 0.46 |
| 2| 799 | 30.94 | 10.07 | 0.51 |
| 3| 968 | 33.47 | 11.45 | 0.55 |
| 5| 1248 | 37.06 | 13.78 | 0.60 |
| 10| 2097 | 48.90 | 20.48 | 0.79 |
| 35| 6012 | 96.46 | 50.55 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.87 | 10.16 | 0.53 |
| 2| 887 | 36.56 | 11.60 | 0.57 |
| 3| 945 | 37.91 | 12.62 | 0.59 |
| 5| 1333 | 44.03 | 15.70 | 0.68 |
| 10| 2206 | 56.69 | 22.62 | 0.87 |
| 30| 4708 | 96.01 | 46.72 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5839 | 27.05 | 9.08 | 0.69 |
| 2| 5977 | 35.84 | 12.06 | 0.79 |
| 3| 6019 | 41.45 | 13.87 | 0.85 |
| 4| 6189 | 50.32 | 16.86 | 0.95 |
| 5| 6417 | 64.27 | 21.64 | 1.11 |
| 6| 6557 | 75.65 | 25.56 | 1.23 |
| 7| 6798 | 84.39 | 28.42 | 1.34 |
| 8| 6695 | 88.09 | 29.56 | 1.37 |
| 9| 6932 | 96.08 | 32.38 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.52 | 6.98 | 0.62 |
| 10 | 20 | 1138 | 6512 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1708 | 6854 | 81.11 | 30.83 | 1.33 |
| 10 | 40 | 2278 | 7195 | 99.22 | 38.09 | 1.54 |
| 10 | 39 | 2220 | 7160 | 97.16 | 37.28 | 1.52 |

