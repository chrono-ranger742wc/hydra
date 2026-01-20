--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-20 05:12:53.637049676 UTC |
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
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6243 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 19.08 | 6.04 | 0.64 |
| 10| 7646 | 29.12 | 9.18 | 0.79 |
| 43| 14286 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2171 | 12.13 | 7.25 | 0.40 |
| 54| 10058 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 39.98 | 11.61 | 0.59 |
| 4 | 227 | 858 | 53.45 | 15.27 | 0.73 |
| 5 | 283 | 969 | 59.89 | 17.22 | 0.80 |
| 6 | 338 | 1081 | 73.95 | 21.05 | 0.95 |
| 7 | 393 | 1196 | 79.96 | 22.77 | 1.01 |
| 8 | 451 | 1303 | 85.14 | 24.46 | 1.07 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1796 | 24.00 | 7.62 | 0.48 |
| 2| 1927 | 25.55 | 8.71 | 0.50 |
| 3| 2017 | 25.95 | 9.49 | 0.52 |
| 5| 2406 | 32.25 | 12.58 | 0.61 |
| 10| 3062 | 39.71 | 18.00 | 0.74 |
| 42| 7851 | 99.32 | 55.92 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 22.50 | 7.29 | 0.41 |
| 2| 764 | 23.56 | 8.22 | 0.43 |
| 3| 909 | 25.58 | 9.49 | 0.47 |
| 5| 1227 | 30.10 | 12.07 | 0.53 |
| 10| 2194 | 44.22 | 19.33 | 0.74 |
| 41| 6636 | 98.99 | 55.20 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 651 | 29.13 | 8.90 | 0.48 |
| 2| 775 | 28.47 | 9.38 | 0.48 |
| 3| 1013 | 33.47 | 11.46 | 0.55 |
| 5| 1328 | 38.38 | 14.19 | 0.62 |
| 10| 1860 | 45.49 | 19.44 | 0.74 |
| 36| 5999 | 96.68 | 51.26 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 33.83 | 10.16 | 0.53 |
| 2| 859 | 36.60 | 11.61 | 0.57 |
| 3| 903 | 37.24 | 12.41 | 0.58 |
| 5| 1161 | 41.11 | 14.82 | 0.64 |
| 10| 2057 | 54.66 | 22.00 | 0.84 |
| 28| 4848 | 96.72 | 45.72 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 27.00 | 9.07 | 0.69 |
| 2| 5992 | 36.89 | 12.43 | 0.80 |
| 3| 6153 | 46.51 | 15.75 | 0.91 |
| 4| 6255 | 54.84 | 18.49 | 1.00 |
| 5| 6505 | 64.49 | 21.84 | 1.11 |
| 6| 6516 | 70.98 | 23.95 | 1.18 |
| 7| 6807 | 84.45 | 28.49 | 1.34 |
| 8| 6842 | 90.35 | 30.45 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5869 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 285 | 6005 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 568 | 6173 | 39.51 | 14.45 | 0.85 |
| 10 | 30 | 1709 | 6856 | 79.15 | 30.16 | 1.31 |
| 10 | 39 | 2220 | 7159 | 99.12 | 37.95 | 1.54 |

