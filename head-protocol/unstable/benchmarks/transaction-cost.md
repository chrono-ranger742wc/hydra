--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-09-08 09:09:25.822739946 UTC |
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
| 1| 5836 | 10.95 | 3.49 | 0.52 |
| 2| 6035 | 13.10 | 4.17 | 0.55 |
| 3| 6242 | 14.50 | 4.58 | 0.58 |
| 5| 6643 | 18.41 | 5.80 | 0.63 |
| 10| 7648 | 29.18 | 9.20 | 0.79 |
| 43| 14279 | 99.11 | 30.98 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 556 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2164 | 12.13 | 7.25 | 0.40 |
| 54| 10070 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 171 | 747 | 42.22 | 12.14 | 0.61 |
| 4 | 225 | 862 | 48.15 | 13.95 | 0.68 |
| 5 | 282 | 969 | 59.42 | 17.07 | 0.80 |
| 6 | 337 | 1081 | 69.39 | 19.84 | 0.90 |
| 7 | 394 | 1192 | 82.70 | 23.47 | 1.04 |
| 8 | 451 | 1303 | 85.31 | 24.55 | 1.07 |
| 9 | 506 | 1414 | 96.77 | 27.81 | 1.19 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1815 | 24.37 | 7.71 | 0.48 |
| 2| 2003 | 26.96 | 9.09 | 0.52 |
| 3| 2136 | 28.31 | 10.14 | 0.55 |
| 5| 2434 | 32.52 | 12.65 | 0.61 |
| 10| 3215 | 42.48 | 18.79 | 0.77 |
| 40| 7480 | 95.34 | 53.48 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 637 | 22.81 | 7.37 | 0.42 |
| 2| 815 | 25.59 | 8.80 | 0.46 |
| 3| 883 | 25.58 | 9.49 | 0.46 |
| 5| 1151 | 28.04 | 11.48 | 0.51 |
| 10| 1997 | 38.81 | 17.82 | 0.68 |
| 39| 6620 | 97.22 | 53.41 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 682 | 27.50 | 8.46 | 0.46 |
| 2| 881 | 29.90 | 9.82 | 0.50 |
| 3| 910 | 30.23 | 10.54 | 0.51 |
| 5| 1259 | 37.13 | 13.80 | 0.61 |
| 10| 2030 | 47.36 | 20.02 | 0.77 |
| 34| 5635 | 98.57 | 50.33 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 629 | 33.15 | 9.95 | 0.52 |
| 2| 765 | 35.21 | 11.18 | 0.55 |
| 3| 946 | 37.95 | 12.63 | 0.59 |
| 5| 1342 | 43.13 | 15.44 | 0.67 |
| 10| 2126 | 55.22 | 22.17 | 0.85 |
| 29| 5053 | 99.75 | 47.24 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5810 | 27.09 | 9.09 | 0.69 |
| 2| 5892 | 34.87 | 11.66 | 0.78 |
| 3| 6022 | 43.83 | 14.68 | 0.88 |
| 4| 6319 | 55.89 | 18.87 | 1.02 |
| 5| 6268 | 59.65 | 19.96 | 1.05 |
| 6| 6571 | 74.15 | 25.01 | 1.22 |
| 7| 6727 | 79.53 | 26.83 | 1.28 |
| 8| 7187 | 97.22 | 32.95 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 56 | 5868 | 19.89 | 6.76 | 0.62 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1137 | 6512 | 60.87 | 22.83 | 1.09 |
| 10 | 30 | 1708 | 6854 | 81.37 | 30.91 | 1.33 |
| 10 | 40 | 2280 | 7196 | 99.66 | 38.24 | 1.55 |
| 10 | 38 | 2165 | 7128 | 98.21 | 37.53 | 1.53 |

