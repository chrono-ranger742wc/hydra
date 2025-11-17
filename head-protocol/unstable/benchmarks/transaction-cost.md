--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2025-11-17 05:36:17.809868473 UTC |
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
| 1| 5837 | 10.38 | 3.29 | 0.51 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6242 | 15.07 | 4.78 | 0.58 |
| 5| 6646 | 18.64 | 5.88 | 0.64 |
| 10| 7647 | 28.71 | 9.03 | 0.78 |
| 43| 14285 | 99.16 | 31.00 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 556 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2172 | 12.13 | 7.25 | 0.40 |
| 54| 10062 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 34.31 | 9.88 | 0.53 |
| 3 | 171 | 747 | 43.59 | 12.49 | 0.63 |
| 4 | 227 | 858 | 50.68 | 14.55 | 0.70 |
| 5 | 282 | 974 | 55.78 | 16.23 | 0.76 |
| 6 | 338 | 1081 | 67.44 | 19.38 | 0.88 |
| 7 | 395 | 1192 | 77.01 | 22.15 | 0.98 |
| 8 | 449 | 1303 | 90.51 | 25.89 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.37 | 7.71 | 0.48 |
| 2| 1928 | 25.76 | 8.76 | 0.51 |
| 3| 2091 | 27.39 | 9.88 | 0.53 |
| 5| 2385 | 31.37 | 12.33 | 0.60 |
| 10| 3371 | 44.61 | 19.38 | 0.80 |
| 39| 7495 | 97.43 | 53.36 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 22.80 | 7.36 | 0.42 |
| 2| 779 | 24.32 | 8.46 | 0.44 |
| 3| 942 | 26.94 | 9.87 | 0.48 |
| 5| 1345 | 33.55 | 13.02 | 0.57 |
| 10| 2141 | 42.07 | 18.74 | 0.72 |
| 43| 6671 | 98.31 | 56.35 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.13 | 8.90 | 0.48 |
| 2| 833 | 29.26 | 9.62 | 0.49 |
| 3| 979 | 33.39 | 11.44 | 0.55 |
| 5| 1328 | 35.69 | 13.45 | 0.59 |
| 10| 1997 | 46.99 | 19.91 | 0.76 |
| 37| 6035 | 98.82 | 52.52 | 1.59 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 695 | 33.83 | 10.16 | 0.53 |
| 2| 811 | 35.88 | 11.39 | 0.56 |
| 3| 945 | 37.80 | 12.59 | 0.59 |
| 5| 1298 | 42.68 | 15.29 | 0.66 |
| 10| 1996 | 53.50 | 21.63 | 0.83 |
| 29| 4795 | 97.57 | 46.58 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5781 | 27.16 | 9.12 | 0.69 |
| 2| 5961 | 35.91 | 12.06 | 0.79 |
| 3| 6060 | 45.07 | 15.16 | 0.89 |
| 4| 6271 | 54.67 | 18.42 | 1.00 |
| 5| 6627 | 67.23 | 22.77 | 1.15 |
| 6| 6636 | 74.52 | 25.21 | 1.23 |
| 7| 6769 | 84.06 | 28.32 | 1.33 |
| 8| 6796 | 88.88 | 29.96 | 1.38 |
| 10| 6861 | 96.98 | 32.52 | 1.47 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.30 | 6.11 | 0.60 |
| 10 | 1 | 57 | 5869 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6005 | 29.98 | 10.65 | 0.73 |
| 10 | 10 | 568 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6513 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2219 | 7158 | 99.56 | 38.10 | 1.54 |

