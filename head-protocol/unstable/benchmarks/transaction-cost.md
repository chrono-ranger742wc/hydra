--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-06-09 08:25:22.991209352 UTC |
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
| 1| 5837 | 10.72 | 3.41 | 0.52 |
| 2| 6037 | 12.53 | 3.97 | 0.55 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.71 | 5.91 | 0.64 |
| 10| 7644 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 99.14 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 169 | 747 | 42.61 | 12.28 | 0.62 |
| 4 | 225 | 858 | 49.37 | 14.27 | 0.69 |
| 5 | 280 | 969 | 64.46 | 18.31 | 0.85 |
| 6 | 338 | 1085 | 69.62 | 19.86 | 0.90 |
| 7 | 393 | 1192 | 72.59 | 21.01 | 0.94 |
| 8 | 451 | 1303 | 81.26 | 23.58 | 1.03 |
| 9 | 505 | 1414 | 95.95 | 27.44 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 24.00 | 7.62 | 0.48 |
| 2| 1886 | 24.80 | 8.49 | 0.49 |
| 3| 2072 | 27.32 | 9.86 | 0.53 |
| 5| 2448 | 32.36 | 12.61 | 0.61 |
| 10| 3149 | 40.87 | 18.32 | 0.75 |
| 39| 7350 | 94.80 | 52.63 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.84 | 7.39 | 0.41 |
| 2| 769 | 24.35 | 8.48 | 0.44 |
| 3| 861 | 24.07 | 9.03 | 0.45 |
| 5| 1136 | 27.96 | 11.45 | 0.51 |
| 10| 2075 | 40.87 | 18.40 | 0.70 |
| 41| 6490 | 97.01 | 54.67 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.17 | 8.91 | 0.48 |
| 2| 813 | 29.22 | 9.61 | 0.49 |
| 3| 914 | 32.68 | 11.22 | 0.54 |
| 5| 1210 | 34.37 | 13.04 | 0.58 |
| 10| 2301 | 47.86 | 20.26 | 0.78 |
| 34| 5629 | 93.33 | 48.96 | 1.50 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.83 | 10.15 | 0.53 |
| 2| 807 | 35.89 | 11.39 | 0.56 |
| 3| 900 | 37.24 | 12.41 | 0.58 |
| 5| 1162 | 41.29 | 14.86 | 0.64 |
| 10| 2025 | 54.13 | 21.84 | 0.83 |
| 28| 4554 | 93.62 | 44.76 | 1.43 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5831 | 26.96 | 9.06 | 0.69 |
| 2| 5868 | 34.88 | 11.66 | 0.77 |
| 3| 6046 | 41.63 | 13.94 | 0.85 |
| 4| 6314 | 56.26 | 18.97 | 1.02 |
| 5| 6353 | 61.46 | 20.72 | 1.08 |
| 6| 6523 | 66.53 | 22.35 | 1.14 |
| 7| 6839 | 85.78 | 28.96 | 1.35 |
| 8| 6834 | 86.70 | 29.20 | 1.36 |
| 9| 7036 | 96.84 | 32.60 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 569 | 6174 | 40.39 | 14.75 | 0.85 |
| 10 | 39 | 2221 | 7161 | 98.49 | 37.73 | 1.53 |

