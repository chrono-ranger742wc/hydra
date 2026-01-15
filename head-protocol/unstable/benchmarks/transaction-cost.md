--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-15 05:07:21.105283453 UTC |
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
| 1| 5840 | 10.61 | 3.37 | 0.52 |
| 2| 6035 | 12.25 | 3.87 | 0.54 |
| 3| 6238 | 14.69 | 4.65 | 0.58 |
| 5| 6641 | 18.79 | 5.94 | 0.64 |
| 10| 7646 | 29.47 | 9.30 | 0.79 |
| 43| 14282 | 99.02 | 30.95 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 922 | 4.36 | 2.33 | 0.24 |
| 5| 1274 | 6.41 | 3.60 | 0.28 |
| 10| 2165 | 12.13 | 7.25 | 0.40 |
| 54| 10049 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 32.38 | 9.43 | 0.51 |
| 3 | 170 | 747 | 43.49 | 12.45 | 0.62 |
| 4 | 228 | 858 | 50.89 | 14.63 | 0.70 |
| 5 | 284 | 974 | 61.05 | 17.46 | 0.81 |
| 6 | 339 | 1081 | 65.78 | 18.94 | 0.87 |
| 7 | 394 | 1196 | 72.90 | 21.17 | 0.94 |
| 8 | 450 | 1303 | 89.79 | 25.52 | 1.12 |
| 9 | 505 | 1414 | 89.68 | 26.06 | 1.12 |
| 10 | 560 | 1529 | 98.62 | 28.62 | 1.22 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1828 | 24.00 | 7.62 | 0.48 |
| 2| 1952 | 25.85 | 8.78 | 0.51 |
| 3| 2138 | 28.02 | 10.08 | 0.54 |
| 5| 2366 | 31.57 | 12.38 | 0.60 |
| 10| 3155 | 40.55 | 18.24 | 0.75 |
| 40| 7394 | 93.42 | 52.95 | 1.61 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 617 | 22.53 | 7.29 | 0.41 |
| 2| 739 | 24.35 | 8.48 | 0.44 |
| 3| 968 | 26.92 | 9.85 | 0.48 |
| 5| 1119 | 27.05 | 11.20 | 0.50 |
| 10| 2038 | 39.68 | 18.08 | 0.69 |
| 42| 6823 | 99.30 | 56.00 | 1.66 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.09 | 8.89 | 0.48 |
| 2| 790 | 30.98 | 10.08 | 0.51 |
| 3| 963 | 33.47 | 11.46 | 0.55 |
| 5| 1194 | 36.31 | 13.56 | 0.59 |
| 10| 2067 | 48.23 | 20.27 | 0.78 |
| 37| 6126 | 99.54 | 52.72 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 633 | 33.12 | 9.94 | 0.52 |
| 2| 807 | 35.92 | 11.40 | 0.56 |
| 3| 958 | 37.91 | 12.62 | 0.59 |
| 5| 1249 | 42.61 | 15.27 | 0.66 |
| 10| 1914 | 52.48 | 21.34 | 0.81 |
| 28| 4751 | 96.59 | 45.66 | 1.47 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5830 | 27.05 | 9.08 | 0.69 |
| 2| 5953 | 35.98 | 12.10 | 0.79 |
| 3| 6100 | 44.52 | 14.97 | 0.89 |
| 4| 6383 | 56.59 | 19.22 | 1.03 |
| 5| 6372 | 61.58 | 20.73 | 1.08 |
| 6| 6603 | 72.98 | 24.52 | 1.21 |
| 7| 6649 | 78.85 | 26.55 | 1.27 |
| 8| 6746 | 87.65 | 29.42 | 1.37 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 5 | 285 | 6005 | 30.23 | 10.73 | 0.74 |
| 10 | 10 | 571 | 6175 | 37.74 | 13.85 | 0.83 |
| 10 | 39 | 2219 | 7158 | 98.49 | 37.73 | 1.53 |

