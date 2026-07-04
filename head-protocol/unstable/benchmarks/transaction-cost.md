--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-04 07:20:07.732723358 UTC |
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
| 1| 5837 | 10.59 | 3.36 | 0.52 |
| 2| 6038 | 12.92 | 4.11 | 0.55 |
| 3| 6240 | 14.52 | 4.59 | 0.58 |
| 5| 6638 | 19.00 | 6.01 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14282 | 98.87 | 30.90 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1275 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10068 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 170 | 747 | 43.61 | 12.48 | 0.63 |
| 4 | 226 | 858 | 47.91 | 13.89 | 0.68 |
| 5 | 282 | 969 | 55.60 | 16.15 | 0.76 |
| 6 | 339 | 1081 | 75.38 | 21.28 | 0.96 |
| 7 | 396 | 1192 | 82.82 | 23.58 | 1.04 |
| 8 | 451 | 1303 | 87.38 | 24.95 | 1.09 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 24.00 | 7.62 | 0.48 |
| 2| 1932 | 25.85 | 8.78 | 0.51 |
| 3| 2059 | 26.98 | 9.78 | 0.53 |
| 5| 2393 | 30.95 | 12.23 | 0.59 |
| 10| 3128 | 40.55 | 18.24 | 0.75 |
| 37| 7418 | 96.60 | 51.80 | 1.63 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 604 | 22.80 | 7.38 | 0.41 |
| 2| 697 | 22.62 | 7.95 | 0.42 |
| 3| 1015 | 28.20 | 10.20 | 0.50 |
| 5| 1249 | 31.33 | 12.42 | 0.55 |
| 10| 2025 | 39.62 | 18.05 | 0.69 |
| 43| 6842 | 99.00 | 56.56 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 669 | 29.09 | 8.89 | 0.48 |
| 2| 770 | 28.55 | 9.40 | 0.48 |
| 3| 982 | 30.98 | 10.76 | 0.52 |
| 5| 1226 | 37.10 | 13.80 | 0.60 |
| 10| 1925 | 46.80 | 19.84 | 0.76 |
| 35| 5839 | 97.18 | 50.74 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 708 | 33.79 | 10.15 | 0.53 |
| 2| 769 | 35.21 | 11.18 | 0.55 |
| 3| 946 | 37.84 | 12.60 | 0.59 |
| 5| 1279 | 42.49 | 15.24 | 0.66 |
| 10| 1927 | 52.52 | 21.35 | 0.81 |
| 28| 4797 | 97.00 | 45.78 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5792 | 27.13 | 9.10 | 0.69 |
| 2| 5850 | 31.48 | 10.48 | 0.74 |
| 3| 6070 | 44.90 | 15.09 | 0.89 |
| 4| 6387 | 55.91 | 18.85 | 1.02 |
| 5| 6183 | 54.61 | 18.23 | 0.99 |
| 6| 6574 | 74.31 | 25.05 | 1.22 |
| 7| 6569 | 78.52 | 26.37 | 1.26 |
| 8| 6909 | 92.57 | 31.12 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 29.53 | 10.50 | 0.73 |
| 10 | 10 | 568 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1137 | 6511 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6855 | 79.60 | 30.31 | 1.31 |
| 10 | 40 | 2279 | 7195 | 99.22 | 38.09 | 1.54 |
| 10 | 38 | 2164 | 7126 | 96.00 | 36.77 | 1.50 |

