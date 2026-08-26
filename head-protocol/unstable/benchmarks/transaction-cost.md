--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-08-26 05:11:44.890244368 UTC |
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
| 1| 5834 | 10.35 | 3.28 | 0.51 |
| 2| 6035 | 12.65 | 4.01 | 0.55 |
| 3| 6239 | 15.14 | 4.81 | 0.58 |
| 5| 6638 | 19.26 | 6.10 | 0.64 |
| 10| 7644 | 29.31 | 9.25 | 0.79 |
| 43| 14279 | 98.66 | 30.82 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 742 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1277 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10073 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.30 | 9.88 | 0.53 |
| 3 | 170 | 747 | 42.33 | 12.19 | 0.61 |
| 4 | 227 | 858 | 47.60 | 13.82 | 0.67 |
| 5 | 282 | 969 | 62.68 | 17.85 | 0.83 |
| 6 | 340 | 1081 | 71.69 | 20.40 | 0.92 |
| 7 | 394 | 1192 | 77.03 | 22.20 | 0.99 |
| 8 | 451 | 1303 | 96.00 | 27.05 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1929 | 25.80 | 8.77 | 0.51 |
| 3| 2077 | 27.35 | 9.87 | 0.53 |
| 5| 2382 | 31.33 | 12.32 | 0.60 |
| 10| 3049 | 38.87 | 17.77 | 0.73 |
| 40| 7642 | 96.21 | 53.73 | 1.65 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 632 | 22.84 | 7.39 | 0.42 |
| 2| 833 | 25.17 | 8.71 | 0.45 |
| 3| 991 | 27.08 | 9.89 | 0.48 |
| 5| 1378 | 32.18 | 12.65 | 0.56 |
| 10| 2021 | 40.88 | 18.41 | 0.70 |
| 40| 6450 | 95.13 | 53.49 | 1.59 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 653 | 29.17 | 8.91 | 0.48 |
| 2| 838 | 29.26 | 9.62 | 0.49 |
| 3| 920 | 32.72 | 11.23 | 0.54 |
| 5| 1337 | 38.38 | 14.19 | 0.62 |
| 10| 2146 | 45.93 | 19.68 | 0.76 |
| 37| 5956 | 97.22 | 52.03 | 1.57 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 674 | 33.87 | 10.16 | 0.53 |
| 2| 811 | 35.81 | 11.37 | 0.56 |
| 3| 1026 | 38.63 | 12.83 | 0.60 |
| 5| 1204 | 41.90 | 15.05 | 0.65 |
| 10| 1993 | 53.54 | 21.64 | 0.83 |
| 29| 4887 | 97.64 | 46.58 | 1.49 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5786 | 27.13 | 9.11 | 0.69 |
| 2| 5976 | 35.96 | 12.08 | 0.79 |
| 3| 6140 | 45.69 | 15.42 | 0.90 |
| 4| 6381 | 55.74 | 18.81 | 1.02 |
| 5| 6459 | 65.06 | 21.95 | 1.12 |
| 6| 6706 | 75.28 | 25.42 | 1.24 |
| 7| 6723 | 80.24 | 27.05 | 1.29 |
| 8| 6805 | 86.85 | 29.17 | 1.36 |
| 9| 6902 | 95.71 | 32.15 | 1.46 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 1 | 57 | 5868 | 21.66 | 7.37 | 0.64 |
| 10 | 5 | 284 | 6003 | 29.09 | 10.34 | 0.72 |
| 10 | 10 | 568 | 6172 | 39.51 | 14.45 | 0.85 |
| 10 | 20 | 1140 | 6515 | 59.98 | 22.53 | 1.08 |
| 10 | 39 | 2218 | 7158 | 99.82 | 38.19 | 1.55 |

