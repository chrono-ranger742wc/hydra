--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-30 10:51:06.815990556 UTC |
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
| 1| 5837 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.92 | 4.11 | 0.55 |
| 3| 6239 | 14.60 | 4.62 | 0.58 |
| 5| 6638 | 18.71 | 5.91 | 0.64 |
| 10| 7646 | 28.81 | 9.07 | 0.78 |
| 43| 14286 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2170 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 170 | 747 | 41.39 | 11.95 | 0.60 |
| 4 | 225 | 862 | 48.24 | 14.03 | 0.68 |
| 5 | 282 | 969 | 61.51 | 17.63 | 0.82 |
| 6 | 339 | 1081 | 73.83 | 20.99 | 0.95 |
| 7 | 397 | 1192 | 71.82 | 20.78 | 0.93 |
| 8 | 450 | 1307 | 84.62 | 24.28 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1744 | 22.93 | 7.32 | 0.47 |
| 2| 1951 | 25.76 | 8.76 | 0.51 |
| 3| 2187 | 28.93 | 10.33 | 0.55 |
| 5| 2394 | 31.18 | 12.28 | 0.60 |
| 10| 3221 | 41.67 | 18.55 | 0.76 |
| 43| 7822 | 98.18 | 56.25 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.81 | 7.37 | 0.42 |
| 2| 808 | 25.09 | 8.67 | 0.45 |
| 3| 1030 | 28.13 | 10.19 | 0.50 |
| 5| 1285 | 30.71 | 12.25 | 0.54 |
| 10| 1974 | 39.06 | 17.89 | 0.68 |
| 42| 6747 | 97.61 | 55.53 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 29.17 | 8.91 | 0.48 |
| 2| 771 | 28.51 | 9.39 | 0.48 |
| 3| 982 | 33.43 | 11.44 | 0.55 |
| 5| 1200 | 36.64 | 13.66 | 0.60 |
| 10| 1957 | 46.80 | 19.84 | 0.76 |
| 36| 5762 | 94.65 | 50.58 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.87 | 10.16 | 0.53 |
| 2| 809 | 35.88 | 11.39 | 0.56 |
| 3| 953 | 37.91 | 12.62 | 0.59 |
| 5| 1273 | 42.65 | 15.28 | 0.66 |
| 10| 2073 | 54.61 | 21.98 | 0.84 |
| 29| 4856 | 97.08 | 46.44 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5823 | 26.92 | 9.04 | 0.69 |
| 2| 6042 | 36.89 | 12.44 | 0.80 |
| 3| 5997 | 40.20 | 13.41 | 0.84 |
| 4| 6265 | 55.29 | 18.62 | 1.01 |
| 5| 6567 | 67.05 | 22.76 | 1.15 |
| 6| 6424 | 68.94 | 23.12 | 1.16 |
| 7| 6688 | 79.53 | 26.70 | 1.28 |
| 8| 6881 | 93.87 | 31.57 | 1.44 |
| 9| 7015 | 96.33 | 32.42 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 20.52 | 6.98 | 0.62 |
| 10 | 5 | 285 | 6004 | 29.98 | 10.65 | 0.73 |
| 10 | 20 | 1139 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2220 | 7160 | 99.38 | 38.04 | 1.54 |

