--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-03-04 05:33:51.574085513 UTC |
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
| 1| 5837 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.54 | 3.97 | 0.55 |
| 3| 6238 | 14.71 | 4.65 | 0.58 |
| 5| 6641 | 18.72 | 5.91 | 0.64 |
| 10| 7647 | 28.81 | 9.07 | 0.78 |
| 43| 14279 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10057 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 640 | 34.27 | 9.87 | 0.53 |
| 3 | 170 | 747 | 42.73 | 12.31 | 0.62 |
| 4 | 226 | 858 | 52.42 | 15.00 | 0.72 |
| 5 | 283 | 969 | 56.54 | 16.44 | 0.77 |
| 6 | 340 | 1081 | 70.64 | 20.26 | 0.91 |
| 7 | 395 | 1192 | 86.82 | 24.50 | 1.08 |
| 8 | 450 | 1303 | 89.29 | 25.45 | 1.11 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1749 | 22.93 | 7.32 | 0.47 |
| 2| 1958 | 25.85 | 8.78 | 0.51 |
| 3| 2152 | 28.39 | 10.16 | 0.55 |
| 5| 2390 | 31.32 | 12.32 | 0.60 |
| 10| 3062 | 39.99 | 18.07 | 0.74 |
| 40| 7658 | 96.94 | 53.94 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 22.50 | 7.30 | 0.41 |
| 2| 764 | 23.51 | 8.21 | 0.43 |
| 3| 967 | 26.53 | 9.75 | 0.48 |
| 5| 1214 | 28.99 | 11.75 | 0.52 |
| 10| 1956 | 37.82 | 17.55 | 0.67 |
| 43| 6802 | 99.30 | 56.68 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 706 | 27.51 | 8.47 | 0.46 |
| 2| 829 | 31.58 | 10.26 | 0.52 |
| 3| 919 | 32.64 | 11.21 | 0.54 |
| 5| 1270 | 35.04 | 13.25 | 0.58 |
| 10| 2034 | 47.25 | 19.99 | 0.77 |
| 34| 5587 | 97.14 | 49.96 | 1.54 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.79 | 10.15 | 0.53 |
| 2| 884 | 36.52 | 11.59 | 0.57 |
| 3| 1032 | 38.66 | 12.84 | 0.60 |
| 5| 1336 | 43.24 | 15.46 | 0.67 |
| 10| 2166 | 54.84 | 22.06 | 0.85 |
| 29| 5017 | 99.80 | 47.25 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5830 | 27.08 | 9.09 | 0.69 |
| 2| 5953 | 37.09 | 12.50 | 0.80 |
| 3| 6085 | 44.91 | 15.12 | 0.89 |
| 4| 6246 | 55.13 | 18.54 | 1.00 |
| 5| 6553 | 65.99 | 22.37 | 1.13 |
| 6| 6603 | 74.60 | 25.21 | 1.23 |
| 7| 6774 | 82.96 | 27.92 | 1.32 |
| 8| 6883 | 90.28 | 30.42 | 1.40 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.49 | 6.17 | 0.60 |
| 10 | 1 | 56 | 5867 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 283 | 6002 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 569 | 6173 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6511 | 60.35 | 22.66 | 1.09 |
| 10 | 30 | 1706 | 6852 | 79.15 | 30.16 | 1.31 |
| 10 | 37 | 2108 | 7094 | 94.83 | 36.27 | 1.49 |

