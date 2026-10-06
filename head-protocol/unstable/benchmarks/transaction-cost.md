--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-10-06 11:36:23.626180337 UTC |
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
| 1| 5836 | 10.36 | 3.28 | 0.51 |
| 2| 6037 | 12.92 | 4.11 | 0.55 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6638 | 18.81 | 5.94 | 0.64 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 170 | 747 | 41.20 | 11.90 | 0.60 |
| 4 | 224 | 862 | 50.74 | 14.57 | 0.70 |
| 5 | 284 | 969 | 58.08 | 16.78 | 0.78 |
| 6 | 339 | 1081 | 75.48 | 21.38 | 0.96 |
| 7 | 394 | 1192 | 78.32 | 22.34 | 1.00 |
| 8 | 448 | 1303 | 81.03 | 23.52 | 1.03 |
| 9 | 505 | 1414 | 94.22 | 27.14 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1809 | 24.00 | 7.62 | 0.48 |
| 2| 1886 | 24.40 | 8.39 | 0.49 |
| 3| 2130 | 28.27 | 10.13 | 0.55 |
| 5| 2511 | 32.79 | 12.75 | 0.62 |
| 10| 3071 | 40.03 | 18.08 | 0.74 |
| 39| 7470 | 96.01 | 52.98 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.57 | 7.33 | 0.41 |
| 2| 698 | 22.62 | 7.95 | 0.42 |
| 3| 878 | 25.58 | 9.50 | 0.46 |
| 5| 1217 | 29.12 | 11.78 | 0.52 |
| 10| 2054 | 39.87 | 18.14 | 0.69 |
| 41| 6579 | 97.20 | 54.72 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 27.50 | 8.46 | 0.46 |
| 2| 793 | 30.98 | 10.08 | 0.51 |
| 3| 1014 | 31.65 | 10.97 | 0.53 |
| 5| 1259 | 35.04 | 13.25 | 0.58 |
| 10| 1986 | 43.96 | 19.09 | 0.73 |
| 35| 5628 | 92.51 | 49.37 | 1.50 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 689 | 33.87 | 10.16 | 0.53 |
| 2| 868 | 36.60 | 11.61 | 0.57 |
| 3| 1010 | 38.66 | 12.84 | 0.60 |
| 5| 1250 | 42.22 | 15.15 | 0.66 |
| 10| 2088 | 55.22 | 22.15 | 0.85 |
| 27| 4690 | 95.06 | 44.58 | 1.45 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5842 | 26.96 | 9.06 | 0.69 |
| 2| 6022 | 36.96 | 12.45 | 0.80 |
| 3| 6166 | 45.74 | 15.41 | 0.90 |
| 4| 6197 | 52.08 | 17.51 | 0.97 |
| 5| 6354 | 63.07 | 21.21 | 1.09 |
| 6| 6626 | 71.73 | 24.22 | 1.20 |
| 7| 6510 | 74.23 | 24.76 | 1.21 |
| 8| 6954 | 93.58 | 31.65 | 1.44 |
| 9| 7011 | 97.68 | 33.06 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1137 | 6511 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1709 | 6855 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2163 | 7126 | 97.07 | 37.14 | 1.52 |

