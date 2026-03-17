--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-17 05:46:36.000578179 UTC |
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
| 1| 5841 | 10.72 | 3.41 | 0.52 |
| 2| 6041 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 18.71 | 5.91 | 0.64 |
| 10| 7644 | 28.81 | 9.07 | 0.78 |
| 43| 14282 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10079 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 640 | 32.20 | 9.36 | 0.51 |
| 3 | 171 | 751 | 40.25 | 11.69 | 0.59 |
| 4 | 228 | 858 | 50.87 | 14.60 | 0.70 |
| 5 | 282 | 974 | 57.55 | 16.59 | 0.78 |
| 6 | 339 | 1081 | 72.19 | 20.60 | 0.93 |
| 7 | 396 | 1192 | 74.15 | 21.38 | 0.96 |
| 8 | 450 | 1303 | 90.45 | 25.84 | 1.12 |
| 10 | 560 | 1525 | 99.57 | 28.83 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1810 | 24.37 | 7.71 | 0.48 |
| 2| 1973 | 26.55 | 9.00 | 0.52 |
| 3| 2127 | 27.89 | 10.04 | 0.54 |
| 5| 2346 | 30.38 | 12.05 | 0.59 |
| 10| 3083 | 39.56 | 17.96 | 0.74 |
| 40| 7520 | 98.43 | 54.31 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 22.77 | 7.36 | 0.42 |
| 2| 799 | 24.28 | 8.45 | 0.44 |
| 3| 838 | 24.02 | 9.02 | 0.45 |
| 5| 1278 | 30.07 | 12.04 | 0.54 |
| 10| 1950 | 38.50 | 17.73 | 0.67 |
| 42| 6725 | 99.60 | 56.08 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 713 | 27.51 | 8.47 | 0.46 |
| 2| 816 | 29.19 | 9.60 | 0.49 |
| 3| 1010 | 31.65 | 10.97 | 0.53 |
| 5| 1313 | 37.58 | 13.96 | 0.61 |
| 10| 2126 | 46.52 | 19.85 | 0.76 |
| 34| 5666 | 98.30 | 50.31 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 690 | 33.79 | 10.15 | 0.53 |
| 2| 826 | 35.85 | 11.38 | 0.56 |
| 3| 896 | 37.20 | 12.40 | 0.58 |
| 5| 1317 | 43.40 | 15.50 | 0.67 |
| 10| 2062 | 54.65 | 21.99 | 0.84 |
| 28| 4847 | 97.15 | 45.83 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 26.92 | 9.04 | 0.69 |
| 2| 5937 | 35.80 | 12.04 | 0.79 |
| 3| 6083 | 44.80 | 15.05 | 0.89 |
| 4| 6315 | 56.19 | 18.91 | 1.02 |
| 5| 6447 | 63.39 | 21.36 | 1.10 |
| 6| 6493 | 70.72 | 23.86 | 1.18 |
| 7| 6735 | 83.66 | 28.13 | 1.33 |
| 8| 6871 | 93.31 | 31.50 | 1.43 |
| 9| 6794 | 95.80 | 32.10 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 20.07 | 6.71 | 0.62 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6005 | 27.58 | 9.82 | 0.71 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1136 | 6510 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1706 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2220 | 7160 | 99.82 | 38.19 | 1.55 |

