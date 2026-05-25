--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-25 08:44:07.165434708 UTC |
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
| 2| 6041 | 12.53 | 3.97 | 0.55 |
| 3| 6239 | 14.84 | 4.71 | 0.58 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7644 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 171 | 747 | 42.62 | 12.25 | 0.62 |
| 4 | 226 | 862 | 53.39 | 15.25 | 0.73 |
| 5 | 282 | 969 | 63.91 | 18.17 | 0.84 |
| 6 | 339 | 1081 | 69.92 | 19.98 | 0.91 |
| 7 | 393 | 1192 | 72.85 | 21.12 | 0.94 |
| 8 | 451 | 1303 | 82.97 | 23.94 | 1.05 |
| 9 | 504 | 1414 | 88.13 | 25.46 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1788 | 24.00 | 7.62 | 0.48 |
| 2| 1928 | 25.76 | 8.76 | 0.51 |
| 3| 2120 | 28.10 | 10.09 | 0.54 |
| 5| 2321 | 29.81 | 11.91 | 0.58 |
| 10| 3197 | 41.86 | 18.60 | 0.76 |
| 39| 7456 | 94.85 | 52.67 | 1.62 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 605 | 22.53 | 7.30 | 0.41 |
| 2| 794 | 24.32 | 8.46 | 0.44 |
| 3| 835 | 24.13 | 9.06 | 0.45 |
| 5| 1224 | 30.07 | 12.04 | 0.53 |
| 10| 1991 | 38.44 | 17.72 | 0.68 |
| 42| 6602 | 96.44 | 55.22 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 27.47 | 8.46 | 0.46 |
| 2| 852 | 31.65 | 10.28 | 0.52 |
| 3| 998 | 31.50 | 10.93 | 0.53 |
| 5| 1134 | 35.63 | 13.35 | 0.58 |
| 10| 2142 | 49.04 | 20.54 | 0.79 |
| 36| 6033 | 98.05 | 51.62 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 675 | 33.79 | 10.15 | 0.53 |
| 2| 833 | 35.89 | 11.39 | 0.56 |
| 3| 1027 | 38.59 | 12.82 | 0.60 |
| 5| 1301 | 43.36 | 15.49 | 0.67 |
| 10| 2203 | 55.59 | 22.27 | 0.86 |
| 30| 4980 | 99.97 | 47.92 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5826 | 27.08 | 9.09 | 0.69 |
| 2| 5924 | 34.83 | 11.65 | 0.78 |
| 3| 6043 | 41.45 | 13.87 | 0.85 |
| 4| 6258 | 55.29 | 18.60 | 1.01 |
| 5| 6403 | 61.53 | 20.74 | 1.08 |
| 6| 6537 | 73.28 | 24.62 | 1.21 |
| 7| 6476 | 76.99 | 25.78 | 1.24 |
| 8| 7004 | 93.76 | 31.60 | 1.44 |
| 9| 7129 | 98.81 | 33.32 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 20.07 | 6.71 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 30 | 1708 | 6854 | 80.67 | 30.67 | 1.32 |
| 10 | 39 | 2222 | 7161 | 97.61 | 37.43 | 1.52 |

