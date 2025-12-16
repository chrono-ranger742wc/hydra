--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-16 05:45:15.432977632 UTC |
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
| 1| 5836 | 10.40 | 3.30 | 0.51 |
| 2| 6038 | 12.91 | 4.10 | 0.55 |
| 3| 6238 | 14.50 | 4.58 | 0.57 |
| 5| 6638 | 18.64 | 5.88 | 0.64 |
| 10| 7648 | 28.94 | 9.11 | 0.79 |
| 43| 14281 | 99.13 | 30.99 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.40 | 9.67 | 0.52 |
| 3 | 170 | 747 | 41.38 | 11.97 | 0.60 |
| 4 | 226 | 858 | 49.18 | 14.20 | 0.69 |
| 5 | 283 | 969 | 61.06 | 17.46 | 0.81 |
| 6 | 339 | 1081 | 71.61 | 20.45 | 0.92 |
| 7 | 395 | 1196 | 71.83 | 20.78 | 0.93 |
| 8 | 448 | 1303 | 98.21 | 27.58 | 1.20 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.37 | 7.71 | 0.48 |
| 2| 1960 | 25.84 | 8.78 | 0.51 |
| 3| 2056 | 26.94 | 9.77 | 0.53 |
| 5| 2503 | 33.57 | 12.96 | 0.63 |
| 10| 3145 | 40.93 | 18.35 | 0.75 |
| 42| 7808 | 99.37 | 55.92 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.81 | 7.37 | 0.42 |
| 2| 773 | 23.54 | 8.22 | 0.43 |
| 3| 911 | 25.07 | 9.31 | 0.46 |
| 5| 1211 | 29.73 | 11.97 | 0.53 |
| 10| 2058 | 39.70 | 18.07 | 0.69 |
| 41| 6717 | 98.54 | 55.10 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 29.17 | 8.91 | 0.48 |
| 2| 902 | 29.97 | 9.84 | 0.50 |
| 3| 957 | 30.82 | 10.73 | 0.52 |
| 5| 1321 | 35.68 | 13.45 | 0.59 |
| 10| 2108 | 48.83 | 20.46 | 0.79 |
| 36| 6063 | 98.47 | 51.80 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 678 | 33.83 | 10.15 | 0.53 |
| 2| 822 | 35.92 | 11.40 | 0.56 |
| 3| 1014 | 38.58 | 12.82 | 0.60 |
| 5| 1257 | 42.68 | 15.29 | 0.66 |
| 10| 1919 | 52.74 | 21.40 | 0.82 |
| 29| 4912 | 99.39 | 47.09 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5833 | 27.12 | 9.10 | 0.69 |
| 2| 5916 | 34.91 | 11.69 | 0.78 |
| 3| 6231 | 46.89 | 15.85 | 0.92 |
| 4| 6224 | 54.79 | 18.43 | 1.00 |
| 5| 6409 | 64.87 | 21.89 | 1.11 |
| 6| 6716 | 75.80 | 25.64 | 1.24 |
| 7| 6761 | 80.29 | 27.01 | 1.29 |
| 8| 6864 | 89.06 | 30.11 | 1.39 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.49 | 6.17 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6175 | 38.62 | 14.15 | 0.84 |
| 10 | 39 | 2220 | 7159 | 98.05 | 37.58 | 1.53 |

