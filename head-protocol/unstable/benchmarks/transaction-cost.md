--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-15 05:01:18.628999096 UTC |
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
| 1| 5837 | 11.10 | 3.55 | 0.52 |
| 2| 6038 | 12.99 | 4.13 | 0.55 |
| 3| 6236 | 14.60 | 4.62 | 0.58 |
| 5| 6638 | 18.81 | 5.94 | 0.64 |
| 10| 7646 | 29.11 | 9.17 | 0.79 |
| 43| 14281 | 98.64 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2164 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 170 | 747 | 40.09 | 11.64 | 0.59 |
| 4 | 227 | 862 | 52.12 | 14.90 | 0.72 |
| 5 | 280 | 969 | 57.63 | 16.67 | 0.78 |
| 6 | 341 | 1081 | 75.67 | 21.43 | 0.96 |
| 7 | 394 | 1192 | 84.44 | 23.80 | 1.06 |
| 8 | 450 | 1303 | 84.84 | 24.33 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1817 | 24.37 | 7.71 | 0.48 |
| 2| 1884 | 24.47 | 8.41 | 0.49 |
| 3| 2130 | 28.38 | 10.16 | 0.55 |
| 5| 2341 | 30.34 | 12.04 | 0.59 |
| 10| 3177 | 41.77 | 18.58 | 0.76 |
| 38| 7252 | 95.23 | 52.08 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 655 | 22.50 | 7.30 | 0.41 |
| 2| 726 | 22.52 | 7.93 | 0.42 |
| 3| 950 | 26.86 | 9.85 | 0.48 |
| 5| 1200 | 29.11 | 11.79 | 0.52 |
| 10| 2037 | 39.83 | 18.10 | 0.69 |
| 40| 6521 | 97.72 | 54.21 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 29.09 | 8.89 | 0.48 |
| 2| 778 | 30.91 | 10.06 | 0.51 |
| 3| 944 | 32.80 | 11.25 | 0.54 |
| 5| 1259 | 34.97 | 13.23 | 0.58 |
| 10| 2099 | 48.98 | 20.50 | 0.79 |
| 38| 6021 | 98.28 | 52.97 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 691 | 33.79 | 10.15 | 0.53 |
| 2| 811 | 35.92 | 11.40 | 0.56 |
| 3| 938 | 37.87 | 12.61 | 0.59 |
| 5| 1316 | 43.31 | 15.48 | 0.67 |
| 10| 2070 | 54.96 | 22.07 | 0.84 |
| 30| 4949 | 99.61 | 47.83 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 26.96 | 9.06 | 0.69 |
| 2| 5950 | 37.01 | 12.47 | 0.80 |
| 3| 6161 | 45.62 | 15.37 | 0.90 |
| 4| 6322 | 54.70 | 18.43 | 1.00 |
| 5| 6496 | 65.10 | 21.99 | 1.12 |
| 6| 6347 | 64.27 | 21.48 | 1.10 |
| 7| 6785 | 80.09 | 26.98 | 1.29 |
| 8| 6744 | 90.25 | 30.28 | 1.39 |
| 9| 6876 | 97.30 | 32.86 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 284 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1140 | 6514 | 60.17 | 22.59 | 1.09 |
| 10 | 30 | 1707 | 6854 | 79.60 | 30.31 | 1.31 |
| 10 | 40 | 2274 | 7190 | 99.66 | 38.24 | 1.55 |

