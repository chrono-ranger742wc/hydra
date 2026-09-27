--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-27 10:23:40.365965509 UTC |
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
| 1| 5841 | 10.19 | 3.22 | 0.51 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6242 | 14.71 | 4.65 | 0.58 |
| 5| 6638 | 18.83 | 5.95 | 0.64 |
| 10| 7646 | 28.94 | 9.11 | 0.79 |
| 43| 14285 | 98.94 | 30.92 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10055 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 113 | 636 | 32.19 | 9.36 | 0.51 |
| 3 | 171 | 747 | 39.93 | 11.62 | 0.59 |
| 4 | 225 | 858 | 54.07 | 15.44 | 0.74 |
| 5 | 282 | 974 | 61.21 | 17.53 | 0.81 |
| 6 | 337 | 1081 | 68.80 | 19.82 | 0.90 |
| 7 | 394 | 1192 | 84.60 | 23.93 | 1.06 |
| 8 | 449 | 1303 | 90.04 | 25.68 | 1.12 |
| 9 | 505 | 1414 | 93.98 | 27.03 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.29 | 7.69 | 0.48 |
| 2| 1958 | 25.43 | 8.69 | 0.50 |
| 3| 2135 | 28.39 | 10.16 | 0.55 |
| 5| 2491 | 34.02 | 13.07 | 0.63 |
| 10| 3132 | 40.67 | 18.27 | 0.75 |
| 40| 7553 | 96.23 | 53.72 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 616 | 22.84 | 7.39 | 0.42 |
| 2| 700 | 22.58 | 7.96 | 0.42 |
| 3| 843 | 24.02 | 9.02 | 0.45 |
| 5| 1267 | 30.71 | 12.25 | 0.54 |
| 10| 1944 | 39.11 | 17.93 | 0.68 |
| 42| 6665 | 97.28 | 55.42 | 1.63 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 672 | 29.13 | 8.90 | 0.48 |
| 2| 741 | 30.23 | 9.85 | 0.50 |
| 3| 1059 | 32.37 | 11.19 | 0.54 |
| 5| 1236 | 36.95 | 13.76 | 0.60 |
| 10| 2018 | 44.71 | 19.32 | 0.74 |
| 34| 5663 | 93.38 | 49.00 | 1.51 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.83 | 10.15 | 0.53 |
| 2| 810 | 35.85 | 11.38 | 0.56 |
| 3| 1039 | 38.66 | 12.84 | 0.60 |
| 5| 1330 | 43.35 | 15.49 | 0.67 |
| 10| 1943 | 52.82 | 21.42 | 0.82 |
| 29| 4950 | 99.59 | 47.20 | 1.51 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5811 | 27.05 | 9.07 | 0.69 |
| 2| 5845 | 31.40 | 10.44 | 0.74 |
| 3| 6093 | 44.64 | 15.03 | 0.89 |
| 4| 6291 | 54.17 | 18.23 | 1.00 |
| 5| 6331 | 62.95 | 21.19 | 1.09 |
| 6| 6501 | 73.08 | 24.57 | 1.20 |
| 7| 6770 | 79.88 | 26.89 | 1.29 |
| 8| 6719 | 86.34 | 28.99 | 1.35 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5869 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 282 | 6002 | 28.46 | 10.13 | 0.72 |
| 10 | 10 | 568 | 6173 | 38.62 | 14.15 | 0.84 |
| 10 | 20 | 1138 | 6512 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1708 | 6854 | 80.48 | 30.61 | 1.32 |
| 10 | 39 | 2220 | 7159 | 98.49 | 37.73 | 1.53 |

