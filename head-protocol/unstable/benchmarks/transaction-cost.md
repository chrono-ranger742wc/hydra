--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-29 11:23:17.425681819 UTC |
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
| 1| 5836 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6239 | 14.79 | 4.69 | 0.58 |
| 5| 6640 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14283 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 42.23 | 12.15 | 0.61 |
| 4 | 228 | 858 | 52.27 | 14.96 | 0.72 |
| 5 | 283 | 969 | 60.20 | 17.35 | 0.80 |
| 6 | 336 | 1081 | 75.51 | 21.35 | 0.96 |
| 7 | 396 | 1192 | 75.85 | 21.74 | 0.97 |
| 8 | 449 | 1303 | 92.46 | 26.31 | 1.14 |
| 9 | 508 | 1414 | 96.67 | 27.73 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1817 | 24.00 | 7.62 | 0.48 |
| 2| 2027 | 26.58 | 9.01 | 0.52 |
| 3| 2126 | 28.01 | 10.07 | 0.54 |
| 5| 2463 | 32.48 | 12.64 | 0.61 |
| 10| 3229 | 41.77 | 18.58 | 0.76 |
| 39| 7432 | 95.18 | 52.76 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.77 | 7.36 | 0.42 |
| 2| 775 | 24.28 | 8.45 | 0.44 |
| 3| 910 | 25.09 | 9.32 | 0.46 |
| 5| 1264 | 31.00 | 12.33 | 0.55 |
| 10| 2123 | 43.19 | 19.05 | 0.73 |
| 41| 6633 | 95.31 | 54.24 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 694 | 27.47 | 8.46 | 0.46 |
| 2| 815 | 29.18 | 9.60 | 0.49 |
| 3| 934 | 32.80 | 11.25 | 0.54 |
| 5| 1221 | 34.30 | 13.02 | 0.58 |
| 10| 2034 | 45.00 | 19.39 | 0.74 |
| 35| 5816 | 94.36 | 49.92 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 696 | 33.83 | 10.16 | 0.53 |
| 2| 810 | 35.92 | 11.40 | 0.56 |
| 3| 952 | 37.95 | 12.63 | 0.59 |
| 5| 1262 | 42.68 | 15.29 | 0.66 |
| 10| 1962 | 53.30 | 21.58 | 0.82 |
| 29| 4949 | 98.39 | 46.84 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5826 | 27.05 | 9.08 | 0.69 |
| 2| 5951 | 35.88 | 12.06 | 0.79 |
| 3| 6205 | 47.11 | 15.88 | 0.92 |
| 4| 6236 | 53.98 | 18.12 | 0.99 |
| 5| 6479 | 65.14 | 22.03 | 1.12 |
| 6| 6671 | 76.33 | 25.85 | 1.25 |
| 7| 6779 | 80.00 | 26.96 | 1.29 |
| 8| 6877 | 93.27 | 31.46 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6513 | 58.66 | 22.07 | 1.07 |
| 10 | 39 | 2221 | 7160 | 98.05 | 37.58 | 1.53 |

