--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-05 06:07:53.413331369 UTC |
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
| 1| 5838 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.42 | 3.93 | 0.54 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 738 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2165 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 170 | 751 | 42.62 | 12.24 | 0.62 |
| 4 | 226 | 858 | 52.29 | 14.94 | 0.72 |
| 5 | 284 | 969 | 59.22 | 17.02 | 0.79 |
| 6 | 338 | 1081 | 75.81 | 21.46 | 0.96 |
| 7 | 396 | 1192 | 85.19 | 24.16 | 1.07 |
| 8 | 450 | 1303 | 84.62 | 24.23 | 1.07 |
| 9 | 504 | 1414 | 93.19 | 26.73 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 22.92 | 7.32 | 0.47 |
| 2| 1882 | 24.43 | 8.40 | 0.49 |
| 3| 2013 | 25.87 | 9.47 | 0.52 |
| 5| 2395 | 31.08 | 12.26 | 0.60 |
| 10| 3216 | 42.05 | 18.65 | 0.77 |
| 41| 7816 | 99.29 | 55.23 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.84 | 7.38 | 0.42 |
| 2| 746 | 24.31 | 8.45 | 0.44 |
| 3| 925 | 26.71 | 9.81 | 0.48 |
| 5| 1161 | 28.12 | 11.50 | 0.51 |
| 10| 1929 | 38.26 | 17.69 | 0.67 |
| 40| 6518 | 99.40 | 54.62 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 705 | 27.50 | 8.46 | 0.46 |
| 2| 840 | 31.62 | 10.27 | 0.52 |
| 3| 950 | 30.82 | 10.73 | 0.52 |
| 5| 1221 | 37.06 | 13.79 | 0.60 |
| 10| 2145 | 46.55 | 19.86 | 0.76 |
| 38| 6166 | 99.59 | 53.36 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 714 | 33.87 | 10.16 | 0.53 |
| 2| 825 | 35.88 | 11.39 | 0.56 |
| 3| 987 | 38.59 | 12.82 | 0.60 |
| 5| 1158 | 41.18 | 14.84 | 0.64 |
| 10| 2055 | 54.32 | 21.89 | 0.84 |
| 28| 4640 | 93.77 | 44.82 | 1.44 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5796 | 27.09 | 9.08 | 0.69 |
| 2| 5962 | 35.80 | 12.04 | 0.79 |
| 3| 6108 | 44.84 | 15.05 | 0.89 |
| 4| 6219 | 53.82 | 18.08 | 0.99 |
| 5| 6467 | 65.03 | 21.93 | 1.12 |
| 6| 6630 | 75.42 | 25.54 | 1.24 |
| 7| 6593 | 77.98 | 26.20 | 1.26 |
| 8| 6807 | 89.79 | 30.12 | 1.39 |
| 9| 6956 | 96.42 | 32.44 | 1.47 |
| 10| 6850 | 98.78 | 33.11 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1138 | 6513 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1708 | 6855 | 80.41 | 30.59 | 1.32 |
| 10 | 39 | 2219 | 7158 | 98.93 | 37.88 | 1.54 |

