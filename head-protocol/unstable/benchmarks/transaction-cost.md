--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-10 05:58:16.525507667 UTC |
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
| 1| 5837 | 10.38 | 3.29 | 0.51 |
| 2| 6038 | 12.23 | 3.86 | 0.54 |
| 3| 6236 | 14.50 | 4.58 | 0.57 |
| 5| 6640 | 18.60 | 5.87 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 171 | 751 | 41.51 | 12.00 | 0.61 |
| 4 | 227 | 858 | 47.86 | 13.93 | 0.68 |
| 5 | 284 | 969 | 57.84 | 16.69 | 0.78 |
| 6 | 339 | 1081 | 69.49 | 19.83 | 0.90 |
| 7 | 395 | 1192 | 74.27 | 21.41 | 0.96 |
| 8 | 451 | 1307 | 84.90 | 24.35 | 1.07 |
| 9 | 506 | 1414 | 93.69 | 26.90 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.29 | 7.69 | 0.48 |
| 2| 1969 | 26.58 | 9.01 | 0.52 |
| 3| 2109 | 28.46 | 10.18 | 0.55 |
| 5| 2322 | 29.84 | 11.92 | 0.58 |
| 10| 3139 | 41.11 | 18.38 | 0.75 |
| 43| 7727 | 97.36 | 56.00 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.84 | 7.39 | 0.41 |
| 2| 718 | 22.52 | 7.93 | 0.42 |
| 3| 872 | 25.13 | 9.34 | 0.46 |
| 5| 1257 | 31.21 | 12.39 | 0.55 |
| 10| 1937 | 37.32 | 17.41 | 0.66 |
| 41| 6597 | 96.40 | 54.53 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 667 | 29.13 | 8.90 | 0.48 |
| 2| 770 | 30.91 | 10.06 | 0.51 |
| 3| 1006 | 31.69 | 10.98 | 0.53 |
| 5| 1221 | 37.02 | 13.77 | 0.60 |
| 10| 2009 | 44.27 | 19.17 | 0.73 |
| 36| 6137 | 98.87 | 51.88 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 673 | 33.87 | 10.16 | 0.53 |
| 2| 760 | 35.17 | 11.17 | 0.55 |
| 3| 938 | 37.87 | 12.61 | 0.59 |
| 5| 1358 | 43.27 | 15.47 | 0.67 |
| 10| 2079 | 54.96 | 22.07 | 0.84 |
| 29| 4843 | 98.24 | 46.75 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5839 | 26.96 | 9.06 | 0.69 |
| 2| 5892 | 34.87 | 11.65 | 0.78 |
| 3| 6107 | 44.76 | 15.07 | 0.89 |
| 4| 6180 | 50.66 | 16.98 | 0.95 |
| 5| 6366 | 63.00 | 21.16 | 1.09 |
| 6| 6664 | 74.28 | 25.09 | 1.22 |
| 7| 6721 | 79.24 | 26.68 | 1.28 |
| 8| 6869 | 88.52 | 29.76 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 283 | 6003 | 30.23 | 10.73 | 0.74 |
| 10 | 20 | 1138 | 6512 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1705 | 6851 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2219 | 7159 | 98.49 | 37.73 | 1.53 |

