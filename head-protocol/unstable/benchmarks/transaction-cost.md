--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-03 05:39:47.121482615 UTC |
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
| 1| 5837 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6638 | 18.71 | 5.91 | 0.64 |
| 10| 7647 | 29.12 | 9.18 | 0.79 |
| 43| 14283 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10053 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 171 | 747 | 39.89 | 11.59 | 0.59 |
| 4 | 225 | 858 | 48.09 | 13.94 | 0.68 |
| 5 | 282 | 969 | 62.79 | 17.90 | 0.83 |
| 6 | 337 | 1081 | 71.10 | 20.29 | 0.92 |
| 7 | 394 | 1192 | 84.89 | 24.04 | 1.06 |
| 8 | 450 | 1303 | 81.43 | 23.62 | 1.04 |
| 9 | 505 | 1414 | 93.87 | 26.95 | 1.17 |
| 10 | 560 | 1525 | 95.95 | 27.71 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1822 | 23.92 | 7.60 | 0.48 |
| 2| 1953 | 25.39 | 8.68 | 0.50 |
| 3| 2127 | 27.93 | 10.05 | 0.54 |
| 5| 2385 | 31.07 | 12.26 | 0.59 |
| 10| 3160 | 41.60 | 18.54 | 0.76 |
| 39| 7310 | 94.26 | 52.46 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 661 | 22.54 | 7.31 | 0.41 |
| 2| 785 | 24.32 | 8.46 | 0.44 |
| 3| 901 | 25.56 | 9.48 | 0.46 |
| 5| 1155 | 28.07 | 11.49 | 0.51 |
| 10| 2103 | 42.72 | 18.94 | 0.72 |
| 40| 6637 | 97.99 | 54.31 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 601 | 28.46 | 8.69 | 0.47 |
| 2| 805 | 29.22 | 9.61 | 0.49 |
| 3| 974 | 33.39 | 11.43 | 0.55 |
| 5| 1192 | 36.38 | 13.58 | 0.59 |
| 10| 2041 | 45.65 | 19.59 | 0.75 |
| 36| 5967 | 97.98 | 51.58 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 683 | 33.87 | 10.16 | 0.53 |
| 2| 821 | 35.92 | 11.40 | 0.56 |
| 3| 1025 | 38.58 | 12.82 | 0.60 |
| 5| 1211 | 41.89 | 15.05 | 0.65 |
| 10| 1915 | 53.11 | 21.51 | 0.82 |
| 30| 4945 | 99.57 | 47.74 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5806 | 26.97 | 9.06 | 0.69 |
| 2| 5941 | 36.04 | 12.10 | 0.79 |
| 3| 6096 | 46.05 | 15.52 | 0.90 |
| 4| 6298 | 54.42 | 18.36 | 1.00 |
| 5| 6320 | 61.88 | 20.78 | 1.08 |
| 6| 6392 | 65.27 | 21.85 | 1.12 |
| 7| 6792 | 85.22 | 28.75 | 1.34 |
| 8| 6849 | 91.52 | 30.86 | 1.41 |
| 9| 7003 | 98.70 | 33.27 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.96 | 7.13 | 0.63 |
| 10 | 20 | 1138 | 6512 | 59.66 | 22.42 | 1.08 |
| 10 | 30 | 1708 | 6854 | 81.55 | 30.98 | 1.33 |
| 10 | 39 | 2221 | 7161 | 98.49 | 37.73 | 1.53 |

