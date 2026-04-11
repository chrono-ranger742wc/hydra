--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-11 05:47:52.457368833 UTC |
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
| 1| 5834 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6646 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 28.80 | 9.07 | 0.78 |
| 43| 14286 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2181 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.33 | 9.64 | 0.52 |
| 3 | 170 | 751 | 40.18 | 11.71 | 0.59 |
| 4 | 227 | 858 | 49.59 | 14.30 | 0.69 |
| 5 | 282 | 969 | 59.50 | 17.09 | 0.80 |
| 6 | 337 | 1081 | 69.84 | 19.92 | 0.91 |
| 7 | 395 | 1192 | 73.94 | 21.29 | 0.95 |
| 8 | 450 | 1303 | 87.01 | 24.80 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1810 | 24.29 | 7.69 | 0.48 |
| 2| 1946 | 25.55 | 8.71 | 0.51 |
| 3| 2018 | 26.36 | 9.59 | 0.52 |
| 5| 2277 | 29.05 | 11.69 | 0.57 |
| 10| 3129 | 41.05 | 18.36 | 0.75 |
| 40| 7562 | 96.88 | 53.87 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 613 | 22.84 | 7.39 | 0.42 |
| 2| 799 | 25.52 | 8.79 | 0.45 |
| 3| 857 | 24.11 | 9.04 | 0.45 |
| 5| 1297 | 30.95 | 12.31 | 0.55 |
| 10| 2057 | 40.08 | 18.18 | 0.70 |
| 43| 6622 | 97.30 | 56.10 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 27.54 | 8.47 | 0.46 |
| 2| 771 | 28.51 | 9.39 | 0.48 |
| 3| 957 | 30.90 | 10.74 | 0.52 |
| 5| 1257 | 36.99 | 13.77 | 0.60 |
| 10| 1882 | 46.09 | 19.63 | 0.75 |
| 37| 6063 | 98.55 | 52.42 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.87 | 10.16 | 0.53 |
| 2| 760 | 35.17 | 11.17 | 0.55 |
| 3| 947 | 37.95 | 12.63 | 0.59 |
| 5| 1416 | 44.07 | 15.71 | 0.68 |
| 10| 2027 | 53.99 | 21.79 | 0.83 |
| 29| 4781 | 97.31 | 46.46 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5842 | 26.96 | 9.06 | 0.69 |
| 2| 6005 | 36.96 | 12.46 | 0.80 |
| 3| 6070 | 45.30 | 15.25 | 0.89 |
| 4| 6243 | 53.83 | 18.05 | 0.99 |
| 5| 6423 | 65.08 | 21.95 | 1.12 |
| 6| 6603 | 70.08 | 23.60 | 1.18 |
| 7| 6851 | 84.32 | 28.40 | 1.34 |
| 8| 6875 | 89.38 | 30.12 | 1.39 |
| 9| 6992 | 99.21 | 33.41 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 56 | 5867 | 20.96 | 7.13 | 0.63 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 39 | 2221 | 7160 | 98.93 | 37.88 | 1.54 |

