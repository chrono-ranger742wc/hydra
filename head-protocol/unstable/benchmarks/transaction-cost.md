--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-12-14 05:46:41.453794658 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6038 | 12.65 | 4.01 | 0.55 |
| 3| 6238 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7647 | 28.88 | 9.10 | 0.79 |
| 43| 14281 | 98.58 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 921 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 41.08 | 11.87 | 0.60 |
| 4 | 226 | 858 | 52.58 | 15.06 | 0.72 |
| 5 | 284 | 969 | 57.88 | 16.76 | 0.78 |
| 6 | 340 | 1081 | 68.22 | 19.60 | 0.89 |
| 7 | 396 | 1192 | 86.37 | 24.31 | 1.08 |
| 8 | 449 | 1303 | 87.86 | 25.11 | 1.10 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 23.92 | 7.60 | 0.48 |
| 2| 2009 | 26.63 | 9.02 | 0.52 |
| 3| 2178 | 29.21 | 10.40 | 0.56 |
| 5| 2464 | 32.49 | 12.64 | 0.61 |
| 10| 3105 | 40.50 | 18.21 | 0.75 |
| 39| 7608 | 97.75 | 53.48 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 613 | 22.84 | 7.38 | 0.41 |
| 2| 741 | 24.07 | 8.39 | 0.44 |
| 3| 854 | 24.11 | 9.04 | 0.45 |
| 5| 1119 | 26.94 | 11.17 | 0.50 |
| 10| 1949 | 37.74 | 17.53 | 0.67 |
| 40| 6549 | 96.49 | 53.87 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 29.17 | 8.91 | 0.48 |
| 2| 796 | 30.90 | 10.06 | 0.51 |
| 3| 1028 | 31.61 | 10.96 | 0.53 |
| 5| 1259 | 35.08 | 13.26 | 0.58 |
| 10| 1994 | 44.07 | 19.12 | 0.73 |
| 37| 6198 | 99.53 | 52.72 | 1.61 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 686 | 33.87 | 10.16 | 0.53 |
| 2| 837 | 35.92 | 11.40 | 0.56 |
| 3| 958 | 37.91 | 12.62 | 0.59 |
| 5| 1292 | 43.36 | 15.49 | 0.67 |
| 10| 2041 | 54.03 | 21.80 | 0.83 |
| 29| 4813 | 96.80 | 46.35 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 26.92 | 9.04 | 0.69 |
| 2| 5958 | 35.91 | 12.07 | 0.79 |
| 3| 6101 | 44.40 | 14.96 | 0.89 |
| 4| 6347 | 55.17 | 18.59 | 1.01 |
| 5| 6385 | 61.72 | 20.83 | 1.08 |
| 6| 6583 | 74.84 | 25.20 | 1.23 |
| 7| 6769 | 80.60 | 27.17 | 1.30 |
| 8| 6905 | 91.43 | 30.81 | 1.41 |
| 9| 6936 | 95.90 | 32.23 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 5 | 285 | 6005 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 569 | 6173 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1137 | 6512 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1710 | 6856 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2218 | 7157 | 98.68 | 37.80 | 1.53 |

