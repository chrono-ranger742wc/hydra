--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-14 05:13:45.652564606 UTC |
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
| 1| 5837 | 10.35 | 3.28 | 0.51 |
| 2| 6035 | 12.70 | 4.03 | 0.55 |
| 3| 6236 | 14.31 | 4.52 | 0.57 |
| 5| 6641 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14279 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10037 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 640 | 32.24 | 9.37 | 0.51 |
| 3 | 169 | 747 | 40.22 | 11.69 | 0.59 |
| 4 | 226 | 858 | 48.26 | 14.00 | 0.68 |
| 5 | 283 | 969 | 64.55 | 18.30 | 0.85 |
| 6 | 340 | 1081 | 65.86 | 19.00 | 0.87 |
| 7 | 394 | 1196 | 80.91 | 23.05 | 1.02 |
| 8 | 450 | 1303 | 80.09 | 23.19 | 1.02 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.29 | 7.69 | 0.48 |
| 2| 2003 | 26.96 | 9.09 | 0.52 |
| 3| 2087 | 27.31 | 9.86 | 0.53 |
| 5| 2447 | 32.27 | 12.59 | 0.61 |
| 10| 3189 | 40.90 | 18.33 | 0.75 |
| 39| 7444 | 94.99 | 52.68 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 665 | 22.81 | 7.38 | 0.42 |
| 2| 701 | 22.58 | 7.94 | 0.42 |
| 3| 903 | 25.14 | 9.33 | 0.46 |
| 5| 1219 | 29.16 | 11.79 | 0.52 |
| 10| 1925 | 37.38 | 17.42 | 0.66 |
| 41| 6554 | 95.94 | 54.36 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 27.54 | 8.47 | 0.46 |
| 2| 823 | 29.22 | 9.61 | 0.49 |
| 3| 961 | 33.51 | 11.47 | 0.55 |
| 5| 1396 | 39.24 | 14.45 | 0.63 |
| 10| 1873 | 46.20 | 19.65 | 0.75 |
| 36| 6014 | 98.69 | 51.83 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 677 | 33.83 | 10.15 | 0.53 |
| 2| 845 | 36.52 | 11.59 | 0.57 |
| 3| 937 | 37.88 | 12.61 | 0.59 |
| 5| 1319 | 43.27 | 15.47 | 0.67 |
| 10| 1980 | 53.16 | 21.54 | 0.82 |
| 29| 4870 | 98.48 | 46.83 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5818 | 27.13 | 9.09 | 0.69 |
| 2| 5895 | 32.57 | 10.88 | 0.75 |
| 3| 6070 | 41.28 | 13.83 | 0.85 |
| 4| 6180 | 51.49 | 17.30 | 0.96 |
| 5| 6379 | 62.85 | 21.12 | 1.09 |
| 6| 6287 | 63.95 | 21.32 | 1.10 |
| 7| 6938 | 85.84 | 29.14 | 1.36 |
| 8| 6789 | 86.23 | 29.02 | 1.35 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 5 | 285 | 6004 | 28.02 | 9.98 | 0.71 |
| 10 | 10 | 570 | 6174 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1137 | 6512 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1703 | 6849 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2218 | 7157 | 98.93 | 37.88 | 1.54 |

