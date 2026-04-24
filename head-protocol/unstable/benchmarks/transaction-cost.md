--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-24 06:33:55.461739777 UTC |
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
| 1| 5837 | 10.19 | 3.22 | 0.51 |
| 2| 6038 | 12.61 | 4.00 | 0.55 |
| 3| 6239 | 14.52 | 4.59 | 0.58 |
| 5| 6641 | 18.43 | 5.81 | 0.63 |
| 10| 7647 | 28.80 | 9.07 | 0.78 |
| 43| 14285 | 99.32 | 31.06 | 1.81 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1271 | 6.41 | 3.60 | 0.28 |
| 10| 2179 | 12.13 | 7.25 | 0.40 |
| 54| 10066 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 113 | 636 | 33.25 | 9.62 | 0.52 |
| 3 | 171 | 747 | 42.50 | 12.22 | 0.61 |
| 4 | 226 | 858 | 48.35 | 14.05 | 0.68 |
| 5 | 284 | 969 | 59.03 | 16.97 | 0.79 |
| 6 | 339 | 1081 | 73.64 | 20.90 | 0.94 |
| 7 | 392 | 1196 | 81.10 | 23.14 | 1.02 |
| 8 | 451 | 1303 | 82.20 | 23.96 | 1.04 |
| 9 | 506 | 1414 | 93.15 | 26.83 | 1.16 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1793 | 24.29 | 7.69 | 0.48 |
| 2| 1884 | 24.40 | 8.39 | 0.49 |
| 3| 2059 | 27.39 | 9.88 | 0.53 |
| 5| 2279 | 28.81 | 11.63 | 0.57 |
| 10| 3237 | 41.23 | 18.42 | 0.76 |
| 41| 7645 | 96.57 | 54.48 | 1.66 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 636 | 22.54 | 7.30 | 0.41 |
| 2| 772 | 24.08 | 8.42 | 0.44 |
| 3| 929 | 25.03 | 9.30 | 0.46 |
| 5| 1182 | 29.11 | 11.79 | 0.52 |
| 10| 2162 | 41.99 | 18.72 | 0.72 |
| 44| 6860 | 99.86 | 57.45 | 1.67 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 706 | 27.50 | 8.46 | 0.46 |
| 2| 736 | 30.27 | 9.86 | 0.50 |
| 3| 872 | 32.05 | 11.02 | 0.53 |
| 5| 1290 | 37.73 | 13.99 | 0.61 |
| 10| 1875 | 45.94 | 19.59 | 0.75 |
| 36| 5949 | 98.46 | 51.72 | 1.58 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 684 | 33.83 | 10.15 | 0.53 |
| 2| 824 | 35.85 | 11.38 | 0.56 |
| 3| 952 | 38.21 | 12.71 | 0.59 |
| 5| 1270 | 42.68 | 15.29 | 0.66 |
| 10| 2056 | 54.92 | 22.06 | 0.84 |
| 28| 4818 | 97.23 | 45.83 | 1.48 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5812 | 27.08 | 9.08 | 0.69 |
| 2| 5989 | 37.09 | 12.50 | 0.80 |
| 3| 6066 | 44.78 | 15.06 | 0.89 |
| 4| 6429 | 56.63 | 19.21 | 1.03 |
| 5| 6495 | 66.07 | 22.38 | 1.13 |
| 6| 6561 | 72.96 | 24.59 | 1.21 |
| 7| 6627 | 76.57 | 25.76 | 1.25 |
| 8| 7155 | 97.20 | 32.93 | 1.49 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 285 | 6004 | 28.90 | 10.28 | 0.72 |
| 10 | 39 | 2219 | 7159 | 98.05 | 37.58 | 1.53 |

