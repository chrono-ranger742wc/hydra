--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-16 06:45:31.080767643 UTC |
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
| 1| 5840 | 10.28 | 3.25 | 0.51 |
| 2| 6037 | 12.34 | 3.90 | 0.54 |
| 3| 6236 | 14.69 | 4.65 | 0.58 |
| 5| 6646 | 18.62 | 5.87 | 0.64 |
| 10| 7646 | 29.02 | 9.14 | 0.79 |
| 43| 14281 | 98.99 | 30.94 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 918 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2174 | 12.13 | 7.25 | 0.40 |
| 54| 10047 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 33.33 | 9.64 | 0.52 |
| 3 | 170 | 747 | 41.38 | 11.95 | 0.60 |
| 4 | 227 | 862 | 49.55 | 14.31 | 0.69 |
| 5 | 281 | 969 | 60.95 | 17.46 | 0.81 |
| 6 | 338 | 1081 | 66.40 | 19.13 | 0.87 |
| 7 | 394 | 1192 | 83.20 | 23.64 | 1.05 |
| 8 | 449 | 1303 | 96.36 | 27.15 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1791 | 23.92 | 7.60 | 0.48 |
| 2| 1882 | 24.40 | 8.40 | 0.49 |
| 3| 2067 | 27.32 | 9.86 | 0.53 |
| 5| 2279 | 28.81 | 11.63 | 0.57 |
| 10| 3235 | 42.27 | 18.70 | 0.77 |
| 40| 7603 | 96.72 | 53.87 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 619 | 22.53 | 7.31 | 0.41 |
| 2| 796 | 24.28 | 8.45 | 0.44 |
| 3| 873 | 25.09 | 9.32 | 0.46 |
| 5| 1236 | 29.63 | 11.95 | 0.53 |
| 10| 1989 | 39.56 | 18.05 | 0.69 |
| 42| 6620 | 97.86 | 55.58 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 656 | 29.13 | 8.90 | 0.48 |
| 2| 794 | 30.98 | 10.08 | 0.51 |
| 3| 906 | 30.26 | 10.55 | 0.51 |
| 5| 1360 | 35.61 | 13.43 | 0.59 |
| 10| 1989 | 44.25 | 19.18 | 0.73 |
| 36| 5735 | 99.91 | 52.00 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.79 | 10.15 | 0.53 |
| 2| 844 | 36.64 | 11.62 | 0.57 |
| 3| 963 | 37.91 | 12.62 | 0.59 |
| 5| 1283 | 42.49 | 15.24 | 0.66 |
| 10| 2040 | 53.95 | 21.78 | 0.83 |
| 29| 4734 | 96.82 | 46.32 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5698 | 22.97 | 7.58 | 0.64 |
| 2| 5964 | 35.99 | 12.08 | 0.79 |
| 3| 6099 | 44.64 | 15.00 | 0.89 |
| 4| 6334 | 54.77 | 18.46 | 1.00 |
| 5| 6364 | 64.14 | 21.64 | 1.10 |
| 6| 6610 | 72.10 | 24.28 | 1.20 |
| 7| 6658 | 83.16 | 27.98 | 1.32 |
| 8| 6814 | 86.72 | 29.16 | 1.36 |
| 9| 6924 | 95.30 | 32.05 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5869 | 22.10 | 7.52 | 0.64 |
| 10 | 5 | 284 | 6004 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 568 | 6172 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1140 | 6515 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 38 | 2164 | 7126 | 97.33 | 37.23 | 1.52 |

