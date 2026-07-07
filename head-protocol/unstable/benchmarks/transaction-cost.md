--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-07-07 08:10:26.32576393 UTC |
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
| 1| 5836 | 10.38 | 3.29 | 0.51 |
| 2| 6039 | 12.42 | 3.93 | 0.54 |
| 3| 6236 | 14.31 | 4.52 | 0.57 |
| 5| 6640 | 18.96 | 6.00 | 0.64 |
| 10| 7646 | 28.88 | 9.10 | 0.79 |
| 43| 14282 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 56 | 524 | 25.24 | 7.32 | 0.43 |
| 2 | 114 | 636 | 34.19 | 9.84 | 0.53 |
| 3 | 169 | 747 | 43.68 | 12.51 | 0.63 |
| 4 | 226 | 858 | 53.33 | 15.21 | 0.73 |
| 5 | 282 | 969 | 64.58 | 18.36 | 0.85 |
| 6 | 338 | 1081 | 73.50 | 20.80 | 0.94 |
| 7 | 397 | 1192 | 78.24 | 22.36 | 1.00 |
| 8 | 451 | 1303 | 88.94 | 25.31 | 1.11 |
| 9 | 505 | 1414 | 91.09 | 26.22 | 1.14 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.37 | 7.71 | 0.48 |
| 2| 1879 | 24.80 | 8.49 | 0.49 |
| 3| 2060 | 27.02 | 9.79 | 0.53 |
| 5| 2335 | 30.04 | 11.97 | 0.58 |
| 10| 3035 | 38.55 | 17.70 | 0.72 |
| 42| 7846 | 99.18 | 55.87 | 1.70 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 22.54 | 7.31 | 0.41 |
| 2| 758 | 23.61 | 8.24 | 0.43 |
| 3| 914 | 25.06 | 9.31 | 0.46 |
| 5| 1187 | 28.08 | 11.49 | 0.51 |
| 10| 1842 | 37.63 | 17.50 | 0.66 |
| 42| 6539 | 94.28 | 54.61 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 701 | 27.54 | 8.47 | 0.46 |
| 2| 807 | 30.94 | 10.07 | 0.51 |
| 3| 931 | 32.76 | 11.24 | 0.54 |
| 5| 1387 | 36.39 | 13.66 | 0.60 |
| 10| 2088 | 45.98 | 19.69 | 0.76 |
| 37| 6139 | 99.21 | 52.62 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 33.87 | 10.16 | 0.53 |
| 2| 825 | 35.85 | 11.38 | 0.56 |
| 3| 987 | 38.47 | 12.79 | 0.60 |
| 5| 1266 | 42.56 | 15.26 | 0.66 |
| 10| 2054 | 54.05 | 21.81 | 0.83 |
| 28| 4853 | 98.10 | 46.11 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5804 | 27.08 | 9.09 | 0.69 |
| 2| 5968 | 35.84 | 12.03 | 0.79 |
| 3| 6211 | 47.14 | 15.91 | 0.92 |
| 4| 6239 | 55.11 | 18.57 | 1.00 |
| 5| 6432 | 64.49 | 21.76 | 1.11 |
| 6| 6649 | 75.25 | 25.37 | 1.23 |
| 7| 6853 | 85.28 | 28.82 | 1.35 |
| 8| 6951 | 93.54 | 31.52 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.63 | 6.56 | 0.61 |
| 10 | 5 | 284 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 10 | 570 | 6175 | 38.18 | 14.00 | 0.83 |
| 10 | 20 | 1141 | 6515 | 60.61 | 22.74 | 1.09 |
| 10 | 30 | 1704 | 6851 | 81.37 | 30.91 | 1.33 |
| 10 | 40 | 2275 | 7191 | 99.66 | 38.24 | 1.55 |

