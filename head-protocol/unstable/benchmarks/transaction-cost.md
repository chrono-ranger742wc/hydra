--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-09 06:03:27.752597066 UTC |
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
| 1| 5834 | 10.26 | 3.25 | 0.51 |
| 2| 6035 | 12.46 | 3.94 | 0.54 |
| 3| 6236 | 14.47 | 4.57 | 0.57 |
| 5| 6641 | 18.41 | 5.80 | 0.63 |
| 10| 7646 | 28.73 | 9.04 | 0.78 |
| 43| 14281 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 33.40 | 9.68 | 0.52 |
| 3 | 169 | 747 | 41.13 | 11.88 | 0.60 |
| 4 | 225 | 858 | 51.27 | 14.75 | 0.71 |
| 5 | 283 | 974 | 56.24 | 16.34 | 0.77 |
| 6 | 339 | 1085 | 67.32 | 19.35 | 0.88 |
| 7 | 394 | 1192 | 74.16 | 21.34 | 0.96 |
| 8 | 448 | 1303 | 80.53 | 23.35 | 1.03 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1810 | 24.37 | 7.71 | 0.48 |
| 2| 1952 | 25.84 | 8.78 | 0.51 |
| 3| 2015 | 26.28 | 9.57 | 0.52 |
| 5| 2332 | 30.18 | 12.00 | 0.58 |
| 10| 3199 | 42.00 | 18.63 | 0.76 |
| 39| 7556 | 96.75 | 53.22 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 622 | 22.84 | 7.38 | 0.42 |
| 2| 799 | 25.12 | 8.68 | 0.45 |
| 3| 883 | 25.74 | 9.53 | 0.47 |
| 5| 1165 | 28.53 | 11.65 | 0.52 |
| 10| 2036 | 40.55 | 18.34 | 0.70 |
| 39| 6499 | 97.81 | 53.56 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 642 | 29.13 | 8.90 | 0.48 |
| 2| 816 | 29.18 | 9.60 | 0.49 |
| 3| 907 | 30.23 | 10.54 | 0.51 |
| 5| 1309 | 38.29 | 14.17 | 0.62 |
| 10| 2027 | 48.30 | 20.30 | 0.78 |
| 36| 6030 | 97.51 | 51.50 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 711 | 33.83 | 10.15 | 0.53 |
| 2| 828 | 35.88 | 11.39 | 0.56 |
| 3| 1015 | 38.55 | 12.81 | 0.60 |
| 5| 1296 | 43.28 | 15.48 | 0.67 |
| 10| 2146 | 54.69 | 22.00 | 0.85 |
| 29| 4806 | 96.66 | 46.28 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5839 | 27.08 | 9.09 | 0.69 |
| 2| 5820 | 31.60 | 10.51 | 0.74 |
| 3| 6150 | 45.90 | 15.46 | 0.90 |
| 4| 6306 | 54.86 | 18.52 | 1.00 |
| 5| 6389 | 61.29 | 20.66 | 1.08 |
| 6| 6473 | 71.11 | 23.82 | 1.18 |
| 7| 6804 | 83.80 | 28.24 | 1.33 |
| 8| 6746 | 81.93 | 27.47 | 1.31 |
| 9| 6877 | 94.34 | 31.64 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 569 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1141 | 6516 | 59.54 | 22.38 | 1.08 |
| 10 | 39 | 2219 | 7158 | 97.61 | 37.43 | 1.52 |

