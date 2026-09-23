--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-23 09:39:45.093219422 UTC |
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
| 1| 5838 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.41 | 3.92 | 0.54 |
| 3| 6239 | 14.60 | 4.62 | 0.58 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7647 | 28.90 | 9.10 | 0.79 |
| 43| 14281 | 99.06 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1280 | 6.41 | 3.60 | 0.28 |
| 10| 2169 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 637 | 34.38 | 9.91 | 0.53 |
| 3 | 169 | 747 | 43.79 | 12.52 | 0.63 |
| 4 | 226 | 858 | 52.26 | 14.96 | 0.72 |
| 5 | 283 | 969 | 56.12 | 16.31 | 0.76 |
| 6 | 341 | 1081 | 70.50 | 20.07 | 0.91 |
| 7 | 396 | 1192 | 72.88 | 21.21 | 0.94 |
| 8 | 450 | 1307 | 90.39 | 25.81 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1944 | 25.92 | 8.80 | 0.51 |
| 3| 2145 | 28.39 | 10.16 | 0.55 |
| 5| 2361 | 30.95 | 12.23 | 0.59 |
| 10| 3136 | 40.94 | 18.34 | 0.75 |
| 40| 7668 | 99.74 | 54.67 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 615 | 22.84 | 7.39 | 0.42 |
| 2| 726 | 22.52 | 7.93 | 0.42 |
| 3| 991 | 26.76 | 9.81 | 0.48 |
| 5| 1222 | 30.05 | 12.05 | 0.53 |
| 10| 1891 | 37.72 | 17.51 | 0.66 |
| 41| 6529 | 95.39 | 54.23 | 1.60 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 702 | 27.54 | 8.47 | 0.46 |
| 2| 736 | 30.27 | 9.86 | 0.50 |
| 3| 925 | 32.76 | 11.24 | 0.54 |
| 5| 1178 | 36.31 | 13.56 | 0.59 |
| 10| 1992 | 44.37 | 19.20 | 0.73 |
| 35| 5626 | 98.53 | 50.92 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 33.15 | 9.95 | 0.52 |
| 2| 843 | 35.85 | 11.38 | 0.56 |
| 3| 1028 | 38.85 | 12.91 | 0.60 |
| 5| 1321 | 43.32 | 15.49 | 0.67 |
| 10| 1930 | 52.67 | 21.38 | 0.81 |
| 29| 4960 | 98.24 | 46.77 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.00 | 9.06 | 0.69 |
| 2| 5872 | 32.72 | 10.94 | 0.75 |
| 3| 6098 | 44.61 | 15.00 | 0.89 |
| 4| 6236 | 53.64 | 18.06 | 0.99 |
| 5| 6490 | 63.00 | 21.22 | 1.10 |
| 6| 6689 | 75.21 | 25.38 | 1.24 |
| 7| 6546 | 75.88 | 25.50 | 1.24 |
| 8| 6769 | 87.73 | 29.59 | 1.37 |
| 9| 7024 | 99.07 | 33.34 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.30 | 6.11 | 0.60 |
| 10 | 10 | 571 | 6175 | 39.95 | 14.60 | 0.85 |
| 10 | 20 | 1139 | 6514 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1706 | 6852 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2222 | 7161 | 99.12 | 37.95 | 1.54 |

