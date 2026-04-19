--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-19 06:23:00.9618156 UTC |
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
| 1| 5840 | 10.47 | 3.32 | 0.52 |
| 2| 6037 | 12.73 | 4.04 | 0.55 |
| 3| 6242 | 14.71 | 4.65 | 0.58 |
| 5| 6641 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 29.30 | 9.24 | 0.79 |
| 43| 14281 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 43.86 | 12.56 | 0.63 |
| 4 | 226 | 858 | 48.45 | 14.07 | 0.68 |
| 5 | 283 | 969 | 62.50 | 17.80 | 0.83 |
| 6 | 337 | 1081 | 66.26 | 19.14 | 0.87 |
| 7 | 394 | 1192 | 76.71 | 22.00 | 0.98 |
| 8 | 449 | 1303 | 80.55 | 23.31 | 1.03 |
| 9 | 506 | 1414 | 98.89 | 28.20 | 1.21 |
| 10 | 560 | 1525 | 98.00 | 28.46 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1798 | 24.00 | 7.62 | 0.48 |
| 2| 1929 | 25.51 | 8.70 | 0.50 |
| 3| 2144 | 28.51 | 10.19 | 0.55 |
| 5| 2408 | 31.83 | 12.48 | 0.60 |
| 10| 3171 | 40.62 | 18.26 | 0.75 |
| 39| 7499 | 96.58 | 53.16 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 604 | 22.84 | 7.38 | 0.41 |
| 2| 767 | 24.28 | 8.45 | 0.44 |
| 3| 951 | 26.12 | 9.62 | 0.47 |
| 5| 1242 | 30.94 | 12.30 | 0.54 |
| 10| 1981 | 39.90 | 18.13 | 0.69 |
| 40| 6421 | 97.13 | 54.03 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 26.83 | 8.26 | 0.45 |
| 2| 812 | 29.22 | 9.61 | 0.49 |
| 3| 974 | 33.51 | 11.47 | 0.55 |
| 5| 1272 | 35.12 | 13.27 | 0.59 |
| 10| 1999 | 44.08 | 19.12 | 0.73 |
| 34| 5730 | 94.50 | 49.28 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 33.87 | 10.16 | 0.53 |
| 2| 814 | 35.92 | 11.40 | 0.56 |
| 3| 970 | 37.84 | 12.60 | 0.59 |
| 5| 1350 | 43.31 | 15.48 | 0.67 |
| 10| 2059 | 54.88 | 22.05 | 0.84 |
| 29| 4816 | 96.53 | 46.28 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5787 | 27.09 | 9.09 | 0.69 |
| 2| 5984 | 35.83 | 12.05 | 0.79 |
| 3| 6154 | 46.10 | 15.53 | 0.91 |
| 4| 6220 | 53.58 | 18.05 | 0.99 |
| 5| 6445 | 65.40 | 22.02 | 1.12 |
| 6| 6555 | 74.01 | 24.96 | 1.22 |
| 7| 6833 | 84.46 | 28.49 | 1.34 |
| 8| 6818 | 88.93 | 29.87 | 1.38 |
| 9| 6743 | 88.08 | 29.50 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6005 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 570 | 6175 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1140 | 6514 | 59.28 | 22.29 | 1.08 |
| 10 | 39 | 2217 | 7156 | 98.93 | 37.88 | 1.54 |

