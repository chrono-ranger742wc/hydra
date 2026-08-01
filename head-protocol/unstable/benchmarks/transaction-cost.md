--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-01 07:01:44.861837984 UTC |
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
| 1| 5838 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6238 | 14.69 | 4.65 | 0.58 |
| 5| 6645 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.40 | 9.28 | 0.79 |
| 43| 14282 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10059 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 33.18 | 9.60 | 0.52 |
| 3 | 170 | 747 | 41.57 | 12.05 | 0.61 |
| 4 | 227 | 858 | 53.54 | 15.24 | 0.73 |
| 5 | 284 | 969 | 59.20 | 16.98 | 0.79 |
| 6 | 339 | 1081 | 64.56 | 18.73 | 0.85 |
| 7 | 395 | 1192 | 78.40 | 22.44 | 1.00 |
| 8 | 450 | 1303 | 91.94 | 26.04 | 1.14 |
| 9 | 505 | 1414 | 93.01 | 26.79 | 1.16 |
| 10 | 561 | 1525 | 96.40 | 27.88 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1882 | 24.44 | 8.41 | 0.49 |
| 3| 2132 | 28.01 | 10.07 | 0.54 |
| 5| 2456 | 32.60 | 12.67 | 0.61 |
| 10| 3224 | 43.24 | 18.97 | 0.78 |
| 38| 7350 | 95.31 | 52.13 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 22.81 | 7.37 | 0.42 |
| 2| 860 | 25.29 | 8.74 | 0.46 |
| 3| 967 | 26.57 | 9.76 | 0.48 |
| 5| 1250 | 30.14 | 12.06 | 0.54 |
| 10| 1980 | 39.43 | 18.01 | 0.69 |
| 42| 6756 | 99.19 | 55.98 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 29.17 | 8.91 | 0.48 |
| 2| 824 | 29.19 | 9.60 | 0.49 |
| 3| 902 | 30.26 | 10.55 | 0.51 |
| 5| 1330 | 38.33 | 14.18 | 0.62 |
| 10| 2047 | 44.67 | 19.31 | 0.74 |
| 35| 5718 | 99.63 | 51.31 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 676 | 33.83 | 10.15 | 0.53 |
| 2| 811 | 35.85 | 11.38 | 0.56 |
| 3| 987 | 38.66 | 12.84 | 0.60 |
| 5| 1358 | 43.31 | 15.48 | 0.67 |
| 10| 1994 | 53.42 | 21.61 | 0.83 |
| 30| 4784 | 96.84 | 46.95 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5836 | 26.96 | 9.06 | 0.69 |
| 2| 5958 | 35.96 | 12.06 | 0.79 |
| 3| 6080 | 44.91 | 15.13 | 0.89 |
| 4| 6282 | 54.51 | 18.38 | 1.00 |
| 5| 6520 | 65.53 | 22.17 | 1.13 |
| 6| 6501 | 73.72 | 24.78 | 1.21 |
| 7| 6756 | 79.53 | 26.79 | 1.28 |
| 8| 6779 | 88.56 | 29.78 | 1.38 |
| 9| 6897 | 95.42 | 32.16 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.38 | 6.48 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1137 | 6512 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1706 | 6852 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2225 | 7164 | 98.93 | 37.88 | 1.54 |

