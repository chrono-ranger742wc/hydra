--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-11 05:39:43.753295439 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6239 | 14.71 | 4.65 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 28.90 | 9.10 | 0.79 |
| 43| 14285 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 40.25 | 11.69 | 0.59 |
| 4 | 226 | 858 | 52.27 | 14.94 | 0.72 |
| 5 | 283 | 969 | 63.87 | 18.13 | 0.84 |
| 6 | 338 | 1081 | 74.98 | 21.19 | 0.96 |
| 7 | 393 | 1192 | 84.93 | 24.05 | 1.06 |
| 8 | 448 | 1303 | 88.77 | 25.22 | 1.11 |
| 9 | 504 | 1414 | 96.58 | 27.70 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1800 | 24.37 | 7.71 | 0.48 |
| 2| 1886 | 24.77 | 8.48 | 0.49 |
| 3| 2073 | 27.03 | 9.79 | 0.53 |
| 5| 2410 | 31.41 | 12.34 | 0.60 |
| 10| 3031 | 38.91 | 17.76 | 0.73 |
| 39| 7373 | 95.42 | 52.78 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 22.54 | 7.30 | 0.41 |
| 2| 703 | 22.62 | 7.96 | 0.42 |
| 3| 1020 | 28.21 | 10.20 | 0.50 |
| 5| 1276 | 30.75 | 12.26 | 0.54 |
| 10| 2027 | 39.97 | 18.19 | 0.69 |
| 41| 6552 | 97.56 | 54.83 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.83 | 8.26 | 0.45 |
| 2| 770 | 28.51 | 9.39 | 0.48 |
| 3| 1016 | 31.58 | 10.95 | 0.53 |
| 5| 1278 | 35.05 | 13.25 | 0.59 |
| 10| 2086 | 48.22 | 20.29 | 0.78 |
| 36| 5703 | 95.44 | 50.80 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 690 | 33.87 | 10.16 | 0.53 |
| 2| 764 | 35.21 | 11.18 | 0.55 |
| 3| 1001 | 38.66 | 12.84 | 0.60 |
| 5| 1162 | 41.15 | 14.83 | 0.64 |
| 10| 1880 | 52.10 | 21.22 | 0.81 |
| 30| 5009 | 99.56 | 47.78 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5963 | 35.88 | 12.08 | 0.79 |
| 3| 6046 | 43.62 | 14.65 | 0.87 |
| 4| 6220 | 53.09 | 17.89 | 0.98 |
| 5| 6389 | 60.48 | 20.31 | 1.07 |
| 6| 6602 | 74.18 | 24.98 | 1.22 |
| 7| 6884 | 85.77 | 29.02 | 1.36 |
| 8| 6609 | 81.38 | 27.21 | 1.29 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1140 | 6515 | 59.10 | 22.22 | 1.07 |
| 10 | 39 | 2217 | 7156 | 99.38 | 38.04 | 1.54 |

