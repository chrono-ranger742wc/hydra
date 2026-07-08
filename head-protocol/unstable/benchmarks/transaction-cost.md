--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-08 06:59:56.96545454 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.44 | 3.94 | 0.54 |
| 3| 6239 | 14.90 | 4.72 | 0.58 |
| 5| 6638 | 18.43 | 5.81 | 0.63 |
| 10| 7650 | 28.94 | 9.11 | 0.79 |
| 43| 14282 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10072 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.63 | 0.52 |
| 3 | 169 | 751 | 43.73 | 12.51 | 0.63 |
| 4 | 226 | 858 | 49.44 | 14.26 | 0.69 |
| 5 | 281 | 969 | 57.63 | 16.64 | 0.78 |
| 6 | 339 | 1085 | 66.10 | 19.13 | 0.87 |
| 7 | 394 | 1192 | 86.91 | 24.53 | 1.08 |
| 8 | 448 | 1303 | 95.52 | 26.89 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1809 | 24.00 | 7.62 | 0.48 |
| 2| 1989 | 26.87 | 9.07 | 0.52 |
| 3| 2017 | 25.87 | 9.47 | 0.52 |
| 5| 2279 | 29.42 | 11.78 | 0.57 |
| 10| 3110 | 40.31 | 18.18 | 0.74 |
| 41| 7595 | 97.19 | 54.62 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 628 | 22.81 | 7.37 | 0.42 |
| 2| 803 | 25.20 | 8.70 | 0.45 |
| 3| 879 | 25.55 | 9.49 | 0.46 |
| 5| 1196 | 29.81 | 11.99 | 0.53 |
| 10| 2040 | 39.83 | 18.12 | 0.69 |
| 41| 6490 | 94.36 | 53.96 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 27.50 | 8.46 | 0.46 |
| 2| 834 | 31.54 | 10.25 | 0.52 |
| 3| 1021 | 31.54 | 10.94 | 0.53 |
| 5| 1299 | 35.61 | 13.43 | 0.59 |
| 10| 2136 | 46.14 | 19.75 | 0.76 |
| 36| 5914 | 97.04 | 51.35 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 33.87 | 10.16 | 0.53 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 982 | 38.62 | 12.83 | 0.60 |
| 5| 1345 | 44.07 | 15.71 | 0.68 |
| 10| 1919 | 52.74 | 21.40 | 0.82 |
| 28| 4828 | 96.50 | 45.65 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5813 | 27.00 | 9.08 | 0.69 |
| 2| 5846 | 31.48 | 10.47 | 0.74 |
| 3| 5997 | 40.31 | 13.43 | 0.84 |
| 4| 6333 | 57.09 | 19.29 | 1.03 |
| 5| 6511 | 64.83 | 21.89 | 1.12 |
| 6| 6501 | 67.19 | 22.61 | 1.14 |
| 7| 6670 | 81.32 | 27.46 | 1.30 |
| 8| 6922 | 93.52 | 31.48 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 17.86 | 5.96 | 0.59 |
| 10 | 5 | 284 | 6003 | 29.98 | 10.65 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1138 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1708 | 6854 | 81.37 | 30.91 | 1.33 |
| 10 | 38 | 2164 | 7127 | 96.63 | 36.99 | 1.51 |

