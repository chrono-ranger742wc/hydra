--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-24 07:01:11.637031418 UTC |
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
| 1| 5837 | 10.40 | 3.30 | 0.51 |
| 2| 6038 | 12.61 | 4.00 | 0.55 |
| 3| 6243 | 14.97 | 4.75 | 0.58 |
| 5| 6638 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2175 | 12.13 | 7.25 | 0.40 |
| 54| 10041 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.32 | 9.66 | 0.52 |
| 3 | 170 | 747 | 43.53 | 12.46 | 0.62 |
| 4 | 228 | 858 | 52.58 | 15.04 | 0.72 |
| 5 | 283 | 974 | 62.53 | 17.81 | 0.83 |
| 6 | 339 | 1081 | 66.22 | 19.13 | 0.87 |
| 7 | 394 | 1192 | 73.92 | 21.28 | 0.95 |
| 8 | 452 | 1303 | 95.92 | 26.99 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1747 | 23.30 | 7.40 | 0.47 |
| 2| 1966 | 26.39 | 8.96 | 0.51 |
| 3| 2086 | 27.39 | 9.88 | 0.53 |
| 5| 2321 | 29.89 | 11.93 | 0.58 |
| 10| 3231 | 42.02 | 18.64 | 0.77 |
| 42| 7831 | 98.67 | 55.73 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 619 | 22.53 | 7.30 | 0.41 |
| 2| 796 | 25.16 | 8.70 | 0.45 |
| 3| 948 | 26.65 | 9.78 | 0.48 |
| 5| 1255 | 30.90 | 12.30 | 0.54 |
| 10| 1903 | 37.74 | 17.52 | 0.67 |
| 39| 6480 | 99.55 | 54.06 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 687 | 27.51 | 8.47 | 0.46 |
| 2| 862 | 29.93 | 9.83 | 0.50 |
| 3| 982 | 30.90 | 10.74 | 0.52 |
| 5| 1401 | 39.17 | 14.43 | 0.63 |
| 10| 2090 | 47.97 | 20.21 | 0.78 |
| 35| 5720 | 94.29 | 49.87 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 33.83 | 10.16 | 0.53 |
| 2| 768 | 35.21 | 11.18 | 0.55 |
| 3| 996 | 38.58 | 12.82 | 0.60 |
| 5| 1318 | 43.28 | 15.47 | 0.67 |
| 10| 2014 | 54.13 | 21.82 | 0.83 |
| 28| 4915 | 98.22 | 46.14 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5803 | 27.13 | 9.09 | 0.69 |
| 2| 5965 | 35.90 | 12.07 | 0.79 |
| 3| 6114 | 44.52 | 14.97 | 0.89 |
| 4| 6282 | 54.68 | 18.44 | 1.00 |
| 5| 6254 | 59.52 | 19.95 | 1.05 |
| 6| 6491 | 69.56 | 23.38 | 1.17 |
| 7| 6751 | 84.37 | 28.44 | 1.33 |
| 8| 6741 | 85.91 | 28.91 | 1.35 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.08 | 6.83 | 0.62 |
| 10 | 5 | 284 | 6003 | 28.65 | 10.19 | 0.72 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 30 | 1708 | 6854 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2220 | 7159 | 98.49 | 37.73 | 1.53 |

