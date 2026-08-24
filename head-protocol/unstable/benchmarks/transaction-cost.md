--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-24 05:15:47.170871118 UTC |
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
| 1| 5836 | 10.95 | 3.49 | 0.52 |
| 2| 6037 | 12.67 | 4.01 | 0.55 |
| 3| 6236 | 14.31 | 4.52 | 0.57 |
| 5| 6638 | 18.83 | 5.95 | 0.64 |
| 10| 7648 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 99.25 | 31.03 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 33.18 | 9.60 | 0.52 |
| 3 | 169 | 751 | 41.01 | 11.85 | 0.60 |
| 4 | 227 | 862 | 49.80 | 14.42 | 0.69 |
| 5 | 285 | 969 | 57.34 | 16.60 | 0.78 |
| 6 | 336 | 1081 | 64.64 | 18.75 | 0.86 |
| 7 | 394 | 1192 | 78.20 | 22.39 | 1.00 |
| 8 | 449 | 1307 | 96.13 | 27.09 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.37 | 7.71 | 0.48 |
| 2| 1927 | 25.92 | 8.80 | 0.51 |
| 3| 2131 | 28.43 | 10.17 | 0.55 |
| 5| 2324 | 30.26 | 12.02 | 0.58 |
| 10| 3069 | 40.11 | 18.10 | 0.74 |
| 40| 7614 | 98.15 | 54.24 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 600 | 22.53 | 7.31 | 0.41 |
| 2| 790 | 23.98 | 8.38 | 0.44 |
| 3| 895 | 25.07 | 9.31 | 0.46 |
| 5| 1205 | 29.79 | 11.99 | 0.53 |
| 10| 2043 | 40.39 | 18.28 | 0.70 |
| 42| 6592 | 98.73 | 55.78 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 663 | 29.13 | 8.90 | 0.48 |
| 2| 875 | 29.93 | 9.83 | 0.50 |
| 3| 873 | 32.04 | 11.02 | 0.53 |
| 5| 1210 | 34.37 | 13.04 | 0.58 |
| 10| 2046 | 44.90 | 19.37 | 0.74 |
| 34| 5401 | 95.44 | 49.42 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 33.83 | 10.16 | 0.53 |
| 2| 811 | 35.88 | 11.39 | 0.56 |
| 3| 953 | 37.80 | 12.59 | 0.59 |
| 5| 1366 | 43.69 | 15.60 | 0.68 |
| 10| 1993 | 53.31 | 21.58 | 0.82 |
| 29| 4951 | 98.69 | 46.92 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5838 | 27.08 | 9.09 | 0.69 |
| 2| 6005 | 37.05 | 12.48 | 0.80 |
| 3| 6112 | 45.78 | 15.43 | 0.90 |
| 4| 6196 | 50.82 | 17.04 | 0.96 |
| 5| 6505 | 65.33 | 22.05 | 1.12 |
| 6| 6371 | 65.27 | 21.85 | 1.12 |
| 7| 6772 | 80.20 | 27.09 | 1.29 |
| 8| 6979 | 92.59 | 31.23 | 1.43 |
| 9| 6903 | 97.87 | 32.87 | 1.48 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1139 | 6513 | 58.66 | 22.07 | 1.07 |
| 10 | 30 | 1708 | 6854 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2221 | 7160 | 99.56 | 38.10 | 1.54 |

