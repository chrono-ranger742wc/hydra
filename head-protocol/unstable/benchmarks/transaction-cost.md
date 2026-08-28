--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-28 16:28:42.151308624 UTC |
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
| 2| 6037 | 12.92 | 4.11 | 0.55 |
| 3| 6239 | 15.16 | 4.82 | 0.58 |
| 5| 6640 | 18.96 | 6.00 | 0.64 |
| 10| 7647 | 28.73 | 9.04 | 0.78 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 40.12 | 11.65 | 0.59 |
| 4 | 226 | 858 | 53.90 | 15.35 | 0.73 |
| 5 | 283 | 969 | 58.00 | 16.73 | 0.78 |
| 6 | 337 | 1081 | 64.88 | 18.85 | 0.86 |
| 7 | 394 | 1192 | 86.21 | 24.35 | 1.07 |
| 8 | 448 | 1303 | 82.95 | 23.98 | 1.05 |
| 9 | 505 | 1414 | 89.11 | 25.86 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.00 | 7.62 | 0.48 |
| 2| 1929 | 25.47 | 8.69 | 0.50 |
| 3| 2168 | 29.09 | 10.37 | 0.56 |
| 5| 2353 | 29.85 | 11.92 | 0.58 |
| 10| 3299 | 44.25 | 19.26 | 0.79 |
| 39| 7487 | 95.80 | 52.93 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 22.57 | 7.32 | 0.41 |
| 2| 793 | 25.16 | 8.69 | 0.45 |
| 3| 959 | 26.06 | 9.59 | 0.47 |
| 5| 1184 | 29.03 | 11.77 | 0.52 |
| 10| 2184 | 41.75 | 18.68 | 0.72 |
| 41| 6446 | 95.12 | 54.16 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 26.83 | 8.26 | 0.45 |
| 2| 840 | 29.22 | 9.61 | 0.49 |
| 3| 1000 | 31.65 | 10.97 | 0.53 |
| 5| 1252 | 34.89 | 13.21 | 0.58 |
| 10| 2209 | 46.61 | 19.91 | 0.77 |
| 35| 6076 | 98.58 | 51.20 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 33.87 | 10.16 | 0.53 |
| 2| 891 | 36.60 | 11.61 | 0.57 |
| 3| 1070 | 39.22 | 13.02 | 0.61 |
| 5| 1256 | 42.53 | 15.25 | 0.66 |
| 10| 2047 | 53.83 | 21.75 | 0.83 |
| 28| 4698 | 95.80 | 45.42 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5793 | 27.13 | 9.09 | 0.69 |
| 2| 5864 | 32.65 | 10.89 | 0.75 |
| 3| 5943 | 38.02 | 12.65 | 0.81 |
| 4| 6241 | 51.47 | 17.28 | 0.97 |
| 5| 6371 | 62.91 | 21.18 | 1.09 |
| 6| 6604 | 75.16 | 25.34 | 1.23 |
| 7| 6729 | 82.59 | 27.86 | 1.31 |
| 8| 6920 | 89.31 | 30.07 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 20.34 | 6.91 | 0.62 |
| 10 | 5 | 285 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 569 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2217 | 7157 | 98.49 | 37.73 | 1.53 |

