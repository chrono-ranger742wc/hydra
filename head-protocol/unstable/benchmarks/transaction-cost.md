--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-01 05:48:27.645843262 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6038 | 12.41 | 3.92 | 0.54 |
| 3| 6239 | 15.05 | 4.78 | 0.58 |
| 5| 6640 | 19.27 | 6.11 | 0.64 |
| 10| 7648 | 29.11 | 9.17 | 0.79 |
| 43| 14281 | 99.23 | 31.02 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1281 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10051 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 528 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.17 | 9.59 | 0.52 |
| 3 | 169 | 747 | 42.50 | 12.23 | 0.61 |
| 4 | 227 | 858 | 49.72 | 14.38 | 0.69 |
| 5 | 281 | 969 | 56.17 | 16.29 | 0.76 |
| 6 | 337 | 1081 | 71.49 | 20.39 | 0.92 |
| 7 | 394 | 1196 | 73.18 | 21.28 | 0.95 |
| 8 | 449 | 1303 | 85.03 | 24.43 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1804 | 24.37 | 7.71 | 0.48 |
| 2| 1882 | 24.43 | 8.40 | 0.49 |
| 3| 2067 | 27.35 | 9.87 | 0.53 |
| 5| 2363 | 31.01 | 12.24 | 0.59 |
| 10| 3284 | 42.78 | 18.86 | 0.78 |
| 39| 7474 | 94.96 | 52.69 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 615 | 22.84 | 7.37 | 0.42 |
| 2| 788 | 25.12 | 8.68 | 0.45 |
| 3| 976 | 28.23 | 10.22 | 0.49 |
| 5| 1210 | 29.63 | 11.95 | 0.53 |
| 10| 1884 | 38.54 | 17.77 | 0.67 |
| 42| 6781 | 99.55 | 56.09 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 27.54 | 8.47 | 0.46 |
| 2| 736 | 30.23 | 9.85 | 0.50 |
| 3| 873 | 32.05 | 11.02 | 0.53 |
| 5| 1264 | 36.98 | 13.76 | 0.60 |
| 10| 2092 | 48.52 | 20.39 | 0.78 |
| 33| 5790 | 95.03 | 48.82 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 33.83 | 10.15 | 0.53 |
| 2| 887 | 36.60 | 11.61 | 0.57 |
| 3| 952 | 37.91 | 12.62 | 0.59 |
| 5| 1393 | 44.82 | 15.94 | 0.69 |
| 10| 2030 | 53.79 | 21.74 | 0.83 |
| 29| 4891 | 98.85 | 46.94 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 26.96 | 9.05 | 0.69 |
| 2| 5940 | 35.76 | 12.03 | 0.79 |
| 3| 6161 | 46.12 | 15.54 | 0.91 |
| 4| 6323 | 55.98 | 18.91 | 1.02 |
| 5| 6372 | 62.49 | 21.03 | 1.09 |
| 6| 6690 | 75.37 | 25.48 | 1.24 |
| 7| 6643 | 79.46 | 26.73 | 1.28 |
| 8| 6946 | 93.54 | 31.57 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 285 | 6004 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 571 | 6176 | 39.69 | 14.52 | 0.85 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2223 | 7162 | 98.05 | 37.58 | 1.53 |

