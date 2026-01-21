--- 
sidebar_label: 'Transaction costs' 
sidebar_position: 3 
--- 

# Transaction costs 

Sizes and execution budgets for Hydra protocol transactions. Note that unlisted parameters are currently using `arbitrary` values and results are not fully deterministic and comparable to previous runs.

| Metadata | |
| :--- | :--- |
| _Generated at_ | 2026-01-21 05:11:24.844429939 UTC |
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
| 1| 5837 | 10.40 | 3.30 | 0.51 |
| 2| 6037 | 12.72 | 4.03 | 0.55 |
| 3| 6236 | 14.40 | 4.55 | 0.57 |
| 5| 6638 | 19.27 | 6.11 | 0.64 |
| 10| 7644 | 28.92 | 9.11 | 0.79 |
| 43| 14285 | 98.78 | 30.87 | 1.80 |


## `Commit` transaction costs
 This uses ada-only outputs for better comparability.

| UTxO | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :--- | ------: | --------: | --------: | --------: |
| 1| 561 | 2.44 | 1.16 | 0.20 |
| 2| 741 | 3.38 | 1.73 | 0.22 |
| 3| 917 | 4.36 | 2.33 | 0.24 |
| 5| 1282 | 6.41 | 3.60 | 0.28 |
| 10| 2183 | 12.13 | 7.25 | 0.40 |
| 54| 10072 | 98.61 | 68.52 | 1.88 |


## `CollectCom` transaction costs

| Parties | UTxO (bytes) |Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :----------- |------: | --------: | --------: | --------: |
| 1 | 57 | 525 | 25.20 | 7.30 | 0.43 |
| 2 | 114 | 636 | 34.23 | 9.85 | 0.53 |
| 3 | 170 | 747 | 41.27 | 11.92 | 0.60 |
| 4 | 227 | 858 | 49.08 | 14.20 | 0.69 |
| 5 | 284 | 969 | 56.22 | 16.33 | 0.76 |
| 6 | 338 | 1085 | 64.84 | 18.83 | 0.86 |
| 7 | 393 | 1192 | 71.41 | 20.68 | 0.93 |
| 8 | 448 | 1307 | 91.57 | 25.90 | 1.13 |


## Cost of Increment Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 1813 | 24.00 | 7.62 | 0.48 |
| 2| 1882 | 24.43 | 8.40 | 0.49 |
| 3| 2059 | 27.40 | 9.88 | 0.53 |
| 5| 2418 | 30.88 | 12.21 | 0.59 |
| 10| 2979 | 37.52 | 17.39 | 0.71 |
| 43| 7806 | 96.90 | 55.88 | 1.68 |


## Cost of Decrement Transaction

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 630 | 22.84 | 7.38 | 0.42 |
| 2| 764 | 23.55 | 8.22 | 0.43 |
| 3| 834 | 24.13 | 9.06 | 0.45 |
| 5| 1334 | 32.39 | 12.70 | 0.56 |
| 10| 1840 | 36.65 | 17.23 | 0.65 |
| 40| 6445 | 93.81 | 53.14 | 1.57 |


## `Close` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 715 | 27.50 | 8.46 | 0.46 |
| 2| 823 | 31.69 | 10.29 | 0.52 |
| 3| 948 | 30.98 | 10.76 | 0.52 |
| 5| 1355 | 35.90 | 13.52 | 0.60 |
| 10| 2129 | 45.45 | 19.54 | 0.75 |
| 34| 5502 | 96.90 | 49.84 | 1.53 |


## `Contest` transaction costs

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 698 | 33.83 | 10.15 | 0.53 |
| 2| 807 | 35.85 | 11.38 | 0.56 |
| 3| 952 | 37.91 | 12.62 | 0.59 |
| 5| 1334 | 43.84 | 15.65 | 0.68 |
| 10| 2012 | 54.10 | 21.82 | 0.83 |
| 29| 4707 | 95.69 | 46.02 | 1.46 |


## `Abort` transaction costs
There is some variation due to the random mixture of initial and already committed outputs.

| Parties | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | ------: | --------: | --------: | --------: |
| 1| 5810 | 27.05 | 9.07 | 0.69 |
| 2| 5951 | 35.93 | 12.06 | 0.79 |
| 3| 6138 | 45.82 | 15.44 | 0.90 |
| 4| 6226 | 50.28 | 16.86 | 0.95 |
| 5| 6326 | 61.99 | 20.80 | 1.08 |
| 6| 6661 | 74.70 | 25.22 | 1.23 |
| 7| 6852 | 83.16 | 28.09 | 1.33 |
| 8| 6933 | 93.39 | 31.41 | 1.44 |


## `FanOut` transaction costs
Involves spending head output and burning head tokens. Uses ada-only UTXO for better comparability.

| Parties | UTxO  | UTxO (bytes) | Tx size | % max Mem | % max CPU | Min fee ₳ |
| :------ | :---- | :----------- | ------: | --------: | --------: | --------: |
| 10 | 0 | 0 | 5835 | 19.19 | 6.41 | 0.61 |
| 10 | 1 | 56 | 5867 | 20.08 | 6.82 | 0.62 |
| 10 | 5 | 284 | 6004 | 30.42 | 10.80 | 0.74 |
| 10 | 10 | 570 | 6174 | 39.06 | 14.30 | 0.84 |
| 10 | 20 | 1137 | 6511 | 59.73 | 22.44 | 1.08 |
| 10 | 30 | 1702 | 6848 | 79.97 | 30.44 | 1.32 |
| 10 | 39 | 2220 | 7159 | 98.05 | 37.58 | 1.53 |

