--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-02 05:41:57.42117984 UTC |
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
| 1| 5834 | 10.86 | 3.46 | 0.52 |
| 2| 6037 | 12.61 | 4.00 | 0.55 |
| 3| 6239 | 14.59 | 4.61 | 0.58 |
| 5| 6640 | 18.64 | 5.88 | 0.64 |
| 10| 7646 | 29.57 | 9.34 | 0.79 |
| 43| 14283 | 99.02 | 30.95 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10056 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 529 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 169 | 747 | 43.68 | 12.51 | 0.63 |
| 4 | 227 | 858 | 52.27 | 14.94 | 0.72 |
| 5 | 284 | 969 | 59.48 | 17.14 | 0.80 |
| 6 | 338 | 1081 | 71.12 | 20.33 | 0.92 |
| 7 | 393 | 1192 | 87.13 | 24.58 | 1.08 |
| 8 | 451 | 1303 | 86.71 | 24.83 | 1.09 |
| 9 | 504 | 1414 | 94.03 | 26.99 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1787 | 24.00 | 7.62 | 0.48 |
| 2| 1970 | 26.91 | 9.08 | 0.52 |
| 3| 2114 | 28.55 | 10.20 | 0.55 |
| 5| 2366 | 31.28 | 12.31 | 0.60 |
| 10| 3040 | 38.88 | 17.76 | 0.73 |
| 41| 7756 | 98.57 | 55.02 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 22.54 | 7.30 | 0.41 |
| 2| 814 | 25.49 | 8.78 | 0.46 |
| 3| 962 | 26.96 | 9.86 | 0.48 |
| 5| 1243 | 31.10 | 12.35 | 0.55 |
| 10| 2019 | 41.01 | 18.47 | 0.70 |
| 42| 6726 | 99.13 | 55.92 | 1.65 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 691 | 27.54 | 8.47 | 0.46 |
| 2| 844 | 29.22 | 9.61 | 0.49 |
| 3| 906 | 30.19 | 10.53 | 0.51 |
| 5| 1172 | 36.42 | 13.59 | 0.59 |
| 10| 2003 | 45.31 | 19.49 | 0.74 |
| 35| 5892 | 99.74 | 51.38 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.83 | 10.15 | 0.53 |
| 2| 813 | 35.92 | 11.40 | 0.56 |
| 3| 899 | 37.24 | 12.41 | 0.58 |
| 5| 1274 | 42.57 | 15.26 | 0.66 |
| 10| 2215 | 56.61 | 22.58 | 0.87 |
| 28| 4761 | 95.45 | 45.33 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5822 | 27.05 | 9.07 | 0.69 |
| 2| 5941 | 35.83 | 12.05 | 0.79 |
| 3| 6211 | 46.56 | 15.78 | 0.91 |
| 4| 6244 | 53.90 | 18.10 | 0.99 |
| 5| 6509 | 66.51 | 22.47 | 1.14 |
| 6| 6693 | 74.67 | 25.18 | 1.23 |
| 7| 6780 | 84.71 | 28.62 | 1.34 |
| 8| 6971 | 94.02 | 31.70 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 284 | 6003 | 28.46 | 10.13 | 0.72 |
| 10 | 20 | 1138 | 6512 | 59.73 | 22.44 | 1.08 |
| 10 | 39 | 2218 | 7157 | 98.42 | 37.71 | 1.53 |

