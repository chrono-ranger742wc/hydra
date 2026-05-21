--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-21 08:16:53.551835731 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.46 | 3.94 | 0.55 |
| 3| 6236 | 14.69 | 4.65 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10063 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.23 | 9.37 | 0.51 |
| 3 | 170 | 747 | 40.14 | 11.65 | 0.59 |
| 4 | 226 | 858 | 51.18 | 14.73 | 0.71 |
| 5 | 284 | 974 | 64.69 | 18.33 | 0.85 |
| 6 | 340 | 1081 | 73.73 | 20.96 | 0.94 |
| 7 | 395 | 1192 | 82.15 | 23.25 | 1.03 |
| 8 | 448 | 1303 | 98.51 | 27.66 | 1.20 |
| 9 | 507 | 1414 | 92.70 | 26.60 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1817 | 24.37 | 7.71 | 0.48 |
| 2| 1886 | 24.47 | 8.41 | 0.49 |
| 3| 2017 | 26.32 | 9.58 | 0.52 |
| 5| 2457 | 32.60 | 12.67 | 0.61 |
| 10| 3129 | 40.75 | 18.29 | 0.75 |
| 40| 7584 | 97.49 | 54.03 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 606 | 22.57 | 7.30 | 0.41 |
| 2| 700 | 22.62 | 7.96 | 0.42 |
| 3| 934 | 25.76 | 9.53 | 0.47 |
| 5| 1264 | 30.00 | 12.03 | 0.53 |
| 10| 2044 | 38.65 | 17.78 | 0.68 |
| 41| 6737 | 99.52 | 55.38 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.46 | 8.69 | 0.47 |
| 2| 770 | 28.55 | 9.40 | 0.48 |
| 3| 902 | 30.26 | 10.55 | 0.51 |
| 5| 1225 | 37.10 | 13.80 | 0.60 |
| 10| 2141 | 46.85 | 19.97 | 0.77 |
| 37| 5996 | 97.60 | 52.14 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 33.87 | 10.16 | 0.53 |
| 2| 869 | 36.64 | 11.62 | 0.57 |
| 3| 950 | 37.84 | 12.60 | 0.59 |
| 5| 1310 | 43.40 | 15.50 | 0.67 |
| 10| 2059 | 53.87 | 21.76 | 0.83 |
| 28| 4779 | 96.37 | 45.60 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5894 | 34.79 | 11.64 | 0.77 |
| 3| 5992 | 41.33 | 13.85 | 0.85 |
| 4| 6118 | 50.51 | 16.94 | 0.95 |
| 5| 6362 | 63.05 | 21.17 | 1.09 |
| 6| 6634 | 76.01 | 25.66 | 1.24 |
| 7| 6762 | 83.85 | 28.25 | 1.33 |
| 8| 6963 | 94.56 | 31.98 | 1.45 |
| 9| 7082 | 99.12 | 33.34 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 56 | 5867 | 19.45 | 6.61 | 0.61 |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 571 | 6175 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6513 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2220 | 7160 | 99.82 | 38.19 | 1.55 |

