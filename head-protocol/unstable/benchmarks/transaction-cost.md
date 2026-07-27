--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-27 08:04:10.47661916 UTC |
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
| 2| 6035 | 12.54 | 3.97 | 0.55 |
| 3| 6242 | 14.29 | 4.51 | 0.57 |
| 5| 6640 | 18.50 | 5.83 | 0.63 |
| 10| 7650 | 28.80 | 9.07 | 0.78 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2178 | 12.13 | 7.25 | 0.40 |
| 54| 10067 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 113 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 751 | 40.18 | 11.66 | 0.59 |
| 4 | 226 | 858 | 52.34 | 14.96 | 0.72 |
| 5 | 284 | 969 | 56.24 | 16.34 | 0.77 |
| 6 | 340 | 1081 | 68.01 | 19.52 | 0.89 |
| 7 | 395 | 1192 | 86.48 | 24.29 | 1.08 |
| 8 | 449 | 1303 | 98.87 | 27.74 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1794 | 24.00 | 7.62 | 0.48 |
| 2| 1934 | 25.84 | 8.78 | 0.51 |
| 3| 2194 | 28.85 | 10.31 | 0.55 |
| 5| 2541 | 33.23 | 12.86 | 0.62 |
| 10| 3206 | 41.98 | 18.63 | 0.76 |
| 41| 7588 | 95.95 | 54.31 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 653 | 22.81 | 7.37 | 0.42 |
| 2| 776 | 24.04 | 8.41 | 0.44 |
| 3| 906 | 25.12 | 9.33 | 0.46 |
| 5| 1228 | 29.63 | 11.95 | 0.53 |
| 10| 2005 | 39.58 | 18.05 | 0.69 |
| 41| 6449 | 94.87 | 54.08 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 27.50 | 8.46 | 0.46 |
| 2| 897 | 29.97 | 9.84 | 0.50 |
| 3| 1002 | 31.65 | 10.97 | 0.53 |
| 5| 1203 | 36.20 | 13.53 | 0.59 |
| 10| 2043 | 45.20 | 19.46 | 0.75 |
| 35| 5743 | 93.70 | 49.72 | 1.52 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.87 | 10.16 | 0.53 |
| 2| 851 | 36.56 | 11.60 | 0.57 |
| 3| 971 | 37.95 | 12.63 | 0.59 |
| 5| 1196 | 41.86 | 15.04 | 0.65 |
| 10| 2055 | 54.96 | 22.09 | 0.84 |
| 29| 4831 | 97.56 | 46.56 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.13 | 9.10 | 0.69 |
| 2| 5990 | 36.73 | 12.40 | 0.80 |
| 3| 6078 | 44.88 | 15.08 | 0.89 |
| 4| 6267 | 51.30 | 17.22 | 0.96 |
| 5| 6227 | 56.14 | 18.76 | 1.01 |
| 6| 6568 | 72.74 | 24.50 | 1.20 |
| 7| 6631 | 75.15 | 25.25 | 1.23 |
| 8| 6778 | 88.88 | 29.91 | 1.38 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.93 | 6.32 | 0.61 |
| 10 | 1 | 57 | 5869 | 21.41 | 7.28 | 0.63 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1137 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.22 | 30.52 | 1.32 |
| 10 | 39 | 2222 | 7161 | 99.75 | 38.17 | 1.55 |

