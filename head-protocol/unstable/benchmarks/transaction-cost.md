--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-02 05:52:11.662969506 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6239 | 14.90 | 4.72 | 0.58 |
| 5| 6641 | 18.50 | 5.83 | 0.63 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1279 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.31 | 9.40 | 0.51 |
| 3 | 169 | 751 | 41.24 | 11.93 | 0.60 |
| 4 | 227 | 858 | 53.78 | 15.30 | 0.73 |
| 5 | 282 | 969 | 59.86 | 17.21 | 0.80 |
| 6 | 339 | 1085 | 72.20 | 20.60 | 0.93 |
| 7 | 395 | 1192 | 86.74 | 24.44 | 1.08 |
| 8 | 451 | 1303 | 83.15 | 23.98 | 1.05 |
| 9 | 508 | 1414 | 93.60 | 26.93 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1803 | 23.92 | 7.60 | 0.48 |
| 2| 1928 | 25.84 | 8.78 | 0.51 |
| 3| 2064 | 27.23 | 9.84 | 0.53 |
| 5| 2461 | 32.48 | 12.64 | 0.61 |
| 10| 3150 | 40.90 | 18.33 | 0.75 |
| 38| 7432 | 95.90 | 52.29 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 608 | 22.57 | 7.30 | 0.41 |
| 2| 742 | 23.58 | 8.23 | 0.43 |
| 3| 900 | 25.02 | 9.30 | 0.46 |
| 5| 1297 | 31.20 | 12.37 | 0.55 |
| 10| 1986 | 38.77 | 17.82 | 0.68 |
| 40| 6368 | 96.99 | 54.01 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 27.54 | 8.47 | 0.46 |
| 2| 774 | 28.47 | 9.38 | 0.48 |
| 3| 1024 | 31.57 | 10.95 | 0.53 |
| 5| 1210 | 34.30 | 13.02 | 0.57 |
| 10| 2004 | 44.23 | 19.16 | 0.73 |
| 39| 6139 | 98.84 | 53.79 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.83 | 10.15 | 0.53 |
| 2| 769 | 35.17 | 11.17 | 0.55 |
| 3| 988 | 38.59 | 12.82 | 0.60 |
| 5| 1253 | 42.60 | 15.27 | 0.66 |
| 10| 2015 | 54.05 | 21.81 | 0.83 |
| 29| 4985 | 99.30 | 47.11 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5827 | 26.92 | 9.05 | 0.69 |
| 2| 5941 | 35.96 | 12.09 | 0.79 |
| 3| 6121 | 46.17 | 15.54 | 0.90 |
| 4| 6374 | 56.92 | 19.23 | 1.03 |
| 5| 6340 | 61.83 | 20.75 | 1.08 |
| 6| 6515 | 73.61 | 24.80 | 1.21 |
| 7| 6579 | 78.84 | 26.53 | 1.27 |
| 8| 6962 | 93.71 | 31.61 | 1.44 |
| 9| 7004 | 98.64 | 33.21 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5868 | 22.55 | 7.67 | 0.65 |
| 10 | 5 | 285 | 6005 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 570 | 6175 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1135 | 6509 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1707 | 6853 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2220 | 7159 | 97.61 | 37.43 | 1.52 |

