--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-28 11:11:13.198885366 UTC |
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
| 1| 5841 | 10.59 | 3.36 | 0.52 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6242 | 14.31 | 4.52 | 0.57 |
| 5| 6646 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 29.11 | 9.17 | 0.79 |
| 43| 14279 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 556 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 112 | 635 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 747 | 43.99 | 12.61 | 0.63 |
| 4 | 228 | 858 | 50.41 | 14.51 | 0.70 |
| 5 | 283 | 969 | 64.04 | 18.17 | 0.84 |
| 6 | 338 | 1081 | 73.37 | 20.80 | 0.94 |
| 7 | 394 | 1192 | 85.14 | 24.10 | 1.06 |
| 8 | 452 | 1307 | 95.38 | 26.80 | 1.17 |
| 9 | 508 | 1414 | 89.31 | 25.97 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1800 | 23.92 | 7.60 | 0.48 |
| 2| 1886 | 24.48 | 8.42 | 0.49 |
| 3| 2083 | 27.24 | 9.84 | 0.53 |
| 5| 2488 | 32.95 | 12.79 | 0.62 |
| 10| 3234 | 42.74 | 18.85 | 0.77 |
| 40| 7616 | 97.92 | 54.15 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 619 | 22.80 | 7.37 | 0.41 |
| 2| 754 | 24.35 | 8.47 | 0.44 |
| 3| 834 | 24.02 | 9.02 | 0.45 |
| 5| 1307 | 31.17 | 12.36 | 0.55 |
| 10| 2084 | 41.72 | 18.65 | 0.71 |
| 40| 6643 | 97.84 | 54.24 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 672 | 29.13 | 8.90 | 0.48 |
| 2| 770 | 28.55 | 9.40 | 0.48 |
| 3| 1016 | 31.54 | 10.94 | 0.53 |
| 5| 1291 | 35.12 | 13.27 | 0.59 |
| 10| 2048 | 48.94 | 20.49 | 0.78 |
| 34| 5732 | 94.99 | 49.48 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.83 | 10.16 | 0.53 |
| 2| 877 | 36.52 | 11.59 | 0.57 |
| 3| 904 | 37.13 | 12.38 | 0.58 |
| 5| 1260 | 42.61 | 15.27 | 0.66 |
| 10| 2123 | 55.64 | 22.28 | 0.85 |
| 28| 4938 | 98.04 | 46.11 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5798 | 26.97 | 9.05 | 0.69 |
| 2| 5846 | 31.48 | 10.46 | 0.74 |
| 3| 6130 | 47.36 | 15.99 | 0.92 |
| 4| 6329 | 56.84 | 19.24 | 1.03 |
| 5| 6325 | 60.34 | 20.29 | 1.06 |
| 6| 6436 | 68.44 | 22.93 | 1.15 |
| 7| 6631 | 83.15 | 27.97 | 1.32 |
| 8| 6900 | 89.62 | 30.16 | 1.40 |
| 10| 6752 | 91.87 | 30.67 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 56 | 5867 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 569 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 30 | 1707 | 6853 | 79.60 | 30.31 | 1.31 |
| 10 | 38 | 2158 | 7121 | 97.33 | 37.23 | 1.52 |

