--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-27 15:34:38.542836532 UTC |
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
| 1| 5840 | 10.59 | 3.36 | 0.52 |
| 2| 6037 | 13.01 | 4.14 | 0.55 |
| 3| 6239 | 14.60 | 4.62 | 0.58 |
| 5| 6641 | 18.84 | 5.95 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14281 | 99.33 | 31.06 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2177 | 12.13 | 7.25 | 0.40 |
| 54| 10065 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 33.32 | 9.64 | 0.52 |
| 3 | 171 | 747 | 41.12 | 11.90 | 0.60 |
| 4 | 227 | 858 | 48.46 | 14.08 | 0.68 |
| 5 | 283 | 969 | 59.36 | 17.05 | 0.80 |
| 6 | 339 | 1081 | 63.82 | 18.51 | 0.85 |
| 7 | 395 | 1196 | 83.03 | 23.60 | 1.04 |
| 8 | 452 | 1303 | 81.46 | 23.63 | 1.04 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 23.92 | 7.60 | 0.48 |
| 2| 1950 | 25.88 | 8.79 | 0.51 |
| 3| 2059 | 27.36 | 9.87 | 0.53 |
| 5| 2508 | 33.40 | 12.90 | 0.62 |
| 10| 3186 | 40.84 | 18.31 | 0.75 |
| 40| 7579 | 99.47 | 54.59 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 631 | 22.50 | 7.29 | 0.41 |
| 2| 743 | 24.31 | 8.47 | 0.44 |
| 3| 903 | 25.72 | 9.52 | 0.47 |
| 5| 1165 | 27.97 | 11.46 | 0.51 |
| 10| 2103 | 41.64 | 18.63 | 0.71 |
| 40| 6650 | 99.73 | 54.75 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 692 | 27.47 | 8.46 | 0.46 |
| 2| 740 | 30.27 | 9.86 | 0.50 |
| 3| 864 | 32.08 | 11.03 | 0.53 |
| 5| 1314 | 35.71 | 13.45 | 0.59 |
| 10| 2107 | 45.56 | 19.57 | 0.75 |
| 36| 5918 | 96.82 | 51.29 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 685 | 33.83 | 10.16 | 0.53 |
| 2| 768 | 35.21 | 11.18 | 0.55 |
| 3| 1018 | 38.62 | 12.83 | 0.60 |
| 5| 1204 | 41.82 | 15.03 | 0.65 |
| 10| 1929 | 52.82 | 21.42 | 0.82 |
| 29| 5007 | 99.87 | 47.27 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5801 | 26.97 | 9.07 | 0.69 |
| 2| 5941 | 36.08 | 12.13 | 0.79 |
| 3| 5898 | 37.08 | 12.29 | 0.80 |
| 4| 6269 | 55.01 | 18.57 | 1.00 |
| 5| 6511 | 64.66 | 21.83 | 1.12 |
| 6| 6701 | 74.82 | 25.28 | 1.23 |
| 7| 6710 | 82.72 | 27.86 | 1.31 |
| 8| 6999 | 93.65 | 31.65 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.63 | 6.56 | 0.61 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 10 | 569 | 6174 | 39.25 | 14.36 | 0.84 |
| 10 | 40 | 2279 | 7195 | 99.66 | 38.24 | 1.55 |
| 10 | 38 | 2161 | 7124 | 96.44 | 36.92 | 1.51 |

