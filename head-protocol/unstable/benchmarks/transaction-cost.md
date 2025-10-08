--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-08 04:39:54.823494588 UTC |
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
| 1| 5836 | 10.59 | 3.36 | 0.52 |
| 2| 6037 | 12.41 | 3.92 | 0.54 |
| 3| 6239 | 14.31 | 4.52 | 0.57 |
| 5| 6645 | 18.88 | 5.97 | 0.64 |
| 10| 7647 | 29.11 | 9.17 | 0.79 |
| 43| 14282 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10050 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 171 | 747 | 42.62 | 12.24 | 0.62 |
| 4 | 226 | 858 | 49.72 | 14.35 | 0.69 |
| 5 | 283 | 969 | 64.25 | 18.23 | 0.84 |
| 6 | 337 | 1081 | 67.58 | 19.38 | 0.88 |
| 7 | 394 | 1192 | 79.26 | 22.70 | 1.01 |
| 8 | 448 | 1303 | 85.35 | 24.50 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1816 | 24.37 | 7.71 | 0.48 |
| 2| 1990 | 26.92 | 9.09 | 0.52 |
| 3| 2117 | 28.43 | 10.17 | 0.55 |
| 5| 2361 | 31.25 | 12.30 | 0.60 |
| 10| 3282 | 44.08 | 19.21 | 0.79 |
| 39| 7414 | 96.09 | 53.01 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 624 | 22.81 | 7.37 | 0.42 |
| 2| 791 | 24.25 | 8.44 | 0.44 |
| 3| 907 | 25.09 | 9.32 | 0.46 |
| 5| 1386 | 31.18 | 12.36 | 0.55 |
| 10| 1871 | 36.35 | 17.15 | 0.65 |
| 41| 6530 | 97.57 | 54.82 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 668 | 29.17 | 8.91 | 0.48 |
| 2| 736 | 30.27 | 9.86 | 0.50 |
| 3| 961 | 30.87 | 10.74 | 0.52 |
| 5| 1407 | 36.39 | 13.66 | 0.60 |
| 10| 2098 | 48.83 | 20.47 | 0.78 |
| 38| 6066 | 97.87 | 52.83 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 33.87 | 10.16 | 0.53 |
| 2| 824 | 35.81 | 11.37 | 0.56 |
| 3| 951 | 37.95 | 12.63 | 0.59 |
| 5| 1249 | 42.68 | 15.29 | 0.66 |
| 10| 2124 | 55.71 | 22.30 | 0.85 |
| 30| 4975 | 99.56 | 47.80 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5836 | 27.12 | 9.10 | 0.69 |
| 2| 5951 | 35.96 | 12.07 | 0.79 |
| 3| 6038 | 41.45 | 13.86 | 0.85 |
| 4| 6286 | 55.02 | 18.55 | 1.01 |
| 5| 6562 | 66.21 | 22.36 | 1.14 |
| 6| 6659 | 74.43 | 25.17 | 1.23 |
| 7| 6787 | 83.78 | 28.25 | 1.33 |
| 8| 6980 | 91.07 | 30.71 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 10 | 570 | 6175 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1138 | 6513 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 40 | 2276 | 7192 | 99.22 | 38.09 | 1.54 |
| 10 | 37 | 2108 | 7093 | 95.72 | 36.57 | 1.50 |

