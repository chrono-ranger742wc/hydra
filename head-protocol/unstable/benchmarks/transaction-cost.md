--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-05 06:39:52.270620167 UTC |
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
| 1| 5840 | 10.36 | 3.28 | 0.51 |
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.98 | 4.75 | 0.58 |
| 5| 6638 | 18.71 | 5.91 | 0.64 |
| 10| 7651 | 29.11 | 9.17 | 0.79 |
| 43| 14282 | 98.73 | 30.85 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2181 | 12.13 | 7.25 | 0.40 |
| 54| 10050 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 169 | 747 | 42.46 | 12.22 | 0.61 |
| 4 | 227 | 858 | 53.50 | 15.23 | 0.73 |
| 5 | 284 | 969 | 57.91 | 16.74 | 0.78 |
| 6 | 340 | 1081 | 65.39 | 18.85 | 0.86 |
| 7 | 394 | 1192 | 84.69 | 23.95 | 1.06 |
| 8 | 450 | 1303 | 85.82 | 24.67 | 1.08 |
| 9 | 504 | 1414 | 88.43 | 25.69 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1981 | 26.92 | 9.09 | 0.52 |
| 3| 2191 | 28.93 | 10.34 | 0.55 |
| 5| 2380 | 31.36 | 12.33 | 0.60 |
| 10| 3331 | 43.94 | 19.18 | 0.79 |
| 38| 7368 | 95.70 | 52.19 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 634 | 22.80 | 7.38 | 0.42 |
| 2| 754 | 23.58 | 8.23 | 0.43 |
| 3| 896 | 25.16 | 9.34 | 0.46 |
| 5| 1169 | 28.01 | 11.47 | 0.51 |
| 10| 1879 | 36.92 | 17.29 | 0.66 |
| 39| 6286 | 94.22 | 52.56 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 664 | 29.13 | 8.90 | 0.48 |
| 2| 741 | 30.27 | 9.86 | 0.50 |
| 3| 1052 | 34.18 | 11.67 | 0.56 |
| 5| 1340 | 35.61 | 13.43 | 0.59 |
| 10| 1891 | 45.98 | 19.60 | 0.75 |
| 37| 6131 | 99.70 | 52.77 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.79 | 10.15 | 0.53 |
| 2| 825 | 35.88 | 11.39 | 0.56 |
| 3| 995 | 38.63 | 12.83 | 0.60 |
| 5| 1203 | 42.01 | 15.08 | 0.65 |
| 10| 2145 | 54.72 | 22.01 | 0.85 |
| 29| 4999 | 98.75 | 46.95 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5809 | 27.04 | 9.09 | 0.69 |
| 2| 5895 | 34.91 | 11.68 | 0.78 |
| 3| 6066 | 42.57 | 14.31 | 0.86 |
| 4| 6291 | 55.92 | 18.84 | 1.01 |
| 5| 6321 | 57.25 | 19.19 | 1.03 |
| 6| 6536 | 70.30 | 23.61 | 1.18 |
| 7| 6713 | 79.78 | 26.86 | 1.28 |
| 8| 6843 | 91.41 | 30.81 | 1.41 |
| 9| 6847 | 92.04 | 30.92 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2218 | 7158 | 98.05 | 37.58 | 1.53 |

