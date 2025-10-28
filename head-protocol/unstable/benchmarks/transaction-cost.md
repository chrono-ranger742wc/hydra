--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-28 05:33:25.633244486 UTC |
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
| 1| 5834 | 10.28 | 3.25 | 0.51 |
| 2| 6035 | 12.67 | 4.01 | 0.55 |
| 3| 6243 | 14.67 | 4.64 | 0.58 |
| 5| 6638 | 18.83 | 5.95 | 0.64 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14281 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1271 | 6.41 | 3.60 | 0.28 |
| 10| 2182 | 12.13 | 7.25 | 0.40 |
| 54| 10048 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.30 | 9.40 | 0.51 |
| 3 | 170 | 747 | 40.27 | 11.70 | 0.59 |
| 4 | 226 | 858 | 54.27 | 15.49 | 0.74 |
| 5 | 280 | 969 | 64.39 | 18.29 | 0.84 |
| 6 | 340 | 1081 | 64.44 | 18.67 | 0.85 |
| 7 | 392 | 1192 | 82.97 | 23.58 | 1.04 |
| 8 | 449 | 1303 | 80.86 | 23.38 | 1.03 |
| 9 | 506 | 1414 | 88.51 | 25.66 | 1.11 |
| 10 | 561 | 1529 | 98.70 | 28.64 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1810 | 24.37 | 7.71 | 0.48 |
| 2| 1984 | 26.87 | 9.07 | 0.52 |
| 3| 2066 | 27.02 | 9.79 | 0.53 |
| 5| 2438 | 32.65 | 12.68 | 0.61 |
| 10| 3143 | 41.01 | 18.37 | 0.75 |
| 40| 7413 | 95.84 | 53.57 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 618 | 22.84 | 7.37 | 0.42 |
| 2| 745 | 23.66 | 8.26 | 0.43 |
| 3| 911 | 25.12 | 9.32 | 0.46 |
| 5| 1184 | 28.85 | 11.72 | 0.52 |
| 10| 1939 | 38.08 | 17.62 | 0.67 |
| 42| 6475 | 93.62 | 54.40 | 1.58 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 639 | 29.17 | 8.91 | 0.48 |
| 2| 824 | 31.58 | 10.27 | 0.52 |
| 3| 987 | 33.39 | 11.43 | 0.55 |
| 5| 1210 | 34.33 | 13.03 | 0.57 |
| 10| 2218 | 46.81 | 19.96 | 0.77 |
| 35| 5809 | 94.53 | 49.93 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.87 | 10.16 | 0.53 |
| 2| 819 | 35.85 | 11.38 | 0.56 |
| 3| 1008 | 38.59 | 12.82 | 0.60 |
| 5| 1203 | 41.78 | 15.02 | 0.65 |
| 10| 2087 | 54.77 | 22.02 | 0.84 |
| 28| 4510 | 93.75 | 44.78 | 1.43 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5803 | 26.97 | 9.06 | 0.69 |
| 2| 5986 | 35.83 | 12.05 | 0.79 |
| 3| 6092 | 45.08 | 15.16 | 0.89 |
| 4| 6249 | 51.80 | 17.41 | 0.97 |
| 5| 6450 | 64.10 | 21.61 | 1.11 |
| 6| 6692 | 76.16 | 25.74 | 1.25 |
| 7| 6665 | 80.40 | 27.06 | 1.29 |
| 8| 6862 | 92.52 | 31.15 | 1.42 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1139 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 38 | 2160 | 7122 | 96.63 | 36.99 | 1.51 |

