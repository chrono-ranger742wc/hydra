--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-05-29 08:19:52.643828818 UTC |
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
| 1| 5834 | 10.57 | 3.36 | 0.52 |
| 2| 6037 | 12.25 | 3.87 | 0.54 |
| 3| 6236 | 14.50 | 4.58 | 0.57 |
| 5| 6640 | 18.41 | 5.80 | 0.63 |
| 10| 7647 | 29.14 | 9.19 | 0.79 |
| 43| 14282 | 99.04 | 30.96 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 558 | 2.44 | 1.16 | 0.20 |
| 2| 736 | 3.38 | 1.73 | 0.22 |
| 3| 923 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2180 | 12.13 | 7.25 | 0.40 |
| 54| 10042 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 32.27 | 9.39 | 0.51 |
| 3 | 171 | 747 | 40.24 | 11.69 | 0.59 |
| 4 | 226 | 858 | 52.65 | 15.08 | 0.72 |
| 5 | 283 | 974 | 62.50 | 17.80 | 0.83 |
| 6 | 339 | 1081 | 66.33 | 19.12 | 0.87 |
| 7 | 392 | 1196 | 80.17 | 22.86 | 1.02 |
| 8 | 450 | 1303 | 89.94 | 25.61 | 1.12 |
| 9 | 507 | 1414 | 89.04 | 25.84 | 1.12 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1789 | 24.37 | 7.71 | 0.48 |
| 2| 1938 | 25.47 | 8.70 | 0.50 |
| 3| 2060 | 27.32 | 9.86 | 0.53 |
| 5| 2333 | 30.26 | 12.02 | 0.58 |
| 10| 3070 | 39.99 | 18.07 | 0.74 |
| 42| 7721 | 98.84 | 55.74 | 1.69 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 643 | 22.54 | 7.31 | 0.41 |
| 2| 730 | 22.60 | 7.95 | 0.42 |
| 3| 921 | 25.10 | 9.32 | 0.46 |
| 5| 1165 | 28.08 | 11.49 | 0.51 |
| 10| 1927 | 39.29 | 17.99 | 0.68 |
| 41| 6533 | 97.04 | 54.72 | 1.62 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 602 | 28.46 | 8.69 | 0.47 |
| 2| 828 | 29.26 | 9.62 | 0.49 |
| 3| 1091 | 32.28 | 11.17 | 0.54 |
| 5| 1252 | 37.14 | 13.81 | 0.60 |
| 10| 2015 | 45.02 | 19.40 | 0.74 |
| 35| 5812 | 96.43 | 50.50 | 1.55 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 697 | 33.87 | 10.16 | 0.53 |
| 2| 853 | 36.64 | 11.62 | 0.57 |
| 3| 1051 | 39.27 | 13.03 | 0.61 |
| 5| 1261 | 42.49 | 15.24 | 0.66 |
| 10| 2113 | 55.13 | 22.15 | 0.85 |
| 29| 4800 | 96.60 | 46.28 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5805 | 27.05 | 9.07 | 0.69 |
| 2| 5963 | 36.03 | 12.09 | 0.79 |
| 3| 6049 | 44.89 | 15.11 | 0.89 |
| 4| 6237 | 53.80 | 18.12 | 0.99 |
| 5| 6403 | 61.17 | 20.62 | 1.07 |
| 6| 6450 | 68.33 | 22.89 | 1.15 |
| 7| 6766 | 82.39 | 27.77 | 1.31 |
| 8| 6882 | 93.48 | 31.57 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 58 | 5869 | 20.78 | 7.06 | 0.63 |
| 10 | 5 | 282 | 6001 | 29.79 | 10.58 | 0.73 |
| 10 | 10 | 570 | 6175 | 40.39 | 14.75 | 0.85 |
| 10 | 20 | 1137 | 6511 | 59.54 | 22.38 | 1.08 |
| 10 | 30 | 1707 | 6853 | 80.04 | 30.46 | 1.32 |
| 10 | 39 | 2219 | 7159 | 99.38 | 38.04 | 1.54 |

