--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-09 05:42:50.919914049 UTC |
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
| 1| 5836 | 10.57 | 3.36 | 0.52 |
| 2| 6037 | 13.01 | 4.14 | 0.55 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6638 | 19.02 | 6.02 | 0.64 |
| 10| 7646 | 29.38 | 9.27 | 0.79 |
| 43| 14281 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10069 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 42.46 | 12.20 | 0.61 |
| 4 | 225 | 858 | 48.04 | 13.95 | 0.68 |
| 5 | 281 | 969 | 56.43 | 16.41 | 0.77 |
| 6 | 337 | 1081 | 73.34 | 20.76 | 0.94 |
| 7 | 394 | 1192 | 81.31 | 23.19 | 1.03 |
| 8 | 451 | 1303 | 93.35 | 26.37 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1791 | 24.37 | 7.71 | 0.48 |
| 2| 1920 | 25.43 | 8.68 | 0.50 |
| 3| 2129 | 28.35 | 10.15 | 0.55 |
| 5| 2378 | 31.34 | 12.32 | 0.60 |
| 10| 3121 | 40.49 | 18.21 | 0.75 |
| 40| 7639 | 99.76 | 54.66 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 22.84 | 7.39 | 0.41 |
| 2| 757 | 23.58 | 8.23 | 0.43 |
| 3| 833 | 24.02 | 9.01 | 0.45 |
| 5| 1306 | 31.03 | 12.32 | 0.55 |
| 10| 1982 | 38.73 | 17.80 | 0.68 |
| 40| 6494 | 94.99 | 53.48 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 658 | 29.17 | 8.91 | 0.48 |
| 2| 770 | 28.55 | 9.40 | 0.48 |
| 3| 948 | 30.87 | 10.74 | 0.52 |
| 5| 1131 | 35.60 | 13.34 | 0.58 |
| 10| 2108 | 48.08 | 20.24 | 0.78 |
| 36| 5851 | 94.96 | 50.73 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 33.87 | 10.16 | 0.53 |
| 2| 890 | 36.60 | 11.61 | 0.57 |
| 3| 972 | 37.80 | 12.59 | 0.59 |
| 5| 1256 | 42.68 | 15.29 | 0.66 |
| 10| 2066 | 54.76 | 22.02 | 0.84 |
| 29| 4837 | 97.30 | 46.51 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 27.05 | 9.07 | 0.69 |
| 2| 5897 | 34.80 | 11.66 | 0.77 |
| 3| 6148 | 45.69 | 15.39 | 0.90 |
| 4| 6183 | 50.31 | 16.88 | 0.95 |
| 5| 6341 | 60.96 | 20.50 | 1.07 |
| 6| 6386 | 68.27 | 22.87 | 1.15 |
| 7| 6674 | 82.08 | 27.70 | 1.31 |
| 8| 6776 | 90.52 | 30.38 | 1.40 |
| 9| 6881 | 97.30 | 32.68 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1139 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1708 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2222 | 7161 | 98.24 | 37.65 | 1.53 |

