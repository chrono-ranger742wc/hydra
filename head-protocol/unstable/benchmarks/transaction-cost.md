--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-04 05:55:57.243695899 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.63 | 4.00 | 0.55 |
| 3| 6238 | 14.38 | 4.54 | 0.57 |
| 5| 6641 | 19.00 | 6.01 | 0.64 |
| 10| 7646 | 28.90 | 9.10 | 0.79 |
| 43| 14279 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2176 | 12.13 | 7.25 | 0.40 |
| 54| 10042 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 41.35 | 11.96 | 0.60 |
| 4 | 227 | 858 | 50.94 | 14.67 | 0.71 |
| 5 | 281 | 969 | 59.83 | 17.17 | 0.80 |
| 6 | 339 | 1081 | 65.00 | 18.88 | 0.86 |
| 7 | 394 | 1192 | 84.25 | 23.80 | 1.05 |
| 8 | 449 | 1303 | 92.82 | 26.40 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1822 | 24.00 | 7.62 | 0.48 |
| 2| 1990 | 26.87 | 9.07 | 0.52 |
| 3| 2064 | 27.02 | 9.79 | 0.53 |
| 5| 2446 | 31.96 | 12.51 | 0.61 |
| 10| 3178 | 41.27 | 18.44 | 0.76 |
| 39| 7459 | 96.38 | 53.11 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 22.81 | 7.37 | 0.42 |
| 2| 722 | 22.52 | 7.93 | 0.42 |
| 3| 967 | 26.84 | 9.83 | 0.48 |
| 5| 1358 | 33.24 | 12.94 | 0.57 |
| 10| 1919 | 37.44 | 17.44 | 0.66 |
| 40| 6632 | 99.74 | 54.77 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.83 | 8.26 | 0.45 |
| 2| 736 | 30.27 | 9.86 | 0.50 |
| 3| 937 | 33.02 | 11.32 | 0.54 |
| 5| 1243 | 36.87 | 13.74 | 0.60 |
| 10| 2075 | 45.76 | 19.62 | 0.75 |
| 36| 5989 | 97.98 | 51.60 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 33.87 | 10.16 | 0.53 |
| 2| 849 | 36.48 | 11.58 | 0.57 |
| 3| 1009 | 38.55 | 12.81 | 0.60 |
| 5| 1352 | 43.13 | 15.44 | 0.67 |
| 10| 2002 | 53.46 | 21.62 | 0.83 |
| 30| 4939 | 99.78 | 47.85 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.93 | 7.56 | 0.64 |
| 2| 5994 | 36.88 | 12.45 | 0.80 |
| 3| 6072 | 43.80 | 14.68 | 0.88 |
| 4| 6354 | 56.30 | 19.01 | 1.02 |
| 5| 6435 | 61.38 | 20.68 | 1.08 |
| 6| 6416 | 66.35 | 22.26 | 1.13 |
| 7| 6672 | 75.86 | 25.50 | 1.24 |
| 8| 7090 | 94.63 | 32.10 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 20.70 | 6.93 | 0.62 |
| 10 | 1 | 57 | 5868 | 20.96 | 7.13 | 0.63 |
| 10 | 5 | 285 | 6004 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 38 | 2165 | 7128 | 96.44 | 36.92 | 1.51 |

