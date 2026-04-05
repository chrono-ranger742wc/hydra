--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-05 06:09:24.843524169 UTC |
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
| 1| 5840 | 10.61 | 3.37 | 0.52 |
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6236 | 14.59 | 4.61 | 0.58 |
| 5| 6638 | 18.72 | 5.91 | 0.64 |
| 10| 7646 | 29.19 | 9.21 | 0.79 |
| 43| 14281 | 98.95 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 113 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 169 | 747 | 41.46 | 11.98 | 0.60 |
| 4 | 226 | 858 | 48.55 | 14.12 | 0.68 |
| 5 | 285 | 969 | 56.13 | 16.31 | 0.76 |
| 6 | 338 | 1081 | 66.87 | 19.36 | 0.88 |
| 7 | 395 | 1192 | 84.70 | 23.91 | 1.06 |
| 8 | 449 | 1307 | 91.28 | 25.87 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 24.00 | 7.62 | 0.48 |
| 2| 1997 | 26.92 | 9.09 | 0.52 |
| 3| 2162 | 29.46 | 10.46 | 0.56 |
| 5| 2523 | 33.36 | 12.89 | 0.62 |
| 10| 3172 | 42.09 | 18.66 | 0.76 |
| 40| 7675 | 97.86 | 54.17 | 1.67 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 612 | 22.84 | 7.38 | 0.41 |
| 2| 835 | 25.16 | 8.71 | 0.45 |
| 3| 971 | 27.00 | 9.87 | 0.48 |
| 5| 1241 | 30.18 | 12.08 | 0.54 |
| 10| 2067 | 41.26 | 18.52 | 0.71 |
| 40| 6523 | 95.50 | 53.61 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 605 | 28.46 | 8.69 | 0.47 |
| 2| 811 | 30.94 | 10.07 | 0.51 |
| 3| 1077 | 31.87 | 11.04 | 0.53 |
| 5| 1206 | 34.41 | 13.05 | 0.58 |
| 10| 2109 | 45.57 | 19.57 | 0.75 |
| 36| 5921 | 97.04 | 51.31 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 681 | 33.87 | 10.16 | 0.53 |
| 2| 802 | 35.92 | 11.40 | 0.56 |
| 3| 1005 | 38.63 | 12.83 | 0.60 |
| 5| 1200 | 41.82 | 15.03 | 0.65 |
| 10| 2111 | 55.56 | 22.26 | 0.85 |
| 28| 4901 | 97.68 | 45.99 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5840 | 27.08 | 9.09 | 0.69 |
| 2| 5918 | 36.07 | 12.12 | 0.79 |
| 3| 5953 | 40.40 | 13.48 | 0.84 |
| 4| 6317 | 55.18 | 18.61 | 1.01 |
| 5| 6480 | 65.06 | 21.97 | 1.12 |
| 6| 6651 | 75.15 | 25.35 | 1.23 |
| 7| 6624 | 77.84 | 26.18 | 1.26 |
| 8| 6874 | 89.00 | 30.00 | 1.39 |
| 9| 6819 | 93.33 | 31.32 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 5 | 285 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2219 | 7159 | 99.82 | 38.19 | 1.55 |

