--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-04-29 06:48:30.309592101 UTC |
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
| 1| 5836 | 10.17 | 3.22 | 0.51 |
| 2| 6037 | 12.23 | 3.86 | 0.54 |
| 3| 6238 | 14.38 | 4.54 | 0.57 |
| 5| 6638 | 19.19 | 6.08 | 0.64 |
| 10| 7646 | 28.92 | 9.11 | 0.79 |
| 43| 14281 | 98.97 | 30.93 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 739 | 3.38 | 1.73 | 0.22 |
| 3| 920 | 4.36 | 2.33 | 0.24 |
| 5| 1283 | 6.41 | 3.60 | 0.28 |
| 10| 2173 | 12.13 | 7.25 | 0.40 |
| 54| 10071 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 58 | 526 | 24.42 | 7.12 | 0.42 |
| 2 | 114 | 636 | 34.20 | 9.84 | 0.53 |
| 3 | 169 | 751 | 41.22 | 11.94 | 0.60 |
| 4 | 225 | 858 | 49.72 | 14.38 | 0.69 |
| 5 | 284 | 974 | 56.04 | 16.26 | 0.76 |
| 6 | 337 | 1081 | 71.77 | 20.46 | 0.93 |
| 7 | 396 | 1192 | 72.04 | 20.83 | 0.93 |
| 8 | 452 | 1303 | 96.49 | 27.23 | 1.18 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1748 | 23.30 | 7.41 | 0.47 |
| 2| 1886 | 24.80 | 8.49 | 0.49 |
| 3| 2131 | 28.35 | 10.15 | 0.55 |
| 5| 2445 | 32.04 | 12.53 | 0.61 |
| 10| 3142 | 40.65 | 18.26 | 0.75 |
| 39| 7502 | 96.19 | 53.03 | 1.64 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 616 | 22.57 | 7.32 | 0.41 |
| 2| 726 | 22.60 | 7.95 | 0.42 |
| 3| 936 | 26.71 | 9.80 | 0.48 |
| 5| 1409 | 33.34 | 12.99 | 0.58 |
| 10| 1996 | 39.50 | 18.04 | 0.69 |
| 40| 6578 | 96.77 | 53.97 | 1.61 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 647 | 29.13 | 8.90 | 0.48 |
| 2| 770 | 28.55 | 9.40 | 0.48 |
| 3| 868 | 32.08 | 11.03 | 0.53 |
| 5| 1232 | 34.41 | 13.05 | 0.58 |
| 10| 2112 | 48.52 | 20.38 | 0.78 |
| 38| 6079 | 98.83 | 53.11 | 1.60 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 670 | 33.83 | 10.15 | 0.53 |
| 2| 840 | 36.18 | 11.48 | 0.56 |
| 3| 999 | 38.66 | 12.84 | 0.60 |
| 5| 1339 | 43.43 | 15.51 | 0.67 |
| 10| 2067 | 54.62 | 21.98 | 0.84 |
| 29| 4959 | 98.58 | 46.87 | 1.50 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5795 | 26.97 | 9.05 | 0.69 |
| 2| 5967 | 35.96 | 12.08 | 0.79 |
| 3| 6153 | 46.03 | 15.52 | 0.90 |
| 4| 6137 | 47.19 | 15.75 | 0.92 |
| 5| 6455 | 60.94 | 20.58 | 1.07 |
| 6| 6744 | 78.06 | 26.38 | 1.27 |
| 7| 6742 | 76.41 | 25.72 | 1.25 |
| 8| 6919 | 94.13 | 31.77 | 1.44 |
| 9| 7012 | 99.97 | 33.76 | 1.51 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5834 | 18.75 | 6.26 | 0.60 |
| 10 | 1 | 57 | 5868 | 21.22 | 7.21 | 0.63 |
| 10 | 10 | 568 | 6172 | 38.18 | 14.00 | 0.83 |
| 10 | 30 | 1710 | 6857 | 80.92 | 30.76 | 1.33 |
| 10 | 39 | 2217 | 7157 | 98.93 | 37.88 | 1.54 |

