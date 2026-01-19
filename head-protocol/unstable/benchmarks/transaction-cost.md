--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-19 05:21:15.578546562 UTC |
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
| 2| 6037 | 12.65 | 4.01 | 0.55 |
| 3| 6239 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.41 | 5.80 | 0.63 |
| 10| 7650 | 29.02 | 9.14 | 0.79 |
| 43| 14282 | 98.56 | 30.79 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1276 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10072 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 33.25 | 9.61 | 0.52 |
| 3 | 170 | 747 | 43.74 | 12.55 | 0.63 |
| 4 | 227 | 862 | 54.07 | 15.42 | 0.74 |
| 5 | 283 | 969 | 58.93 | 16.98 | 0.79 |
| 6 | 337 | 1081 | 64.85 | 18.84 | 0.86 |
| 7 | 394 | 1192 | 84.96 | 24.02 | 1.06 |
| 8 | 449 | 1303 | 90.26 | 25.79 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1797 | 24.00 | 7.62 | 0.48 |
| 2| 2009 | 26.83 | 9.06 | 0.52 |
| 3| 2089 | 27.06 | 9.80 | 0.53 |
| 5| 2280 | 29.18 | 11.72 | 0.57 |
| 10| 3130 | 40.04 | 18.08 | 0.74 |
| 41| 7621 | 98.59 | 55.03 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 623 | 22.84 | 7.39 | 0.42 |
| 2| 705 | 22.58 | 7.94 | 0.42 |
| 3| 901 | 25.79 | 9.53 | 0.47 |
| 5| 1185 | 28.01 | 11.47 | 0.51 |
| 10| 1858 | 36.61 | 17.22 | 0.65 |
| 41| 6800 | 98.09 | 55.00 | 1.64 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 27.54 | 8.47 | 0.46 |
| 2| 832 | 29.26 | 9.62 | 0.49 |
| 3| 902 | 30.23 | 10.54 | 0.51 |
| 5| 1234 | 37.02 | 13.77 | 0.60 |
| 10| 2083 | 45.69 | 19.60 | 0.75 |
| 35| 5956 | 96.35 | 50.50 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 708 | 33.87 | 10.16 | 0.53 |
| 2| 816 | 35.92 | 11.40 | 0.56 |
| 3| 998 | 38.59 | 12.82 | 0.60 |
| 5| 1260 | 42.65 | 15.28 | 0.66 |
| 10| 2059 | 54.51 | 21.94 | 0.84 |
| 30| 4974 | 99.96 | 47.90 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 23.01 | 7.58 | 0.64 |
| 2| 5917 | 35.81 | 12.02 | 0.79 |
| 3| 6113 | 44.79 | 15.09 | 0.89 |
| 4| 6433 | 57.45 | 19.43 | 1.04 |
| 5| 6511 | 66.47 | 22.46 | 1.14 |
| 6| 6522 | 71.38 | 23.99 | 1.19 |
| 7| 6561 | 74.34 | 24.87 | 1.22 |
| 8| 7057 | 94.35 | 31.99 | 1.45 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.12 | 6.39 | 0.61 |
| 10 | 1 | 57 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 284 | 6003 | 28.90 | 10.28 | 0.72 |
| 10 | 20 | 1138 | 6512 | 59.10 | 22.22 | 1.07 |
| 10 | 30 | 1706 | 6852 | 80.92 | 30.76 | 1.33 |
| 10 | 40 | 2276 | 7193 | 99.84 | 38.30 | 1.55 |

