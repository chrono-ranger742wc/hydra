--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-23 05:09:45.994861699 UTC |
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
| 1| 5837 | 10.69 | 3.40 | 0.52 |
| 2| 6035 | 13.10 | 4.17 | 0.55 |
| 3| 6236 | 14.79 | 4.69 | 0.58 |
| 5| 6640 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.38 | 9.27 | 0.79 |
| 43| 14279 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10052 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 640 | 33.25 | 9.63 | 0.52 |
| 3 | 171 | 751 | 43.73 | 12.51 | 0.63 |
| 4 | 226 | 858 | 50.70 | 14.56 | 0.70 |
| 5 | 283 | 969 | 64.31 | 18.27 | 0.84 |
| 6 | 340 | 1085 | 67.81 | 19.47 | 0.89 |
| 7 | 392 | 1192 | 74.81 | 21.63 | 0.96 |
| 8 | 451 | 1303 | 84.76 | 24.31 | 1.07 |
| 9 | 506 | 1418 | 92.14 | 26.54 | 1.15 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1807 | 23.92 | 7.60 | 0.48 |
| 2| 1925 | 25.84 | 8.78 | 0.51 |
| 3| 2060 | 27.47 | 9.90 | 0.53 |
| 5| 2455 | 32.19 | 12.57 | 0.61 |
| 10| 3284 | 43.01 | 18.92 | 0.78 |
| 39| 7466 | 96.95 | 53.23 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 627 | 22.81 | 7.37 | 0.42 |
| 2| 800 | 25.16 | 8.71 | 0.45 |
| 3| 870 | 25.85 | 9.55 | 0.47 |
| 5| 1220 | 29.97 | 12.04 | 0.53 |
| 10| 1897 | 36.70 | 17.23 | 0.65 |
| 43| 6710 | 97.27 | 56.12 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 665 | 29.17 | 8.91 | 0.48 |
| 2| 774 | 28.47 | 9.38 | 0.48 |
| 3| 873 | 32.01 | 11.01 | 0.53 |
| 5| 1273 | 34.97 | 13.23 | 0.58 |
| 10| 2148 | 46.36 | 19.81 | 0.76 |
| 34| 5680 | 98.89 | 50.45 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 33.87 | 10.16 | 0.53 |
| 2| 764 | 35.17 | 11.17 | 0.55 |
| 3| 963 | 37.84 | 12.60 | 0.59 |
| 5| 1162 | 41.15 | 14.83 | 0.64 |
| 10| 2081 | 54.96 | 22.07 | 0.85 |
| 29| 4944 | 99.74 | 47.20 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5823 | 26.96 | 9.06 | 0.69 |
| 2| 5973 | 37.17 | 12.51 | 0.80 |
| 3| 6083 | 44.70 | 15.02 | 0.89 |
| 4| 6281 | 55.03 | 18.50 | 1.00 |
| 5| 6452 | 64.16 | 21.62 | 1.11 |
| 6| 6561 | 73.44 | 24.66 | 1.21 |
| 7| 6688 | 77.70 | 26.18 | 1.26 |
| 8| 6945 | 93.75 | 31.59 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5868 | 20.34 | 6.91 | 0.62 |
| 10 | 10 | 570 | 6174 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1137 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1707 | 6853 | 80.48 | 30.61 | 1.32 |
| 10 | 38 | 2163 | 7125 | 96.81 | 37.05 | 1.51 |

