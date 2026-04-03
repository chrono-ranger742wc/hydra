--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-03 06:05:47.331450543 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.67 | 4.01 | 0.55 |
| 3| 6243 | 14.76 | 4.67 | 0.58 |
| 5| 6638 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 29.09 | 9.17 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10080 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 640 | 33.33 | 9.64 | 0.52 |
| 3 | 170 | 751 | 40.00 | 11.63 | 0.59 |
| 4 | 226 | 858 | 53.71 | 15.28 | 0.73 |
| 5 | 284 | 969 | 64.44 | 18.24 | 0.85 |
| 6 | 337 | 1081 | 71.89 | 20.52 | 0.93 |
| 7 | 394 | 1192 | 74.86 | 21.64 | 0.96 |
| 8 | 449 | 1303 | 82.85 | 23.96 | 1.05 |
| 9 | 506 | 1414 | 90.97 | 26.31 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1791 | 23.92 | 7.60 | 0.48 |
| 2| 1931 | 25.51 | 8.70 | 0.50 |
| 3| 2213 | 29.09 | 10.37 | 0.56 |
| 5| 2462 | 32.56 | 12.66 | 0.61 |
| 10| 3216 | 42.40 | 18.75 | 0.77 |
| 38| 7216 | 91.42 | 51.05 | 1.57 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 619 | 22.57 | 7.32 | 0.41 |
| 2| 853 | 25.29 | 8.73 | 0.46 |
| 3| 1078 | 28.04 | 10.17 | 0.50 |
| 5| 1297 | 30.75 | 12.26 | 0.54 |
| 10| 1925 | 37.49 | 17.47 | 0.66 |
| 43| 6628 | 95.20 | 55.50 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 27.50 | 8.46 | 0.46 |
| 2| 877 | 29.97 | 9.84 | 0.50 |
| 3| 992 | 33.36 | 11.42 | 0.55 |
| 5| 1282 | 37.74 | 13.99 | 0.61 |
| 10| 1899 | 46.50 | 19.75 | 0.75 |
| 36| 5993 | 98.29 | 51.70 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 33.83 | 10.15 | 0.53 |
| 2| 862 | 36.56 | 11.60 | 0.57 |
| 3| 990 | 38.59 | 12.82 | 0.60 |
| 5| 1339 | 43.25 | 15.47 | 0.67 |
| 10| 2149 | 55.36 | 22.21 | 0.85 |
| 29| 4828 | 98.51 | 46.84 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5792 | 26.97 | 9.05 | 0.69 |
| 2| 5957 | 35.99 | 12.09 | 0.79 |
| 3| 6098 | 44.76 | 15.06 | 0.89 |
| 4| 6093 | 48.94 | 16.37 | 0.93 |
| 5| 6343 | 62.99 | 21.13 | 1.09 |
| 6| 6553 | 73.42 | 24.74 | 1.21 |
| 7| 6777 | 85.17 | 28.72 | 1.34 |
| 8| 7018 | 91.82 | 30.98 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 19.45 | 6.61 | 0.61 |
| 10 | 10 | 569 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1139 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 40 | 2279 | 7196 | 99.66 | 38.24 | 1.55 |

