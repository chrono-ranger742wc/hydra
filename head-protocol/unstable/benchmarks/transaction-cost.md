--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-30 09:08:50.530851168 UTC |
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
| 1| 5834 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.75 | 4.04 | 0.55 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.90 | 5.97 | 0.64 |
| 10| 7646 | 28.71 | 9.03 | 0.78 |
| 43| 14279 | 98.75 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 171 | 751 | 42.22 | 12.14 | 0.61 |
| 4 | 225 | 858 | 49.41 | 14.27 | 0.69 |
| 5 | 283 | 969 | 56.08 | 16.30 | 0.76 |
| 6 | 336 | 1081 | 63.77 | 18.54 | 0.85 |
| 7 | 392 | 1192 | 72.59 | 21.01 | 0.94 |
| 8 | 449 | 1303 | 83.06 | 24.01 | 1.05 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1817 | 24.00 | 7.62 | 0.48 |
| 2| 1928 | 25.39 | 8.68 | 0.50 |
| 3| 2059 | 27.31 | 9.86 | 0.53 |
| 5| 2370 | 30.95 | 12.23 | 0.59 |
| 10| 3037 | 38.78 | 17.73 | 0.73 |
| 41| 7840 | 99.83 | 55.40 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 635 | 22.81 | 7.37 | 0.42 |
| 2| 766 | 23.58 | 8.23 | 0.43 |
| 3| 930 | 25.14 | 9.33 | 0.46 |
| 5| 1329 | 31.27 | 12.39 | 0.55 |
| 10| 1964 | 38.49 | 17.73 | 0.68 |
| 42| 6644 | 98.30 | 55.69 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 661 | 29.17 | 8.91 | 0.48 |
| 2| 840 | 29.15 | 9.59 | 0.49 |
| 3| 945 | 32.72 | 11.23 | 0.54 |
| 5| 1338 | 35.56 | 13.42 | 0.59 |
| 10| 1981 | 44.08 | 19.12 | 0.73 |
| 36| 6127 | 99.26 | 52.03 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 679 | 33.87 | 10.16 | 0.53 |
| 2| 821 | 35.92 | 11.40 | 0.56 |
| 3| 974 | 37.80 | 12.59 | 0.59 |
| 5| 1227 | 41.86 | 15.04 | 0.65 |
| 10| 1979 | 53.46 | 21.62 | 0.83 |
| 29| 4868 | 98.17 | 46.75 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5824 | 27.00 | 9.07 | 0.69 |
| 2| 5972 | 35.89 | 12.06 | 0.79 |
| 3| 6085 | 44.56 | 14.99 | 0.89 |
| 4| 6278 | 55.02 | 18.53 | 1.00 |
| 5| 6325 | 59.35 | 19.92 | 1.05 |
| 6| 6620 | 75.39 | 25.47 | 1.23 |
| 7| 6801 | 84.83 | 28.57 | 1.34 |
| 8| 6991 | 93.99 | 31.74 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 10 | 569 | 6174 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1138 | 6512 | 61.05 | 22.90 | 1.10 |
| 10 | 30 | 1709 | 6855 | 79.60 | 30.31 | 1.31 |
| 10 | 40 | 2274 | 7190 | 99.22 | 38.09 | 1.54 |

