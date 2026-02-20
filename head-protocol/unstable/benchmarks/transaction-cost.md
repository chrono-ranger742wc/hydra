--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-20 05:41:51.799940515 UTC |
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
| 1| 5836 | 10.61 | 3.37 | 0.52 |
| 2| 6038 | 12.41 | 3.92 | 0.54 |
| 3| 6236 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.60 | 5.87 | 0.64 |
| 10| 7646 | 29.21 | 9.21 | 0.79 |
| 43| 14281 | 98.76 | 30.86 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 559 | 2.44 | 1.16 | 0.20 |
| 2| 740 | 3.38 | 1.73 | 0.22 |
| 3| 919 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10084 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 43.73 | 12.51 | 0.63 |
| 4 | 225 | 858 | 48.20 | 13.99 | 0.68 |
| 5 | 283 | 969 | 57.78 | 16.67 | 0.78 |
| 6 | 339 | 1081 | 64.70 | 18.80 | 0.86 |
| 7 | 394 | 1192 | 80.66 | 23.11 | 1.02 |
| 8 | 451 | 1303 | 91.71 | 26.08 | 1.14 |
| 10 | 560 | 1525 | 99.66 | 28.79 | 1.23 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1811 | 24.37 | 7.71 | 0.48 |
| 2| 1953 | 25.80 | 8.77 | 0.51 |
| 3| 2122 | 28.34 | 10.15 | 0.55 |
| 5| 2321 | 30.22 | 12.01 | 0.58 |
| 10| 3175 | 40.73 | 18.30 | 0.75 |
| 38| 7516 | 97.49 | 52.74 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 659 | 22.54 | 7.31 | 0.41 |
| 2| 751 | 24.35 | 8.48 | 0.44 |
| 3| 904 | 25.51 | 9.48 | 0.46 |
| 5| 1142 | 28.15 | 11.50 | 0.51 |
| 10| 1987 | 38.47 | 17.73 | 0.68 |
| 39| 6097 | 89.35 | 51.21 | 1.51 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 597 | 28.46 | 8.69 | 0.47 |
| 2| 813 | 30.94 | 10.07 | 0.51 |
| 3| 948 | 30.90 | 10.74 | 0.52 |
| 5| 1193 | 36.27 | 13.55 | 0.59 |
| 10| 2088 | 44.71 | 19.32 | 0.74 |
| 36| 5871 | 96.50 | 51.19 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 688 | 33.87 | 10.16 | 0.53 |
| 2| 809 | 35.89 | 11.39 | 0.56 |
| 3| 954 | 37.88 | 12.61 | 0.59 |
| 5| 1356 | 44.03 | 15.70 | 0.68 |
| 10| 2138 | 55.56 | 22.26 | 0.85 |
| 29| 5064 | 99.79 | 47.25 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5697 | 22.97 | 7.57 | 0.64 |
| 2| 5946 | 35.77 | 12.03 | 0.79 |
| 3| 5955 | 40.28 | 13.45 | 0.83 |
| 4| 6252 | 54.99 | 18.52 | 1.00 |
| 5| 6317 | 58.02 | 19.48 | 1.04 |
| 6| 6655 | 74.36 | 25.10 | 1.22 |
| 7| 6712 | 79.67 | 26.84 | 1.28 |
| 8| 6951 | 92.99 | 31.34 | 1.43 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 19.38 | 6.48 | 0.61 |
| 10 | 5 | 285 | 6004 | 29.79 | 10.58 | 0.73 |
| 10 | 20 | 1137 | 6511 | 59.98 | 22.53 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2219 | 7158 | 98.93 | 37.88 | 1.54 |

