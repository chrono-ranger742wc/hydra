--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-10-14 04:39:33.471991593 UTC |
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
| 1| 5836 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6638 | 18.84 | 5.95 | 0.64 |
| 10| 7646 | 28.90 | 9.10 | 0.79 |
| 43| 14285 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2182 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 171 | 747 | 40.40 | 11.75 | 0.59 |
| 4 | 224 | 858 | 51.15 | 14.70 | 0.71 |
| 5 | 284 | 969 | 64.44 | 18.24 | 0.85 |
| 6 | 337 | 1081 | 67.90 | 19.56 | 0.89 |
| 7 | 395 | 1192 | 84.44 | 23.89 | 1.06 |
| 8 | 453 | 1307 | 98.79 | 27.83 | 1.21 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1785 | 23.92 | 7.60 | 0.48 |
| 2| 1941 | 25.88 | 8.79 | 0.51 |
| 3| 2083 | 27.40 | 9.88 | 0.53 |
| 5| 2321 | 30.12 | 11.99 | 0.58 |
| 10| 3140 | 40.79 | 18.30 | 0.75 |
| 41| 7827 | 98.70 | 55.09 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 626 | 22.81 | 7.37 | 0.42 |
| 2| 770 | 23.98 | 8.37 | 0.44 |
| 3| 974 | 26.06 | 9.59 | 0.47 |
| 5| 1189 | 30.08 | 12.06 | 0.53 |
| 10| 2000 | 39.43 | 18.02 | 0.69 |
| 42| 6515 | 95.75 | 54.97 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 655 | 29.17 | 8.91 | 0.48 |
| 2| 797 | 30.98 | 10.08 | 0.51 |
| 3| 1002 | 31.54 | 10.94 | 0.53 |
| 5| 1212 | 34.18 | 13.00 | 0.57 |
| 10| 2134 | 46.81 | 19.94 | 0.77 |
| 36| 5956 | 97.31 | 51.45 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 693 | 33.83 | 10.15 | 0.53 |
| 2| 769 | 35.14 | 11.16 | 0.55 |
| 3| 941 | 37.80 | 12.59 | 0.59 |
| 5| 1263 | 42.64 | 15.28 | 0.66 |
| 10| 1969 | 53.27 | 21.57 | 0.82 |
| 29| 4989 | 99.71 | 47.21 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5816 | 27.05 | 9.07 | 0.69 |
| 2| 5983 | 37.12 | 12.50 | 0.80 |
| 3| 6140 | 44.69 | 15.06 | 0.89 |
| 4| 6165 | 50.41 | 16.88 | 0.95 |
| 5| 6321 | 61.70 | 20.67 | 1.08 |
| 6| 6562 | 73.16 | 24.68 | 1.21 |
| 7| 6566 | 75.47 | 25.28 | 1.23 |
| 8| 6900 | 90.03 | 30.45 | 1.40 |
| 9| 6979 | 98.72 | 33.31 | 1.50 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 5 | 283 | 6002 | 29.35 | 10.43 | 0.73 |
| 10 | 10 | 570 | 6174 | 38.81 | 14.21 | 0.84 |
| 10 | 20 | 1139 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2215 | 7155 | 99.38 | 38.03 | 1.54 |

