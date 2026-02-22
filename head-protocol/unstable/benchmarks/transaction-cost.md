--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-02-22 05:41:57.021955807 UTC |
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
| 1| 5838 | 10.61 | 3.37 | 0.52 |
| 2| 6037 | 12.46 | 3.94 | 0.55 |
| 3| 6236 | 14.29 | 4.51 | 0.57 |
| 5| 6638 | 18.43 | 5.81 | 0.63 |
| 10| 7646 | 29.00 | 9.14 | 0.79 |
| 43| 14282 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 743 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10061 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.46 | 7.13 | 0.42 |
| 2 | 114 | 636 | 32.20 | 9.36 | 0.51 |
| 3 | 171 | 747 | 40.27 | 11.70 | 0.59 |
| 4 | 225 | 858 | 51.97 | 14.86 | 0.72 |
| 5 | 282 | 969 | 64.45 | 18.27 | 0.85 |
| 6 | 337 | 1081 | 73.26 | 20.77 | 0.94 |
| 7 | 396 | 1192 | 72.52 | 21.04 | 0.94 |
| 8 | 452 | 1303 | 80.84 | 23.47 | 1.03 |
| 9 | 506 | 1414 | 94.09 | 27.00 | 1.17 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1819 | 24.00 | 7.62 | 0.48 |
| 2| 1937 | 25.47 | 8.70 | 0.50 |
| 3| 2120 | 27.93 | 10.05 | 0.54 |
| 5| 2402 | 31.49 | 12.36 | 0.60 |
| 10| 3225 | 42.28 | 18.74 | 0.77 |
| 40| 7618 | 99.50 | 54.60 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 652 | 22.77 | 7.36 | 0.42 |
| 2| 779 | 23.59 | 8.23 | 0.43 |
| 3| 944 | 27.03 | 9.88 | 0.48 |
| 5| 1171 | 28.45 | 11.59 | 0.52 |
| 10| 2030 | 39.19 | 17.97 | 0.69 |
| 38| 6240 | 93.64 | 51.77 | 1.55 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 648 | 29.13 | 8.90 | 0.48 |
| 2| 869 | 29.97 | 9.84 | 0.50 |
| 3| 957 | 33.43 | 11.44 | 0.54 |
| 5| 1365 | 38.56 | 14.24 | 0.62 |
| 10| 2150 | 48.69 | 20.43 | 0.79 |
| 37| 5821 | 96.35 | 51.72 | 1.56 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.79 | 10.15 | 0.53 |
| 2| 852 | 36.64 | 11.62 | 0.57 |
| 3| 942 | 37.87 | 12.61 | 0.59 |
| 5| 1256 | 42.65 | 15.28 | 0.66 |
| 10| 2051 | 54.92 | 22.06 | 0.84 |
| 29| 4987 | 99.73 | 47.23 | 1.52 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5817 | 27.08 | 9.09 | 0.69 |
| 2| 6031 | 36.81 | 12.43 | 0.80 |
| 3| 6052 | 44.89 | 15.09 | 0.89 |
| 4| 6367 | 56.57 | 19.16 | 1.03 |
| 5| 6203 | 54.90 | 18.31 | 1.00 |
| 6| 6538 | 73.02 | 24.57 | 1.21 |
| 7| 6553 | 77.85 | 26.14 | 1.26 |
| 8| 6915 | 91.09 | 30.74 | 1.41 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 20 | 1137 | 6512 | 60.42 | 22.68 | 1.09 |
| 10 | 30 | 1708 | 6854 | 80.04 | 30.46 | 1.32 |
| 10 | 40 | 2276 | 7192 | 99.22 | 38.09 | 1.54 |

